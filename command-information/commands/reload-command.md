# Reload Command

{% hint style="danger" %}
This command is considered an _<mark style="color:red;">**ADMIN ONLY**</mark>_ command\
Ordinary players should _<mark style="color:red;">**NOT**</mark>_ be given access to this command
{% endhint %}

## What does this command do?

This command is used when you have modified any of the configuration files for the plugin, and you would like reload the file(s)/folder

If you do not specify a selector, then all of them will be reloaded.

## Command Usage

> <mark style="color:orange;">`<>`</mark> = REQUIRED
>
> <mark style="color:blue;">`[]`</mark> = OPTIONAL
>
>
>
> Usage: /pet reload <mark style="color:blue;">`[selector]`</mark>

### Usage Descriptions

| Usage                                                     | Description                                                                                                                                                                                                                                                                                                                                                                            |
| --------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /pet reload                                               | Running this command will reload all files                                                                                                                                                                                                                                                                                                                                             |
| /pet reload <mark style="color:blue;">`[selector]`</mark> | <p>Running this command will reload the targeted selector<br><br>Current Selectors: <mark style="color:purple;"><code>config</code></mark>, <mark style="color:purple;"><code>messages</code></mark>, <mark style="color:purple;"><code>inventories</code></mark>, <mark style="color:purple;"><code>particles</code></mark>, <mark style="color:purple;"><code>pets</code></mark></p> |

## Permissions

| Permission Node     | Description                                                                   |
| ------------------- | ----------------------------------------------------------------------------- |
| pet.commands.reload | Grants the player access to run <mark style="color:red;">`/pet reload`</mark> |
