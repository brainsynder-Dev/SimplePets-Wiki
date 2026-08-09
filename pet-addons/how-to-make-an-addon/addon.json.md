# addon.json

{% hint style="warning" %}
As of <mark style="color:orange;">`April 3rd 2022`</mark>\
All addons are required to have an <mark style="color:purple;">`addon.json`</mark> file in their jar file\
Like how plugins require a <mark style="color:green;">`plugin.yml`</mark> file in theirs
{% endhint %}

## Required Keys

This file has a few required keys needed

|       Key       | Description                                                                                                                                                                                                                                                                              |                                           Type                                          |
| :-------------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------: |
|       name      | What is the name of the addon you made?                                                                                                                                                                                                                                                  |                        <mark style="color:green;">`STRING`</mark>                       |
|      author     | <p>Who is the author of the addon<br><mark style="color:green;"><code>(Used for when there is only one author)</code></mark></p>                                                                                                                                                         |                        <mark style="color:green;">`STRING`</mark>                       |
|     authors     | <p>Who is contributed to the development of the addon<br><mark style="color:green;"><code>(Used for when there is more then one author)</code></mark></p>                                                                                                                                |                        <mark style="color:orange;">`ARRAY`</mark>                       |
|     version     | <p>What is the version of the addon<br>Example: <mark style="color:blue;"><code>0.1</code></mark></p>                                                                                                                                                                                    |                        <mark style="color:blue;">`DOUBLE`</mark>                        |
| supported-build | <p>What build of SimplePets does this addon work on?<br><mark style="color:green;"><code>Example:</code></mark> SimplePets version <mark style="color:purple;"><code>R5-B308</code></mark><br>So the build number would be <mark style="color:yellow;"><code>308</code></mark><br><mark style="color:green;"><code>(The addon will not load on any build older than this, leave it out to skip the check)</code></mark></p> |                         <mark style="color:yellow;">`INT`</mark>                        |
|   description   | <p>Give a brief description of what the addon does, Color codes can be used in the text<br><mark style="color:green;"><code>(This will also be displayed on the addon item)</code></mark></p>                                                                                            | <mark style="color:green;">`STRING`</mark> / <mark style="color:orange;">`ARRAY`</mark> |

## Optional Keys

These keys are not required, they are used when your addon needs another plugin to work

|      Key      | Description                                                                                                                                                                                                                                                                                                       |                                           Type                                          |
| :-----------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :-------------------------------------------------------------------------------------: |
| plugin-support | <p>What plugin(s) does the addon need to be installed, each entry needs a <mark style="color:purple;"><code>name</code></mark> and a <mark style="color:purple;"><code>url</code></mark><br><mark style="color:green;"><code>(Only ONE of them has to be installed, the url is shown in the console when none are found)</code></mark></p> |                        <mark style="color:orange;">`ARRAY`</mark>                       |
|  class-checks | <p>What class(s) must be found before the addon is loaded<br><mark style="color:green;"><code>(A fail-safe for when the plugin is installed but is missing the class the addon uses)</code></mark></p>                                                                                                            | <mark style="color:green;">`STRING`</mark> / <mark style="color:orange;">`ARRAY`</mark> |

## Example addon.json file

```json
{
  "name": "AwesomeAddon",
  "author": "Steve",

  "version": 0.1,
  "supported-build": 308,

  "description": [
    "&7This addon adds multiple awesome",
    "&7features in to SimplePets"
  ]
}
```

## Example addon.json file <mark style="color:green;">(with plugin requirements)</mark>

```json
{
  "name": "WorldGuard",
  "author": "Steve",

  "version": 0.1,
  "supported-build": 308,

  "description": "&7Adds WorldGuard region flags to SimplePets",

  "plugin-support": [
    {
      "name": "WorldGuard",
      "url": "https://dev.bukkit.org/projects/worldguard"
    }
  ],
  "class-checks": [
    "com.sk89q.worldguard.WorldGuard"
  ]
}
```
