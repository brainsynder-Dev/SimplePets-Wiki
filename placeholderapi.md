---
description: The PlaceholderAPI placeholders SimplePets provides
---

# PlaceholderAPI

{% hint style="info" %}
PlaceholderAPI support was added in <mark style="color:orange;">`R5-B297`</mark>
{% endhint %}

## Setting it up

There is nothing to enable, if [PlaceholderAPI](https://www.spigotmc.org/resources/6245/) is installed and enabled when the server starts then SimplePets will register its placeholders automatically\
The console will log <mark style="color:green;">`Hooked into PlaceholderAPI`</mark> when that happens

Every placeholder below is under the <mark style="color:purple;">`simplepets`</mark> identifier, and all of them are for the player the placeholder is being parsed for

## Placeholders

| Placeholder                                                                                       | Description                                                                                                                                                                                          | Returns                                                                                       |
| ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------- |
| %simplepets\_has\_pet%                                                                            | <p>Does the player have any pet spawned right now?<br>Example: <mark style="color:green;"><code>%simplepets_has_pet%</code></mark></p>                                                               | <mark style="color:orange;">`true`</mark> / <mark style="color:orange;">`false`</mark>        |
| %simplepets\_has\_spawned\_<mark style="color:orange;">`<type>`</mark>%                           | <p>Does the player have that specific pet type spawned right now?<br>Example: <mark style="color:green;"><code>%simplepets_has_spawned_cow%</code></mark></p>                                        | <mark style="color:orange;">`true`</mark> / <mark style="color:orange;">`false`</mark>        |
| %simplepets\_has\_access\_<mark style="color:orange;">`<type>`</mark>%                            | <p>Is the player able to use that pet type?<br>Example: <mark style="color:green;"><code>%simplepets_has_access_cow%</code></mark></p>                                                               | <mark style="color:orange;">`true`</mark> / <mark style="color:orange;">`false`</mark>        |

<mark style="color:orange;">`<type>`</mark> is the pet type name, the same one you would give to <mark style="color:red;">`/pet summon`</mark> <mark style="color:green;">(a full list can be found with `/pet list`)</mark>

## Things worth knowing

* <mark style="color:green;">`has_access`</mark> counts a purchased pet as accessible, but only when <mark style="color:green;">`Utilize-Purchased-Pets`</mark> is set to <mark style="color:orange;">`true`</mark> in the config.yml. Otherwise it only checks the pets [permission](permissions/pet-permissions/)
* An unknown pet type will always return <mark style="color:orange;">`false`</mark> rather than an error, so double check your spelling if a placeholder is never true
* Placeholders are only parsed for players, there is nothing for the console to resolve them against
