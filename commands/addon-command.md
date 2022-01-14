# Addon Command

{% hint style="danger" %}
This command is considered an _<mark style="color:red;">**ADMIN ONLY**</mark>_ command\
Ordinary players should _<mark style="color:red;">**NOT**</mark>_ be given access to this command
{% endhint %}

## What does this command do?

This command opens a GUI that allows you to toggle already installed addons, or allows you to install addons from our database

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
>
>
> Usage: /pet addon <mark style="color:blue;">`[reload]`</mark>

### Usage Descriptions

|                   | Description                                                                                                                                                                                 |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /pet addon        | The GUI that opened shows all the addons currently installed on your server.                                                                                                                |
| /pet addon reload | <p>Reloads <mark style="color:red;"><strong>ALL</strong></mark> the addons currently installed<br><mark style="color:green;"><code>(Used for reloading addon config data)</code></mark></p> |

## Permissions

| Permission Node            | Description                                                                                           |
| -------------------------- | ----------------------------------------------------------------------------------------------------- |
| pet.commands.addon         | Grants the player access to run <mark style="color:red;">`/pet addon`</mark>                          |
| pet.commands..addon.reload | Grants the player access to reload the addons via <mark style="color:red;">`/pet addon reload`</mark> |
