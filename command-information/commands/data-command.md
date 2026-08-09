# Data Command

{% hint style="info" %}
This command players are given access to by <mark style="color:orange;">`DEFAULT`</mark>
{% endhint %}

## What does this command do?

Opens the GUI that will allow you to modify the pet you have specified

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
> Usage: /pet data <mark style="color:orange;">`<type>`</mark>
>
> Usage: /pet data target <mark style="color:blue;">`[player]`</mark> <mark style="color:orange;">`<type>`</mark>

### Usage Descriptions

| Usage | Description |
| - | - |
| /pet data <mark style="color:orange;">`<type>`</mark> | <p>Opens the GUI to modify the selected pet types data<br>Example: <mark style="color:green;"><code>/pet data cow</code></mark></p> |
| /pet data target <mark style="color:orange;">`<type>`</mark> | <p>Opens the data GUI for your own pet, the same as running the command without <mark style="color:green;">`target`</mark><br>Example: <mark style="color:green;"><code>/pet data target cow</code></mark></p> |
| /pet data target <mark style="color:blue;">`[player]`</mark> <mark style="color:orange;">`<type>`</mark> | <p>Forces the targeted player to open the selected pet types data GUI<br>Example: <mark style="color:green;"><code>/pet data target Steve cow</code></mark></p> |

## Permissions

| Permission Node | Description |
| - | - |
| pet.commands.data | Grants the player access to run <mark style="color:red;">`/pet data`</mark> |
| pet.commands.data.target | Grants the player access to run <mark style="color:red;">`/pet data target`</mark> |
| pet.commands.data.other | Grants the player access to force another player to open their Pet Data <mark style="color:red;">`/pet data target [player] <type>`</mark> |
