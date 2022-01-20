# Purchased Command

{% hint style="danger" %}
This command is considered an _<mark style="color:red;">**ADMIN ONLY**</mark>_ command\
Ordinary players should _<mark style="color:red;">**NOT**</mark>_ be given access to this command
{% endhint %}

## What does this command do?

This command will allow you to control/view what pets the player has purchased <mark style="color:green;">(or has access to)</mark>

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
> Usage: /pet permissions add <mark style="color:orange;">`<player>`</mark> <mark style="color:orange;">`<type>`</mark>
>
> Usage: /pet permissions remove <mark style="color:orange;">`<player>`</mark> <mark style="color:orange;">`<type>`</mark>
>
> Usage: /pet permissions list <mark style="color:orange;">`<player>`</mark>

### Usage Descriptions

| Usage                                                                                                             | Description                                                                          |
| ----------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| /pet permissions add <mark style="color:orange;">`<player>`</mark> <mark style="color:orange;">`<type>`</mark>    | This command allows you to add pets to the targeted players purchased pets list      |
| /pet permissions remove <mark style="color:orange;">`<player>`</mark> <mark style="color:orange;">`<type>`</mark> | This command allows you to remove pets from the targeted players purchased pets list |
| /pet permissions list <mark style="color:orange;">`<player>`</mark>                                               | Allows you to view a list of all the pets the targeted player has purchased          |

## Permissions

| Permission Node                   | Description                                                                                                                    |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| pet.commands.purchased            | Grants the player access to run <mark style="color:red;">`/pet purchased`</mark>                                               |
| pet.commands.purchased.add        | Grants the player access to add pets to a targeted player via <mark style="color:red;">`/pet purchased add`</mark>             |
| pet.commands.purchased.remove     | Grants the player access to remove pets to a targeted player via <mark style="color:red;">`/pet purchased remove`</mark>       |
| pet.commands.purchased.list       | Grants the player access to view their  purchased pets via <mark style="color:red;">`/pet purchased list`</mark>               |
| pet.commands.purchased.list.other | Grants the player access to view purchased pets of a targeted player via <mark style="color:red;">`/pet purchased list`</mark> |
