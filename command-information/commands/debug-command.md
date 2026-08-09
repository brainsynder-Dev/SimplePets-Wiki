# Debug Command

{% hint style="danger" %}
This command is considered an _<mark style="color:red;">**ADMIN ONLY**</mark>_ command\
Ordinary players should _<mark style="color:red;">**NOT**</mark>_ be given access to this command
{% endhint %}

## What does this command do?

Collects the plugin/server information we need when looking into an issue, then uploads it and gives you the link.

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
> Usage: /pet debug
>
> Usage: /pet debug skip
>
> Usage: /pet debug pet

### Usage Descriptions

| Usage | Description |
| - | - |
| /pet debug | <p>Generates the debug information and uploads it<br>Example: <mark style="color:green;"><code>/pet debug</code></mark></p> |
| /pet debug skip | <p>Generates the debug information without running the Jenkins build check<br>Example: <mark style="color:green;"><code>/pet debug skip</code></mark></p> |
| /pet debug pet | <p>Generates the debug information for the pets you currently have spawned <mark style="color:green;">`(players only)`</mark><br>Example: <mark style="color:green;"><code>/pet debug pet</code></mark></p> |

## Permissions

| Permission Node | Description |
| - | - |
| pet.commands.debug | Grants the player access to run <mark style="color:red;">`/pet debug`</mark> and all of its sub-commands |
