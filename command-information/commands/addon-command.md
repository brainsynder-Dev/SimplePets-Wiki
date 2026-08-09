# Addon Command

{% hint style="danger" %}
This command is considered an _<mark style="color:red;">**ADMIN ONLY**</mark>_ command\
Ordinary players should _<mark style="color:red;">**NOT**</mark>_ be given access to this command
{% endhint %}

## What does this command do?

Opens the GUI that lists every addon, letting you download new ones and toggle the installed ones.

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
> Usage: /pet addon
>
> Usage: /pet addon install <mark style="color:orange;">`<addon>`</mark>
>
> Usage: /pet addon update <mark style="color:orange;">`<addon>`</mark>
>
> Usage: /pet addon reload

### Usage Descriptions

| Usage | Description |
| - | - |
| /pet addon | <p>Opens the addon GUI <mark style="color:green;">`(players only)`</mark><br>Example: <mark style="color:green;"><code>/pet addon</code></mark></p> |
| /pet addon install <mark style="color:orange;">`<addon>`</mark> | <p>Downloads and installs an addon from our database, the addon can not already be installed<br>Example: <mark style="color:green;"><code>/pet addon install WorldGuard</code></mark></p> |
| /pet addon update <mark style="color:orange;">`<addon>`</mark> | <p>Updates an installed addon to the latest version<br>Example: <mark style="color:green;"><code>/pet addon update WorldGuard</code></mark></p> |
| /pet addon reload | <p>Unloads every addon, then loads them again from the addons folder<br>Example: <mark style="color:green;"><code>/pet addon reload</code></mark></p> |

## Permissions

| Permission Node | Description |
| - | - |
| pet.commands.addon | Grants the player access to run <mark style="color:red;">`/pet addon`</mark> |
| pet.commands.addon.install | Grants the player access to run <mark style="color:red;">`/pet addon install`</mark> |
| pet.commands.addon.update | Grants the player access to run <mark style="color:red;">`/pet addon update`</mark> |
| pet.commands.addon.reload | Grants the player access to run <mark style="color:red;">`/pet addon reload`</mark> |
