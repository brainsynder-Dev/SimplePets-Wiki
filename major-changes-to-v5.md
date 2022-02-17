---
description: >-
  This page will show all the new features and changes that have been made for
  v5 of SimplePets. Especially if you are updating from v4
---

# Major changes to v5

## Introduction

SimplePets v5 has been completely re-coded from the ground up, only a select few bits and pieces of code remain untouched. Since it was re-coded I was able to add some neat features that I could not add due to the code structure of current versions

{% tabs %}
{% tab title="Multiple Pets" %}
Thanks to re-coding the plugin I was finally able to add a long time request, and that was to be allowed to have multiple pets spawned at the same time.

The limit of how many pets a player can have can be modified in the <mark style="color:green;">`config.yml`</mark> file as shown below.

```yaml
pet-toggles:
  # The maximum number of pets a player can spawn at a time.
  # This can be overridden using pet.amount.<Number>, e.g. pet.amount.1 to only allow 1 at once.
  # 
  # Default: 3
  pet-spawn-limit: 3
```
{% endtab %}

{% tab title="Addons" %}
So addons are something new we are trying with SimplePets. The goal of addons is to mainly help minimize the number of external plugins we link into, but there are of course many more reasons... Like new small features that other developers can code <mark style="color:green;">`(Example: Pet Weights or maybe a leveling system)`</mark>, we can also say that this will help us find issues with certain plugin linkages, and last but not least other developers can make an addon that could link into their own plugin.

Addons can be installed via the IN-GAME installer \[[INSTRUCTIONS HERE](faq.md#how-can-i-install-addons-for-simplepets)]

The addons can also be downloaded from the [Addon Site](https://pluginwiki.us/addons/) and added to the <mark style="color:red;">`plugins/SimplePets/Addons/`</mark> folder on your server <mark style="color:green;">`(restart would be required)`</mark>
{% endtab %}

{% tab title="Pet Data" %}
Thanks to the re-code I was able to make it so you can customize the default value for pets <mark style="color:green;">(Example: age)</mark>

I have also added a few new data items for some pets like the Ravager, Zoglin/Hoglin, Bee, Fox, Enderman <mark style="color:green;">(Can now hold blocks, can only be set via</mark> <mark style="color:red;">`/pet modify`</mark><mark style="color:green;">)</mark>, and a few others.

Pets that can have their size changed <mark style="color:green;">(Example: Slime/MagmaCube/Phantom)</mark> can now have custom sizes added to their list of items <mark style="color:green;">(the ones viewed in the GUI)</mark>, this can be done by simply copying one of the size items in the pets JSON file then change the values <mark style="color:green;">(</mark><mark style="color:green;">`If the data is not formatted correctly or has an issue it will default to ?`</mark><mark style="color:green;">)</mark>
{% endtab %}
{% endtabs %}

## Pet Renaming

In the past you could only rename a pet via <mark style="color:orange;">CHAT</mark> or the <mark style="color:orange;">ANVIL GUI</mark> <mark style="color:green;">(or if you were advanced the</mark> <mark style="color:red;">`/pet modify`</mark> <mark style="color:green;">command)</mark>

A total of <mark style="color:purple;">4</mark> different ways to change your pets name were added, and those are <mark style="color:orange;">CHAT</mark>, <mark style="color:orange;">ANVIL</mark>, <mark style="color:orange;">SIGN</mark> <mark style="color:green;">(Requires</mark> [_<mark style="color:green;">**ProtocolLIB**</mark>_](https://www.spigotmc.org/resources/1997/)<mark style="color:green;">)</mark>, and the <mark style="color:orange;">command</mark> <mark style="color:red;">`/pet rename <type> <name>`</mark>

This can be changed in the <mark style="color:green;">`config.yml`</mark> file

```yaml
RenamePet:
  # How should the player be able to modify their pets name?
  # Types:
  # - COMMAND (They have to use the '/pet rename' command to set the name)
  # - CHAT (They have to type the name in chat)
  # - ANVIL (The Anvil GUI will open and they can change the name there)
  # - SIGN [REQUIRES ProtocolLib] (Will open a Sign GUI they input the name on the configured line)
  # Default: ANVIL
  Type: ANVIL
```

### HEX Chat Colors

With the re-code of SimplePets, we were able to make it so [HEX color codes](https://htmlcolorcodes.com/color-picker/) could be used along with [regular color codes](https://minecraft.fandom.com/wiki/Formatting\_codes#Color\_codes).

The formatting for HEX color codes is setup like this: <mark style="color:orange;">`&#FFFFFF`</mark>

Example Usage: `"&7Hey have you said`` `<mark style="color:red;">`&#e93b19`</mark>`Hello`` `<mark style="color:orange;">`&#e99919`</mark>`World yet?"`

## Customization of the Sign GUI

You can change what line the player has to use for inputting the pets name, This can be simply done by moving the <mark style="color:orange;">`{input}`</mark> placeholder to one of the 4 lines.

* HEX Color Codes can <mark style="color:red;">**NOT**</mark> be used for the sign GUI
* <mark style="color:red;">MUST</mark> have 4 lines
* One line <mark style="color:red;">MUST</mark> have the <mark style="color:orange;">`{input}`</mark> placeholder

```yaml
rename:
  sign:
    # The text that will be set for the sign
    #   - One line MUST have {input} to mark what line the player types the pets name
    #   - Hex colors can NOT be used for this
    #   - MUST have 4 lines
    lines:
    - '{input}'
    - '&l^^^^^^^^'
    - '&9&lPlease Enter'
    - '&9&lPet Name'
```
