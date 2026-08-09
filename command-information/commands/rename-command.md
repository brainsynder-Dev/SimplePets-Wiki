# Rename Command

{% hint style="info" %}
This command players are given access to by <mark style="color:orange;">`DEFAULT`</mark>
{% endhint %}

{% hint style="warning" %}
This command is only registered when <mark style="color:green;">`Rename-Enabled`</mark> is set to <mark style="color:orange;">`true`</mark> in the config.yml
{% endhint %}

## What does this command do?

Renames the selected pet type, leaving the name out will open whichever rename method the <mark style="color:green;">`Rename-Type`</mark> config option is set to <mark style="color:green;">`(anvil, chat, sign, or dialog)`</mark>.

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
> Usage: /pet rename <mark style="color:orange;">`<type>`</mark> <mark style="color:blue;">`[name]`</mark>
>
> Usage: /pet rename target <mark style="color:orange;">`<player>`</mark> <mark style="color:orange;">`<type>`</mark> <mark style="color:blue;">`[name]`</mark>

### Usage Descriptions

| Usage | Description |
| - | - |
| /pet rename <mark style="color:orange;">`<type>`</mark> | <p>Opens the rename method set in the config for that pet type<br>Example: <mark style="color:green;"><code>/pet rename cow</code></mark></p> |
| /pet rename <mark style="color:orange;">`<type>`</mark> <mark style="color:blue;">`[name]`</mark> | <p>Renames the pet type to the name given<br>Example: <mark style="color:green;"><code>/pet rename cow Bessie</code></mark></p> |
| /pet rename target <mark style="color:orange;">`<player>`</mark> <mark style="color:orange;">`<type>`</mark> | <p>Opens the rename method for the targeted players pet type<br>Example: <mark style="color:green;"><code>/pet rename target Steve cow</code></mark></p> |
| /pet rename target <mark style="color:orange;">`<player>`</mark> <mark style="color:orange;">`<type>`</mark> <mark style="color:blue;">`[name]`</mark> | <p>Renames the targeted players pet type to the name given<br>Example: <mark style="color:green;"><code>/pet rename target Steve cow Bessie</code></mark></p> |

## Permissions

| Permission Node | Description |
| - | - |
| pet.commands.rename | Grants the player access to run <mark style="color:red;">`/pet rename`</mark> |
| pet.commands.rename.other | Grants the player access to run <mark style="color:red;">`/pet rename target`</mark> so they can rename another players pet |
