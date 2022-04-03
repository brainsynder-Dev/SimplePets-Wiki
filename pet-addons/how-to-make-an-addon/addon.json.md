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
| supported-build | <p>What build of SimplePets does this addon work on?<br><mark style="color:green;"><code>Example:</code></mark> SimplePets version <mark style="color:purple;"><code>5.0-BUILD-160</code></mark><br>So the build number would be <mark style="color:yellow;"><code>160</code></mark></p> |                         <mark style="color:yellow;">`INT`</mark>                        |
|   description   | <p>Give a brief description of what the addon does, Color codes can be used in the text<br><mark style="color:green;"><code>(This will also be displayed on the addon item)</code></mark></p>                                                                                            | <mark style="color:green;">`STRING`</mark> / <mark style="color:orange;">`ARRAY`</mark> |

## Example addon.json file

```json
{
  "name": "AwesomeAddon",
  "author": "Steve",

  "version": 0.1,
  "supported-build": 160,

  "description": [
    "&7This addon adds multiple awesome",
    "&7features in to SimplePets"
  ]
}
```
