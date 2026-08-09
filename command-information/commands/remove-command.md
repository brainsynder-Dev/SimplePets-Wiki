# Remove Command

{% hint style="info" %}
This command players are given access to by <mark style="color:orange;">`DEFAULT`</mark>
{% endhint %}

## What does this command do?

Running this command will remove either all your currently spawned pets or it can remove a specific pet type

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
> Usage: /pet remove <mark style="color:blue;">`[type]`</mark>
>
> Usage: /pet remove target <mark style="color:orange;">`<player>`</mark> <mark style="color:blue;">`[type]`</mark>

### Usage Descriptions

| Usage | Description |
| - | - |
| /pet remove | <p>Removes all of your currently spawned pets<br>Example: <mark style="color:green;"><code>/pet remove</code></mark></p> |
| /pet remove <mark style="color:blue;">`[type]`</mark> | <p>Removes the selected pet type<br>Example: <mark style="color:green;"><code>/pet remove cow</code></mark></p> |
| /pet remove target <mark style="color:orange;">`<player>`</mark> | <p>Removes all of the targeted players currently spawned pets<br>Example: <mark style="color:green;"><code>/pet remove target Steve</code></mark></p> |
| /pet remove target <mark style="color:orange;">`<player>`</mark> <mark style="color:blue;">`[type]`</mark> | <p>Removes the selected pet type from the targeted player<br>Example: <mark style="color:green;"><code>/pet remove target Steve cow</code></mark></p> |

## Permissions

| Permission Node | Description |
| - | - |
| pet.commands.remove | Grants the player access to run <mark style="color:red;">`/pet remove`</mark> |
| pet.commands.remove.other | Grants the player access to run <mark style="color:red;">`/pet remove target`</mark> so they can remove another players pets |
