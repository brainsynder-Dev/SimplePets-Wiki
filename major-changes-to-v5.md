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
Thanks to re-coding the plugin I was finally able to add a long time request, and that was to be allowed to have multiple pets spawned at the same time.&#x20;

The limit of how many pets a player can have can be modified in the <mark style="color:green;">`config.yml`</mark> file as shown below.

```yaml
PetToggles:
  # The maximum number of pets a player can spawn at a time.
  # This can be overridden using pet.amount.<Number>, e.g. pet.amount.1 to only allow 1 at once.
  # Default: 3
  Default-Spawn-Limit: 3
```
{% endtab %}

{% tab title="Addons" %}
So addons are something new we are trying with SimplePets. The goal of addons is to mainly help minimize the number of external plugins we link into, but there are of course many more reasons... Like new small features that other developers can code <mark style="color:green;">`(Example: Pet Weights or maybe a leveling system)`</mark>, we can also say that this will help us find issues with certain plugin linkages, and last but not least other developers can make an addon that could link into their own plugin.

Addons can be installed via the IN-GAME installer \[[INSTRUCTIONS HERE](faq.md#how-can-i-install-addons-for-simplepets)]

The addons can also be downloaded from the [Addon Site](https://pluginwiki.us/addons/) and added to the <mark style="color:red;">`plugins/SimplePets/Addons/`</mark> folder on your server <mark style="color:green;">`(restart would be required)`</mark>
{% endtab %}
{% endtabs %}
