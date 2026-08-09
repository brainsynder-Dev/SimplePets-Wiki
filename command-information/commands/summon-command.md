# Summon Command

{% hint style="info" %}
This command players are given access to by <mark style="color:orange;">`DEFAULT`</mark>
{% endhint %}

{% hint style="info" %}
This command can also be run as <mark style="color:green;">`/pet spawn`</mark>
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
> Usage: /pet summon <mark style="color:orange;">`<type>`</mark> <mark style="color:blue;">`[nbt]`</mark>
>
> Usage: /pet summon all
>
> Usage: /pet summon target <mark style="color:orange;">`<player>`</mark> <mark style="color:orange;">`<type>`</mark> <mark style="color:blue;">`[nbt]`</mark>

### Usage Descriptions

| Usage | Description |
| - | - |
| /pet summon <mark style="color:orange;">`<type>`</mark> | <p>Spawns the selected pet type <mark style="color:green;">`(the same as spawning it from the gui)`</mark><br>Example: <mark style="color:green;"><code>/pet summon cow</code></mark></p> |
| /pet summon <mark style="color:orange;">`<type>`</mark> <mark style="color:blue;">`[nbt]`</mark> | <p>Spawns the selected pet type with customized <a href="../../pet-nbt/pet-nbt-tags/">Pet NBT</a><br>Example: <mark style="color:green;"><code>/pet summon cow {baby:true}</code></mark></p> |
| /pet summon all | <p>Spawns every pet type that is available to you<br>Example: <mark style="color:green;"><code>/pet summon all</code></mark></p> |
| /pet summon target <mark style="color:orange;">`<player>`</mark> <mark style="color:orange;">`<type>`</mark> | <p>Spawns the selected pet type for the targeted player<br>Example: <mark style="color:green;"><code>/pet summon target Steve cow</code></mark></p> |
| /pet summon target <mark style="color:orange;">`<player>`</mark> <mark style="color:orange;">`<type>`</mark> <mark style="color:blue;">`[nbt]`</mark> | <p>Spawns the selected pet type for the targeted player with customized <a href="../../pet-nbt/pet-nbt-tags/">Pet NBT</a><br>Example: <mark style="color:green;"><code>/pet summon target Steve cow {baby:true}</code></mark></p> |

## Permissions

| Permission Node | Description |
| - | - |
| pet.commands.summon | Grants the player access to run <mark style="color:red;">`/pet summon`</mark> |
| pet.commands.summon.all | Grants the player access to run <mark style="color:red;">`/pet summon all`</mark> <mark style="color:green;">`(will spawn all pets)`</mark> <mark style="color:orange;">`[IGNORES PERMISSIONS]`</mark> |
| pet.commands.summon.other | Grants the player access to run <mark style="color:red;">`/pet summon target`</mark> so they can spawn pets for other players |
| pet.commands.summon.nbt | Grants the player access to spawn pets with customized data |
