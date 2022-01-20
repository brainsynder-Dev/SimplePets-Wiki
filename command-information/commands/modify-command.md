# Modify Command

{% hint style="warning" %}
This command could allow players to modify their pets information
{% endhint %}

## What does this command do?

This command allows you to modify the targeted pet type, Some of the pets have 'HIDDEN' pet data that can only be accessed via this command (EG: health & carried\_block)

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
> Usage: /pet modify <mark style="color:blue;">`[player]`</mark> <mark style="color:orange;">`<type>`</mark> <mark style="color:orange;">`<nbt>`</mark>

### Usage Descriptions

| Usage                                                                                                                                          | Description                                                                                                                                                                                                                                                                             |
| ---------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /pet modify <mark style="color:orange;">`<type>`</mark> <mark style="color:orange;">`<nbt>`</mark>                                             | <p>This will allow you to modify your targeted pet type with the data you put via customized <a href="../../pet-nbt/pet-nbt-tags/">Pet NBT</a><br><br>nbt is in a similar structure to JSON<br>Find out more <a href="https://minecraft.fandom.com/wiki/NBT_format">HERE</a></p>        |
| /pet modify <mark style="color:blue;">`[player]`</mark> <mark style="color:orange;">`<type>`</mark> <mark style="color:orange;">`<nbt>`</mark> | <p>This will allow you to modify the targeted players pet type with the data you put via customized <a href="../../pet-nbt/pet-nbt-tags/">Pet NBT</a><br><br>nbt is in a similar structure to JSON<br>Find out more <a href="https://minecraft.fandom.com/wiki/NBT_format">HERE</a></p> |

## Permissions

| Permission Node           | Description                                                                                             |
| ------------------------- | ------------------------------------------------------------------------------------------------------- |
| pet.commands.modify       | Grants the player access to run <mark style="color:red;">`/pet modify`</mark>                           |
| pet.commands.modify.other | Grants the player access to modify other players pets via <mark style="color:red;">`/pet modify`</mark> |
