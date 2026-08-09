# Permissions Command

{% hint style="danger" %}
This command is considered an _<mark style="color:red;">**ADMIN ONLY**</mark>_ command\
Ordinary players should _<mark style="color:red;">**NOT**</mark>_ be given access to this command
{% endhint %}

## What does this command do?

Generates a <mark style="color:purple;">`permissions.yml`</mark> file inside the <mark style="color:purple;">`Generated Files`</mark> folder that contains every permission the plugin uses.

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
> Usage: /pet permissions
>
> Usage: /pet permissions dev

### Usage Descriptions

| Usage | Description |
| - | - |
| /pet permissions | <p>Generates the permissions file<br>Example: <mark style="color:green;"><code>/pet permissions</code></mark></p> |
| /pet permissions dev | <p>Generates the permissions file without the wildcard placeholders<br>Example: <mark style="color:green;"><code>/pet permissions dev</code></mark></p> |

## Permissions

| Permission Node | Description |
| - | - |
| pet.commands.permissions | Grants the player access to run <mark style="color:red;">`/pet permissions`</mark> and <mark style="color:red;">`/pet permissions dev`</mark> |
