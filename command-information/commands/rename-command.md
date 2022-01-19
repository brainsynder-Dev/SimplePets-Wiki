# Rename Command

{% hint style="info" %}
This command players are given access to by <mark style="color:orange;">`DEFAULT`</mark>
{% endhint %}

## What does this command do?

Running this command will allow the player to change what their pets name is

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
>
>
> Usage: /pet rename <mark style="color:blue;">`[player]`</mark> <mark style="color:orange;">`<type>`</mark> <mark style="color:blue;">`[name]`</mark>

### Usage Descriptions

| Usage                                                                                                                                         | Description                                                                                                                                                                                                                                                                                                                                                                                                             |
| --------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /pet rename <mark style="color:orange;">`<type>`</mark> <mark style="color:blue;">`[name]`</mark>                                             | <p>This command will <mark style="color:green;">(depending on the config option)</mark> open a GUI that will allow the player to rename the targeted pet type<br>Example: <mark style="color:green;"><code>/pet rename cow</code></mark><br>Example: <mark style="color:green;"><code>/pet rename cow MooMoo</code></mark> (Will only work if the rename type is set to <mark style="color:purple;">COMMAND</mark>)</p> |
| /pet rename <mark style="color:blue;">`[player]`</mark> <mark style="color:orange;">`<type>`</mark> <mark style="color:blue;">`[name]`</mark> | <p>This command will change the targeted players pet to have the new custom name <mark style="color:green;">(bypasses the RenameType)</mark><br><mark style="color:green;"></mark><br><mark style="color:green;"></mark>Example: <mark style="color:green;"><code>/pet rename Steve cow MooMoo</code></mark></p>                                                                                                        |

## Permissions

| Permission Node          | Description                                                                                                 |
| ------------------------ | ----------------------------------------------------------------------------------------------------------- |
| pet.commands.rename      | Grants the player access to run <mark style="color:red;">`/pet rename`</mark>                               |
| pet.command.rename.other | Grants the player access to change other players pet name via <mark style="color:red;">`/pet rename`</mark> |
