# Database Command

{% hint style="danger" %}
This command is considered an _<mark style="color:red;">**ADMIN ONLY**</mark>_ command\
Ordinary players should _<mark style="color:red;">**NOT**</mark>_ be given access to this command
{% endhint %}

## What does this command do?

Shows information about the database the plugin is storing the pet data in, and lets you clean it up.

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
> Usage: /pet database
>
> Usage: /pet database findduplicates
>
> Usage: /pet database removeduplicates
>
> Usage: /pet database removenpcs

### Usage Descriptions

| Usage | Description |
| - | - |
| /pet database | <p>Shows the database type, its connection status, and how many players are stored in it<br>Example: <mark style="color:green;"><code>/pet database</code></mark></p> |
| /pet database findduplicates | <p>Fetches a list of all the duplicate players in the database<br>Example: <mark style="color:green;"><code>/pet database findduplicates</code></mark></p> |
| /pet database removeduplicates | <p>Clears the database of all the duplicate players<br>Example: <mark style="color:green;"><code>/pet database removeduplicates</code></mark></p> |
| /pet database removenpcs | <p>Clears the database of any NPC/offline UUIDs<br>Example: <mark style="color:green;"><code>/pet database removenpcs</code></mark></p> |

## Permissions

| Permission Node | Description |
| - | - |
| pet.commands.database | Grants the player access to run <mark style="color:red;">`/pet database`</mark> |
| pet.commands.database.findduplicates | Grants the player access to run <mark style="color:red;">`/pet database findduplicates`</mark> |
| pet.commands.database.removeduplicates | Grants the player access to run <mark style="color:red;">`/pet database removeduplicates`</mark> |
| pet.commands.database.removenpcs | Grants the player access to run <mark style="color:red;">`/pet database removenpcs`</mark> |
