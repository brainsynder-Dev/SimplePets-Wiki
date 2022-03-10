# Pet JSON Commands

## When are the commands run?

The commands you add have different 'reasons' for when they are run, These reasons are listed below:

* <mark style="color:blue;">`SPAWN`</mark> - Will run the commands listed when the pet is spawned
* <mark style="color:blue;">`REVOKE`</mark> - Will run the commands listed when the pet is removed
* <mark style="color:blue;">`RIDE`</mark> - Will run the commands listed when the player mounts the pet
* <mark style="color:blue;">`RIDE_DISMOUNT`</mark> - Will run the commands listed when the player dismounts off the pet
* <mark style="color:blue;">`HAT`</mark> - Will run the commands listed when the pet is put on the players head
* <mark style="color:blue;">`TELEPORT`</mark> - Will run the commands listed when the pet teleports
* <mark style="color:blue;">`FAILED`</mark> - Will run the commands listed when a task for the pet fails to run <mark style="color:green;">`(like failed spawning)`</mark>

## Command Placeholders

We have added some placeholders to the pet commands, there could always be more added but these are the current ones added:

| Placeholder | Description                                                                      |
| :---------: | -------------------------------------------------------------------------------- |
|    {petX}   | This is the X coordinate of the pet                                              |
|    {petY}   | This is the Y coordinate of the pet                                              |
|    {petZ}   | This is the Z coordinate of the pet                                              |
|   {ownerX}  | This is the X coordinate of pets owner                                           |
|   {ownerY}  | This is the Y coordinate of pets owner                                           |
|   {ownerZ}  | This is the Z coordinate of pets owner                                           |
| {ownerName} | This is the name for the player who spawned the pet                              |
|  {petName}  | This is the pets display name                                                    |
|  {petType}  | This is the type of pet <mark style="color:green;">`(EG: COW, PIG, ETC.)`</mark> |
|  {petUUID}  | The UUID for the pet                                                             |

## Some examples of how to add commands

```json
  "commands": {
    "SPAWN": [
      "say {ownerName} has spawned the {petType} pet"
    ],
    "REVOKE": [
      "say {ownerName} has removed the {petType} pet",
      "tell {ownerName} would you like to spawn another? Type /pet gui"
    ],
    "RIDE": [
      
    ],
    "RIDE_DISMOUNT": [
      
    ],
    "HAT": [
      
    ],
    "TELEPORT": [
      
    ],
    "FAILED": [
      "tell {ownerName} An error occurred when trying this task"
    ]
  }
```

}
