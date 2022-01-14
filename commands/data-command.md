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
>
>
> Usage: /pet data <mark style="color:blue;">`[player]`</mark> <mark style="color:orange;">`<type>`</mark>

### Usage Descriptions

| Usage                                                                                             | Description                                                                                                                                              |
| ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /pet data <mark style="color:orange;">`<type>`</mark>                                             | <p>Opens the GUI to modify the selected pet types data<br>Example: <mark style="color:green;"><code>/pet data cow</code></mark></p>                      |
| /pet data <mark style="color:blue;">`[player]`</mark> <mark style="color:orange;">`<type>`</mark> | <p>Forces the targeted player to open the selected pet types data GUI<br>Example: <mark style="color:green;"><code>/pet data Steve cow</code></mark></p> |

## Permissions

| Permission Node         | Description                                                                                                                  |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| pet.commands.data       | Grants the player access to run <mark style="color:red;">`/pet data`</mark>                                                  |
| pet.commands.data.other | Grants the player access to force another player to open their Pet Data <mark style="color:red;">`/pet data [player]`</mark> |
