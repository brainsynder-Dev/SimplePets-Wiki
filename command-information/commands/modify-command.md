# Modify Command

{% hint style="danger" %}
This command is considered an _<mark style="color:red;">**ADMIN ONLY**</mark>_ command\
Ordinary players should _<mark style="color:red;">**NOT**</mark>_ be given access to this command
{% endhint %}

## What does this command do?

Applies [Pet NBT](../../pet-nbt/pet-nbt-tags/) to a pet that is already spawned, without having to respawn it.

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
> Usage: /pet modify <mark style="color:orange;">`<type>`</mark> <mark style="color:orange;">`<nbt>`</mark>
>
> Usage: /pet modify target <mark style="color:orange;">`<player>`</mark> <mark style="color:orange;">`<type>`</mark> <mark style="color:orange;">`<nbt>`</mark>

### Usage Descriptions

| Usage | Description |
| - | - |
| /pet modify <mark style="color:orange;">`<type>`</mark> <mark style="color:orange;">`<nbt>`</mark> | <p>Applies the NBT to your own spawned pet of that type<br>Example: <mark style="color:green;"><code>/pet modify cow {baby:true}</code></mark></p> |
| /pet modify target <mark style="color:orange;">`<player>`</mark> <mark style="color:orange;">`<type>`</mark> <mark style="color:orange;">`<nbt>`</mark> | <p>Applies the NBT to the targeted players spawned pet of that type<br>Example: <mark style="color:green;"><code>/pet modify target Steve cow {baby:true}</code></mark></p> |

## Permissions

| Permission Node | Description |
| - | - |
| pet.commands.modify | Grants the player access to run <mark style="color:red;">`/pet modify`</mark> |
| pet.commands.modify.other | Grants the player access to run <mark style="color:red;">`/pet modify target`</mark> so they can modify another players pet |
