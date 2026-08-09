# Purchased Command

{% hint style="danger" %}
This command is considered an _<mark style="color:red;">**ADMIN ONLY**</mark>_ command\
Ordinary players should _<mark style="color:red;">**NOT**</mark>_ be given access to this command
{% endhint %}

## What does this command do?

Controls which pets a player has purchased, purchased pets can be used without the player having the pets permission.

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
> Usage: /pet purchased add <mark style="color:orange;">`<player>`</mark> <mark style="color:orange;">`<type>`</mark>
>
> Usage: /pet purchased remove <mark style="color:orange;">`<player>`</mark> <mark style="color:orange;">`<type>`</mark>
>
> Usage: /pet purchased list <mark style="color:blue;">`[player]`</mark>

### Usage Descriptions

| Usage | Description |
| - | - |
| /pet purchased add <mark style="color:orange;">`<player>`</mark> <mark style="color:orange;">`<type>`</mark> | <p>Adds the pet type to the targeted players purchased pets<br>Example: <mark style="color:green;"><code>/pet purchased add Steve cow</code></mark></p> |
| /pet purchased remove <mark style="color:orange;">`<player>`</mark> <mark style="color:orange;">`<type>`</mark> | <p>Removes the pet type from the targeted players purchased pets<br>Example: <mark style="color:green;"><code>/pet purchased remove Steve cow</code></mark></p> |
| /pet purchased list | <p>Lists your own purchased pets<br>Example: <mark style="color:green;"><code>/pet purchased list</code></mark></p> |
| /pet purchased list <mark style="color:blue;">`[player]`</mark> | <p>Lists the targeted players purchased pets<br>Example: <mark style="color:green;"><code>/pet purchased list Steve</code></mark></p> |

## Permissions

| Permission Node | Description |
| - | - |
| pet.commands.purchased | Grants the player access to run <mark style="color:red;">`/pet purchased`</mark> |
| pet.commands.purchased.add | Grants the player access to run <mark style="color:red;">`/pet purchased add`</mark> |
| pet.commands.purchased.remove | Grants the player access to run <mark style="color:red;">`/pet purchased remove`</mark> |
| pet.commands.purchased.list | Grants the player access to run <mark style="color:red;">`/pet purchased list`</mark> |
| pet.commands.purchased.list.other | Grants the player access to list another players purchased pets <mark style="color:red;">`/pet purchased list [player]`</mark> |
