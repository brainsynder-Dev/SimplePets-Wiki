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

| Usage                                                                                             | Description                                                                 |
| ------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| /pet remove                                                                                       | This command will remove all of your currently spawned pets                 |
| /pet remove <mark style="color:blue;">`[type]`</mark>                                             | This command will remove the selected pet type.                             |
| /pet remove <mark style="color:blue;">`[player]`</mark>                                           | This command will remove all of the targeted players currently spawned pets |
| /pet remove <mark style="color:blue;">`[player]`</mark> <mark style="color:blue;">`[type]`</mark> | This command will remove the selected pet type from the targeted player     |

## Permissions

| Permission Node           | Description                                                                                                                                                                                                                                                                                                                                |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| pet.commands.remove       | <p>Grants the player access to run <mark style="color:red;"><code>/pet remove</code></mark><br><mark style="color:red;"><code></code></mark>Example: <mark style="color:green;"><code>/pet remove</code></mark><br>Example: <mark style="color:green;"><code>/pet remove cow</code></mark></p>                                             |
| pet.commands.remove.other | <p>Grants the player access to remove pets from another player via <mark style="color:red;"><code>/pet remove</code></mark><br><mark style="color:red;"><code></code></mark>Example: <mark style="color:green;"><code>/pet remove Steve</code></mark><br>Example: <mark style="color:green;"><code>/pet remove Steve cow</code></mark></p> |
