# Addon FAQ

## How can I install addons for SimplePets

Here is the main way of installing addons for SimplePets:

1. Click the <mark style="color:red;">`Install Addons`</mark> item that is on the last row
2. Click the addon you would like to install _<mark style="color:green;">(Some of them have plugin requirements)</mark>_
3. Re-Open the <mark style="color:red;">`/pet addon`</mark> GUI and make sure the installed addon is enabled (green)

<mark style="color:orange;">**--- IF it is still red check your console for an error message ---**</mark>

Here are some images showing how to do this [_<mark style="color:blue;">**CLICK HERE**</mark>_](https://imgur.com/a/Yl0oxft)

## How can i reload my addons after customizing them?

So you have finished customizing the addons config file and would like the new configuration to be used. You can do it 2 ways..\
\
\- The first way is to simply <mark style="color:red;">`restart`</mark> your server, doing the restart refreshes the plugins memory and guarantees a fresh start\
\
\- The second way is to follow these steps:

1. Run the <mark style="color:red;">`/pet addon`</mark> command
2. <mark style="color:orange;">`Disable`</mark> the addon you modified the config for
3. <mark style="color:orange;">`Re-Enable`</mark> the addon you just disabled\
   Doing so will refresh the addon with the new config information.

## How can I update the addons I have installed?

Currently there are currently 3 ways to update the addons you have installed

1. The simplest way is to use the [Addon Command](../command-information/commands/addon-command.md). You can run the command like: \
   <mark style="color:red;">`/pet addon update PetWeight`</mark> as an example, This will unload the current version... then download the latest version available. <mark style="color:orange;">`(Added in v5.0-BUILD-124)`</mark>
2. Download them manually from either our [_<mark style="color:red;">**JENKINS**</mark>_](https://ci.pluginwiki.us/view/SimplePets%20Addons/) or from the [_<mark style="color:red;">**Addon Site**</mark>_](https://bsdevelopment.org/addons/) Then drop them into the <mark style="color:red;">`plugins/SimplePets/Addons`</mark> folder and restart your server
3. The final way is to delete the Addons' jar file from the <mark style="color:red;">`plugins/SimplePets/Addons`</mark> folder then re-install it by following the [_<mark style="color:red;">**STEPS HERE**</mark>_](addon-faq.md#how-can-i-install-addons-for-simplepets)_<mark style="color:red;">****</mark>_
