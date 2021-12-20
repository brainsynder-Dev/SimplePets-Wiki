---
description: List of frequently asked questions we receive
---

# FAQ

## **Will the Ender Dragon be added to the plugin?**

I personally wont be adding it to the plugin but if someone else adds it via GitHub [Pull Request](https://github.com/brainsynder-Dev/SimplePets/compare) it might be another story

## **What version should I use for my server?**

It depends on what version your server is running. Minecraft Version:

* [Any Version above 1.18.1](https://ci.pluginwiki.us/job/SimplePets\_v5/)
* [1.18.1](https://ci.pluginwiki.us/job/SimplePets\_v5/lastSuccessfulBuild/artifact/Version\_1.18.1/target/SimplePets-1.18.1.jar)
* [1.18](https://ci.pluginwiki.us/job/SimplePets\_v5/lastSuccessfulBuild/artifact/Version\_1.18/target/SimplePets-1.18.jar)
* [1.17.1](https://ci.pluginwiki.us/job/SimplePets\_v5/lastSuccessfulBuild/artifact/Version\_1.17.1/target/SimplePets-1.17.1.jar)
* [1.17](https://ci.pluginwiki.us/job/SimplePets\_v5/lastSuccessfulBuild/artifact/Version\_1.17/target/SimplePets-1.17.jar)&#x20;

SimplePets v4

* [1.16.4/1.16.5](https://ci.pluginwiki.us/job/SimplePets-Experimental/lastSuccessfulBuild/artifact/v1\_16\_R3/target/SimplePets-1.16.4.jar)
* [1.16.3](https://ci.pluginwiki.us/job/SimplePets-Experimental/lastSuccessfulBuild/artifact/v1\_16\_R2/target/SimplePets-1.16.3.jar)
* [1.16](https://ci.pluginwiki.us/job/SimplePets-Experimental/lastSuccessfulBuild/artifact/v1\_16\_R1/target/SimplePets-1.16.jar)
* [1.15](https://ci.pluginwiki.us/job/SimplePets-Experimental/lastSuccessfulBuild/artifact/v1\_15\_R1/target/SimplePets-1.15.jar)&#x20;

For people who are a dinosaur and don't update:

* [All versions below 1.15](https://ci.pluginwiki.us/job/SimplePets/)

## How can I install addons for SimplePets

Here is the main way of installing addons for SimplePets:

1. Run the <mark style="color:red;">`/pet addon`</mark> command
2. Click the <mark style="color:red;">`Install Addons`</mark> item that is on the last row
3. Click the addon you would like to install _<mark style="color:green;">(Some of them have plugin requirements)</mark>_
4. Re-Open the <mark style="color:red;">`/pet addon`</mark> GUI and make sure the installed addon is enabled (green)&#x20;

<mark style="color:orange;">**--- IF it is still red check your console for an error message ---**</mark>

Here are some images showing how to do this [_<mark style="color:blue;">**CLICK HERE**</mark>_](https://imgur.com/a/Yl0oxft)_<mark style="color:blue;">****</mark>_

## My World Guard flags do not seem to be working!

There could be a major reason for this, in v5 of SimplePets we split all external plugin links into their own addons.&#x20;

What you could do is make sure you have the World Guard addon installed on your server (Check <mark style="color:red;">`/pet addon`</mark>)

If the addon is not installed you can follow the steps listed [HERE](faq.md#how-can-i-install-addons-for-simplepets)

## How can I update the addons I have installed?

Currently there is not an easy way to do this, You could update them 2 ways...

1. Download them an manually from either our [JENKINS](https://ci.pluginwiki.us/view/SimplePets%20Addons/) or from the [Addon Site](https://pluginwiki.us/addons/) Then drop them into the <mark style="color:red;">`plugins/SimplePets/Addons`</mark> folder and restart your server
2. The second way is to delete the Addons jar file from the <mark style="color:red;">`plugins/SimplePets/Addons`</mark> folder then re-install them from following the [STEPS HERE](faq.md#how-can-i-install-addons-for-simplepets)

## My players do not have permission for the <mark style="color:red;">`/pet gui`</mark> command!

There is 2 ways you can fix this:

1. Give the player`(s)` a permission for any pet
2. Go into the <mark style="color:green;">`config.yml`</mark> file and make sure <mark style="color:red;">`Needs-Pet-Permission-for-GUI`</mark> is set to <mark style="color:orange;">`false`</mark>, This will allow players to open the GUI regardless of what pet`(s)` they have permission to.

```yaml
Permissions:
  # Enabling this would require players to have access to at least 1 pets permission
  # Default: false
  Needs-Pet-Permission-for-GUI: false 
  # Make sure this is false if you went the second option
```

## My players see a blank GUI when they run the <mark style="color:red;">`/pet gui`</mark> command!

There is 3 ways you can fix this:

1. Give the player`(s)` a permission for any pet
2. Give the player`(s)` a pet via the <mark style="color:red;">`/pet purchased`</mark> command
3. Go into the <mark style="color:green;">`config.yml`</mark> and set <mark style="color:red;">`Only-Show-Pets-Player-Can-Access`</mark> to <mark style="color:orange;">`false`</mark>, This will allow the players to see all the pets enabled and available for use.

```yaml
Permissions:
  # Enabling this would remove all the pets the player does not have access to from the GUI
  # Default: true
  Only-Show-Pets-Player-Can-Access: true # Set this to false if option 3
```

## Can the Sign GUI for renaming be customized?

Yes the sign GUI can be customized, have a look at [THIS](major-changes-to-v5.md#customization-of-the-sign-gui) section for information

## How can I disable certain pets?

You are able to disable what ever pet you want, that can be done by simply changing one line in the pets json file!

1. Open the pets json file <mark style="color:green;">`"plugins/SimplePets/Pets/<type>.json"`</mark>
2. Change line that is <mark style="color:green;">`"enabled":`</mark>` `<mark style="color:orange;">`true`</mark> to be <mark style="color:green;">`"enabled":`</mark>` `<mark style="color:orange;">`false`</mark>

## How can I set defaults for pets? <mark style="color:green;">(Like Age)</mark>

This can be done by modifying the pets json file <mark style="color:green;">`"plugins/SimplePets/Pets/<type>.json"`</mark>.

This is an example of what line you can modify for a pet to be a baby/adult when they are spawned by default. Some data toggles can be numbers or text just depends on what values are listed for that bit of data.

Using the example below the <mark style="color:purple;">`"baby"`</mark> data could have a value of either <mark style="color:green;">`true`</mark> or <mark style="color:red;">`false`</mark>, so that is what we would put on the line named <mark style="color:purple;">`"default"`</mark>

```json
  "data": {
    "baby": {
      "enabled": true,
      "default": false, <- This line can be changed to be any of the values below
      "values": {
        "true": {
          "material": "WHEAT",
          "name": "&#C8C8C8Baby: &atrue"
        },
        "false": {
          "material": "WHEAT",
          "name": "&#C8C8C8Baby: &cfalse"
        }
      }
    }
  }
```

## My pet vanishes after a while, usually when I'm afk for a bit.

This is caused because by default the <mark style="color:green;">`"AutoRemove"`</mark> feature is enabled, This can either be disabled or the time that it takes for the auto-removal can be increased.

#### How to change the time

The time for the <mark style="color:green;">`"AutoRemove"`</mark> is in ticks <mark style="color:green;">`(20 ticks is equal to 1 second)`</mark>, by default the time is set for 10000 ticks and that would be around 8 minutes 20 seconds.

If you want to change the delay you can use this bit of math: <mark style="color:purple;">`20 x (seconds)`</mark>&#x20;

Example: say you want pets to be removed after 35 minutes, First figure out how many seconds that would be <mark style="color:purple;">`(35 x 60 = 2,100)`</mark>. Once we have the total number of seconds that is in 35 minutes, We can then convert the seconds to Ticks <mark style="color:purple;">`(2,100 x 20 = 42,000)`</mark> So we would set the <mark style="color:green;">`"TickDelay"`</mark> to 42000.

Alternatively you could use a Tick Calculator&#x20;

```yaml
PetToggles:
  AutoRemove:
    # Disabling this will make it so pets wont be automatically removed if the player is afk
    # Default: true
    Enabled: true
    # What should the wait be?
    # This is in ticks (20 ticks = 1 second)
    # Default: 10000
    TickDelay: 10000
```
