# GUI Command

{% hint style="info" %}
This command players are given access to by <mark style="color:orange;">`DEFAULT`</mark>
{% endhint %}

{% hint style="info" %}
This command can be disabled by setting <mark style="color:green;">`"Simpler-Pet-GUI-Command"`</mark> to <mark style="color:orange;">`true`</mark>

The command would then be simplified to just <mark style="color:green;">`/pet`</mark>
{% endhint %}

## What does this command do?

Opens the GUI that allows you to spawn a pet

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
> Usage: /pet gui <mark style="color:blue;">`[player]`</mark>

### Usage Descriptions

| Usage | Description |
| - | - |
| /pet gui | <p>Opens the Pet Selection GUI so you can spawn pets<br>Example: <mark style="color:green;"><code>/pet gui</code></mark></p> |
| /pet gui <mark style="color:blue;">`[player]`</mark> | <p>Forces the Pet Selection GUI to open for the selected player<br>Example: <mark style="color:green;"><code>/pet gui Steve</code></mark></p> |

## Permissions

| Permission Node | Description |
| - | - |
| pet.commands.gui | Grants the player access to run <mark style="color:red;">`/pet gui`</mark> |
| pet.commands.gui.other | Grants the player access to force another player to open the Pet Selection GUI <mark style="color:red;">`/pet gui [player]`</mark> |
