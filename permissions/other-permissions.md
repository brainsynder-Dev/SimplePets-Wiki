# Other Permissions

{% hint style="warning" %}
This page is still being worked on and is not 100% complete
{% endhint %}

### All Access Pet Permissions

| Permission            | Description                                                                                                                                                     |
| --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| pet.type.\*           | Grants access to _<mark style="color:red;">**`ALL`**</mark>_ pets and their data (customization)                                                                |
| pet.type.passive      | <p>Grants access to all pets that would be passive in vanilla Minecraft<br><mark style="color:green;"><code>(Includes their data permissions)</code></mark></p> |
| pet.type.hostile      | <p>Grants access to all pets that would be hostile in vanilla Minecraft<br><mark style="color:green;"><code>(Includes their data permissions)</code></mark></p> |
| pet.type.\*_.data.\*_ | Grants access to _<mark style="color:red;">**`ALL`**</mark>_ pet data customization for _<mark style="color:red;">**`ALL`**</mark>_ pets                        |

### Pet Renaming

| Permission         | Description                                                                                                                                                                |
| ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| pet.name.bypass    | This permission bypasses any of the pet renaming checks                                                                                                                    |
| pet.name.color     | <p>This permission is to allow players to add color codes when renaming their pet<br>Example: <mark style="color:green;"><code>&#x26;cNew Name</code></mark></p>           |
| pet.name.color.hex | <p>This permission is to allow players to add HEX color codes when renaming their pet<br>Example: <mark style="color:green;"><code>&#x26;#d05454New Name</code></mark></p> |

### Miscellaneous Permissions

| Permission                                                                                        | Description                                                                                                                                                                                                                                                                                                     |
| ------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| pet.update                                                                                        | <p>Allows the player who has this permission to get notified when there is a plugin update.<br><mark style="color:green;"><code>(OP players get alerted no mater what)</code></mark></p>                                                                                                                        |
| pet.amount.bypass                                                                                 | This permission bypasses the limit of how many pets can be spawned                                                                                                                                                                                                                                              |
| pet.amount.<mark style="color:blue;">`{number}`</mark>                                            | <p>This permission sets how many pets the player can have spawned<br>Example: <mark style="color:green;"><code>pet.amount.5</code></mark> means they can spawn 5 pets at once </p><p><br><em><mark style="color:red;"><strong>NOTE:</strong></mark></em> Higher numbers take priority</p>                       |
| pet.saves.bypass                                                                                  | This permission bypasses the limit of how many pets can be saved                                                                                                                                                                                                                                                |
| pet.saves.<mark style="color:blue;">`{number}`</mark>                                             | <p>This permission sets how many pets the player can have saved<br>Example: <mark style="color:green;"><code>pet.saves.5</code></mark> means they can save 5 pets</p><p><br><em><mark style="color:red;"><strong>NOTE:</strong></mark></em> Higher numbers take priority</p>                                    |
| pet.saves.<mark style="color:orange;">`{type}`</mark>.bypass                                      | This permission bypasses the limit of how many of a certain type of pet can be saved                                                                                                                                                                                                                            |
| pet.saves.<mark style="color:orange;">`{type}`</mark>.<mark style="color:blue;">`{number}`</mark> | <p>This permission sets how many of a certain pet type the player can have saved<br>Example: <mark style="color:green;"><code>pet.saves.cow.5</code></mark> means they can save 5 different cow pets</p><p><br><em><mark style="color:red;"><strong>NOTE:</strong></mark></em> Higher numbers take priority</p> |

