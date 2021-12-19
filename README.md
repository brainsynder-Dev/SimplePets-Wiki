# HOME

![Current plugin version on the Jenkins](https://img.shields.io/maven-metadata/v?color=red\&label=Current%20Version\&metadataUrl=https%3A%2F%2Frepo.pluginwiki.us%2Frepository%2Fmaven-releases%2Fsimplepets%2Fbrainsynder%2FAPI%2Fmaven-metadata.xml\&style=for-the-badge)

### Requirements

* As of v5 of the plugin the minimum spigot version required is 1.17
* 1.17 & 1.17.1 require `Java 16`
* 1.18 & 1.18.1 require `Java 17`
* If you are getting older versions of the plugin then those versions are labeled for the spigot version used and they all use `Java 8`

### How to compile the plugin yourself

Compiling the plugin is VERY easy, you can run the maven command `mvn clean install -f pom.xml -Denv.BUILD_NUMBER=`<mark style="color:orange;">`{build}`</mark>` ``-Denv.JOB_NAME=`<mark style="color:purple;">`{job}`</mark>

<mark style="color:orange;">`{build}`</mark> = The build number you want as the version <mark style="color:green;">(e.g 1000 = 5.0-BUILD-1000)</mark>

<mark style="color:purple;">`{job}`</mark> = This can be set to what you want its mostly used by the update checker <mark style="color:green;">(e.g SimplePets\_v5)</mark>

### How to install the plugin

* Download the plugin off the [spigot](https://www.spigotmc.org/resources/14124/) site (or from the [JENKINS](https://ci.pluginwiki.us/job/SimplePets\_v5/) site)\
  &#x20;            (Make sure you have the correct jar file for your servers version)
* Once you have the Simple Pets jar file for your version, simply drag and drop it into your servers <mark style="color:red;">`plugins`</mark> folder
* <mark style="color:orange;">`RESTART`</mark> your server (DO _<mark style="color:red;">**NOT**</mark>_ RELOAD)
* You can then configure the different config files to your liking, Once that is done then you can either run the <mark style="color:red;">`/pet reload`</mark> command or <mark style="color:orange;">`RESTART`</mark> the server again

### Where can I get support?

We currently have quite a few areas were you can receive support or find out information\
Our primary support center is on our [DISCORD](https://discord.gg/TzhnW8xtsR) server\
You can also open a [GITHUB ISSUE](https://github.com/brainsynder-Dev/SimplePets/issues/new/choose) and we will take a look at it&#x20;

If you don't have a GITHUB or DISCORD account then you can leave us a message on spigot \[This is if you want slow support as we don't check spigot a lot]
