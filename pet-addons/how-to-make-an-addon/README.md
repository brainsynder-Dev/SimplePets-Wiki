# How to make an addon

{% hint style="warning" %}
This page is not complete, More will be added soon
{% endhint %}

{% hint style="info" %}
This is not a tutorial on how to make an addon, as that would require teaching how to code Java. Instead this focuses on developers who already know how to make plugins
{% endhint %}

## Requirements

* For SimplePets addons you must use a minimum of Java 16 for your development environments&#x20;
* The SimplePets API module [_<mark style="color:red;">**SEE BELOW**</mark>_](./#maven)_<mark style="color:red;">****</mark>_
* BSLib <mark style="color:blue;">`[Optional]`</mark>

## Maven

For the sake of the example I will be using maven\
When developing an addon you need the SimplePets API\
You are able to get that 2 ways by either using the [_<mark style="color:red;">**SimplePets-API.jar**</mark>_](https://ci.pluginwiki.us/view/SimplePets/job/SimplePets\_v5/lastSuccessfulBuild/artifact/API/target/SimplePets-API%20\(DEVELOPERS%20ONLY\).jar) file on the Jenkins server or you could use Maven

### Maven Repository

```xml
<repository>
    <id>bs-public</id>
    <url>https://repo.pluginwiki.us/repository/maven-releases/</url>
</repository>
```

### Pet API Dependency

![Latest version of the SimplePets plugin](https://img.shields.io/maven-metadata/v?color=red\&label=Current%20Version\&metadataUrl=https%3A%2F%2Frepo.pluginwiki.us%2Frepository%2Fmaven-releases%2Fsimplepets%2Fbrainsynder%2FAPI%2Fmaven-metadata.xml\&style=for-the-badge)

{% hint style="danger" %}
This must _<mark style="color:red;">**`NOT`**</mark>_ be shaded, it _<mark style="color:red;">**`WILL`**</mark>_ throw an error when you try to test it.
{% endhint %}

```xml
<dependency>
    <groupId>simplepets.brainsynder</groupId>
    <artifactId>API</artifactId>
    <version><!-- INSERT THE LATEST VERSION --></version>
    <scope>provided</scope>
</dependency>
```

### BSLib Dependency

![Latest version of the Library](https://img.shields.io/maven-metadata/v?color=red\&label=Current%20Version\&metadataUrl=https://repo.pluginwiki.us/repository/maven-releases/lib/brainsynder/API/maven-metadata.xml\&style=for-the-badge)

```xml
<dependency>
    <groupId>lib.brainsynder</groupId>
    <artifactId>API</artifactId>
    <version><!-- INSERT THE LATEST VERSION --></version>
</dependency>
```

Just a note: If you use BSLib it MUST be shaded into the jar file
