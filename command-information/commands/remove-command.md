# Remove Command

{% hint style="info" %}
This command players are given access to by <mark style="color:orange;">`DEFAULT`</mark>
{% endhint %}

## What does this command do?

Running this command will remove either all your currently spawn pets or it can remove a specific pet type

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
> Usage: /pet remove <mark style="color:blue;">`[player]`</mark> <mark style="color:blue;">`[type]`</mark>

### Usage Descriptions

| Usage                                                                                             | Description                                                                                                                                                                                                  |
| ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| /pet remove                                                                                       | <p>This command will remove all of your currently spawned pets<br><mark style="color:red;"><code></code></mark>Example: <mark style="color:green;"><code>/pet remove</code></mark></p>                       |
| /pet remove <mark style="color:blue;">`[type]`</mark>                                             | <p>This command will remove the selected pet type.<br>Example: <mark style="color:green;"><code>/pet remove cow</code></mark></p>                                                                            |
| /pet remove <mark style="color:blue;">`[player]`</mark>                                           | <p>This command will remove all of the targeted players currently spawned pets<br><mark style="color:red;"><code></code></mark>Example: <mark style="color:green;"><code>/pet remove Steve</code></mark></p> |
| /pet remove <mark style="color:blue;">`[player]`</mark> <mark style="color:blue;">`[type]`</mark> | <p>This command will remove the selected pet type from the targeted player<br>Example: <mark style="color:green;"><code>/pet remove Steve cow</code></mark></p>                                              |

## Permissions

| Permission Node           | Description                                                                                                   |
| ------------------------- | ------------------------------------------------------------------------------------------------------------- |
| pet.commands.remove       | Grants the player access to run <mark style="color:red;">`/pet remove`</mark>                                 |
| pet.commands.remove.other | Grants the player access to remove pets from another player via <mark style="color:red;">`/pet remove`</mark> |
