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
