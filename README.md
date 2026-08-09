# HOME

![Current plugin version on the Jenkins](https://img.shields.io/maven-metadata/v?metadataUrl=https%3A%2F%2Frepo.bsdevelopment.org%2Freleases%2Forg%2Fbsdevelopment%2Fsimplepets%2Fapi%2Fmaven-metadata.xml&style=for-the-badge&label=Current%20Version&color=red)

### Requirements

* The supported spigot versions are `1.21.8`, `1.21.10`, `1.21.11`, `26.1`, and `26.2`
* 1.21.8 -> 1.21.11 require `Java 21`
* 26.1 and up require `Java 25`
* Support for 1.21.6 was dropped in <mark style="color:orange;">`R5-B296`</mark> and 1.21.7 was dropped in <mark style="color:orange;">`R5-B304`</mark>

### How to compile the plugin yourself

As of <mark style="color:orange;">`R5-B292`</mark> the plugin is a gradle project, so there are no longer separate jars for each server version\
Compiling it only takes the single command: `gradle clean build`

The finished <mark style="color:red;">`SimplePets.jar`</mark> will then be in the <mark style="color:red;">`build/libs`</mark> folder

The version the jar is built as comes from the <mark style="color:purple;">`version`</mark> property in the <mark style="color:red;">`gradle.properties`</mark> file <mark style="color:green;">(currently `R5-B308`)</mark>\
You can build it as a different version by adding `-Pversion=`<mark style="color:orange;">`{version}`</mark> to the command

<mark style="color:orange;">`{version}`</mark> = The version you want the jar to be built as <mark style="color:green;">(e.g `gradle clean build -Pversion=R5-B308`)</mark>

### How to install the plugin

* Download the plugin off the [spigot](https://www.spigotmc.org/resources/100106/) site (or from the [JENKINS](https://ci.pluginwiki.us/job/SimplePets\_v5/) site)\
  (Make sure you have the correct jar file for your servers version)
* Once you have the Simple Pets jar file for your version, simply drag and drop it into your servers <mark style="color:red;">`plugins`</mark> folder
* <mark style="color:orange;">`RESTART`</mark> your server (DO _<mark style="color:red;">**NOT**</mark>_ RELOAD)
* You can then configure the different config files to your liking, Once that is done then you can either run the <mark style="color:red;">`/pet reload`</mark> command or <mark style="color:orange;">`RESTART`</mark> the server again

### Where can I get support?

We currently have quite a few areas were you can receive support or find out information\
Our primary support center is on our [DISCORD](https://discord.bsdevelopment.org) server\
You can also open a [GITHUB ISSUE](https://github.com/brainsynder-Dev/SimplePets/issues/new/choose) and we will take a look at it

If you don't have a GITHUB or DISCORD account then you can leave us a message on spigot \[This is if you want slow support as we don't check spigot a lot]
