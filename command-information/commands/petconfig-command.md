# PetConfig Command

{% hint style="danger" %}
This command is considered an _<mark style="color:red;">**ADMIN ONLY**</mark>_ command\
Ordinary players should _<mark style="color:red;">**NOT**</mark>_ be given access to this command
{% endhint %}

## What does this command do?

Changes a value inside a pet types config file without you having to edit the file and reload the plugin.

Only the keys that hold a single value can be changed this way, and tab completion will only list those keys.

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
> Usage: /pet petconfig <mark style="color:orange;">`<type>`</mark> <mark style="color:orange;">`<key>`</mark> <mark style="color:orange;">`<value>`</mark>

### Usage Descriptions

| Usage | Description |
| - | - |
| /pet petconfig <mark style="color:orange;">`<type>`</mark> <mark style="color:orange;">`<key>`</mark> <mark style="color:orange;">`<value>`</mark> | <p>Sets the key in the selected pet types config file to the new value<br>Example: <mark style="color:green;"><code>/pet petconfig cow hat false</code></mark></p> |
| /pet petconfig <mark style="color:orange;">`<type>`</mark> <mark style="color:orange;">`<key>`</mark> reset | <p>Sets the key back to its default value<br>Example: <mark style="color:green;"><code>/pet petconfig cow hat reset</code></mark></p> |

## Permissions

| Permission Node | Description |
| - | - |
| pet.commands.petconfig | Grants the player access to run <mark style="color:red;">`/pet petconfig`</mark> |
