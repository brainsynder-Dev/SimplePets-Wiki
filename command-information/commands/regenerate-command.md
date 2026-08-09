# Regenerate Command

{% hint style="danger" %}
This command is considered an _<mark style="color:red;">**ADMIN ONLY**</mark>_ command\
Ordinary players should _<mark style="color:red;">**NOT**</mark>_ be given access to this command
{% endhint %}

## What does this command do?

Deletes the selected files and generates them again with their default values <mark style="color:green;">`(addon files are ignored)`</mark>.

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
> Usage: /pet regenerate pets
>
> Usage: /pet regenerate inventories
>
> Usage: /pet regenerate items
>
> Usage: /pet regenerate particles
>
> Usage: /pet regenerate type <mark style="color:orange;">`<petType>`</mark>

### Usage Descriptions

| Usage | Description |
| - | - |
| /pet regenerate pets | <p>Regenerates every pet config file<br>Example: <mark style="color:green;"><code>/pet regenerate pets</code></mark></p> |
| /pet regenerate inventories | <p>Regenerates every inventory file<br>Example: <mark style="color:green;"><code>/pet regenerate inventories</code></mark></p> |
| /pet regenerate items | <p>Regenerates every item file<br>Example: <mark style="color:green;"><code>/pet regenerate items</code></mark></p> |
| /pet regenerate particles | <p>Regenerates every particle file<br>Example: <mark style="color:green;"><code>/pet regenerate particles</code></mark></p> |
| /pet regenerate type <mark style="color:orange;">`<petType>`</mark> | <p>Regenerates the config file of the selected pet type only<br>Example: <mark style="color:green;"><code>/pet regenerate type cow</code></mark></p> |

## Permissions

| Permission Node | Description |
| - | - |
| pet.commands.regenerate | Grants the player access to run <mark style="color:red;">`/pet regenerate`</mark> and all of its sub-commands |
