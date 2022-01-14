# Debug Command

{% hint style="danger" %}
This command is considered an _<mark style="color:red;">**ADMIN ONLY**</mark>_ command\
Ordinary players should _<mark style="color:red;">**NOT**</mark>_ be given access to this command
{% endhint %}

## What does this command do?

This command will generate a debug link, This link is mostly used when reporting bugs on either [Discord](https://discord.com/invite/TzhnW8xtsR) or [Github](https://github.com/brainsynder-Dev/SimplePets/issues/new/choose) and will help us with answering key questions we ask.

The data that this collects in this link is:&#x20;

<details>

<summary>Server Information</summary>

* Java Version
* Server Type
* Server Version
* NMS Version
* SimplePets Version

</details>

<details>

<summary>Installed Addons</summary>

* Addon Names
* Addon Versions
* Addon Authors

</details>

<details>

<summary>Installed Plugins</summary>

* Plugin Name
* Plugin Version

</details>

<details>

<summary>Config</summary>

Yes we get a copy of your config file, Do not worry as the key info like MySQL login is <mark style="color:purple;">HIDDEN</mark> from this copy.

This helps us to make sure your config settings are not an issue.

If you do not want to send us your config then just modify the debug information to remove the line where the config is at

</details>

<details>

<summary>Debug Information</summary>

The debug we collect are the internal messages the plugin sends either to itself or in your console <mark style="color:green;">`(If Debug is enabled)`</mark>

</details>

<details>

<summary>Misc Information</summary>

The last bit of information we collect is sort of random like:

* Jenkins <mark style="color:green;">`(Current build, number of builds behind compared to Jenkins)`</mark>
* Was your server reloaded?
* If you have the <mark style="color:green;">`"block-plugin-spawning"`</mark> enabled in the WorldGuard config

</details>

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
>
>
> Usage: /pet debug

## Permissions

| Permission Node    | Description                                                                  |
| ------------------ | ---------------------------------------------------------------------------- |
| pet.commands.debug | Grants the player access to run <mark style="color:red;">`/pet debug`</mark> |
