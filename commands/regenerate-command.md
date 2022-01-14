# Regenerate Command

{% hint style="danger" %}
This command is considered an _<mark style="color:red;">**ADMIN ONLY**</mark>_ command\
Ordinary players should _<mark style="color:red;">**NOT**</mark>_ be given access to this command
{% endhint %}

## What does this command do?

Running this command will regenerate the files/folder they specify to their default state (In other terms reset the file and have it recreated)

{% hint style="danger" %}
I would <mark style="color:red;">**`STRONGLY`**</mark> suggest only trusted players have access to this command as it could reset pet files, inventory configurations, item configurations, and particle files
{% endhint %}

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
>
>
> Usage: /pet regenerate <mark style="color:orange;">`<selector>`</mark> <mark style="color:blue;">`[type]`</mark>

### Usage Descriptions

| Usage                                                                                                     | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /pet regenerate <mark style="color:orange;">`<selector>`</mark> <mark style="color:blue;">`[type]`</mark> | <p>If you did not read above for what this command does <a href="regenerate-command.md#what-does-this-command-do">CLICK HERE</a> <br><br>Selectors can be: <mark style="color:purple;"><code>pets</code></mark>, <mark style="color:purple;"><code>inventories</code></mark>, <mark style="color:purple;"><code>items</code></mark>, <mark style="color:purple;"><code>particles</code></mark>, and/or <mark style="color:purple;"><code>type</code></mark>(pet type)<br>Example: <mark style="color:green;">/pet regenerate pets</mark><br>Example: <mark style="color:green;">/pet regenerate type cow</mark></p> |

## Permissions

| Permission Node         | Description                                                                       |
| ----------------------- | --------------------------------------------------------------------------------- |
| pet.commands.regenerate | Grants the player access to run <mark style="color:red;">`/pet regenerate`</mark> |
