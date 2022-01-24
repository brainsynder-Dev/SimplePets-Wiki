# Summon Command

{% hint style="info" %}
This command players are given access to by <mark style="color:orange;">`DEFAULT`</mark>
{% endhint %}

{% hint style="warning" %}
This command could allow players to modify their pets default information
{% endhint %}

## What does this command do?

Running this command will spawn in the targeted pet type for the player.

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
> Usage: /pet summon <mark style="color:orange;">`<type>`</mark> <mark style="color:blue;">`[player]`</mark> <mark style="color:blue;">`[nbt]`</mark>

### Usage Descriptions

| Usage                                                                                                                                        | Description                                                                                                                                                                                                                                 |
| -------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /pet summon <mark style="color:orange;">`<type>`</mark>                                                                                      | <p>This command will spawn the selected pet type (will be similar to spawning it from the gui)<br>Example: <mark style="color:green;"><code>/pet summon cow</code></mark></p>                                                               |
| /pet summon <mark style="color:orange;">`<type>`</mark> <mark style="color:blue;">`[nbt]`</mark>                                             | <p>This command will spawn the selected pet type with customized <a href="../../pet-nbt/pet-nbt-tags/">Pet NBT</a><br>Example: <mark style="color:green;"><code>/pet summon cow {baby:true}</code></mark></p>                               |
| /pet summon <mark style="color:orange;">`<type>`</mark> <mark style="color:blue;">`[player]`</mark>                                          | <p>This command will spawn the selected pet type for the targeted player<br>Example: <mark style="color:green;"><code>/pet summon cow Steve</code></mark></p>                                                                               |
| /pet summon <mark style="color:orange;">`<type>`</mark> <mark style="color:blue;">`[player]`</mark> <mark style="color:blue;">`[nbt]`</mark> | <p>This command will spawn the selected pet type for the targeted player with customized <a href="../../pet-nbt/pet-nbt-tags/">Pet NBT</a><br>Example: <mark style="color:green;"><code>/pet summon cow Steve {baby:true}</code></mark></p> |

## Permissions

| Permission Node           | Description                                                                                                                                                                                        |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| pet.commands.summon       | Grants the player access to run <mark style="color:red;">`/pet summon`</mark>                                                                                                                      |
| pet.commands.summon.all   | Grants the player access to <mark style="color:red;">`/pet summon all`</mark> <mark style="color:green;">`(will spawn all pets)`</mark> <mark style="color:orange;">`[IGNORES PERMISSIONS]`</mark> |
| pet.commands.summon.other | Grants the player access to summon pets for other players using <mark style="color:red;">`/pet summon`</mark>                                                                                      |
| pet.commands.summon.nbt   | Grants the player access to spawn pets with customized data                                                                                                                                        |
