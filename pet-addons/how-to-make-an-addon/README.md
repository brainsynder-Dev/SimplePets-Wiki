# How to make an addon

{% hint style="warning" %}
This page is not complete, More will be added soon
{% endhint %}

{% hint style="info" %}
This is not a tutorial on how to make an addon, as that would require teaching how to code Java. Instead this focuses on developers who already know how to make plugins
{% endhint %}

## Requirements

* For SimplePets addons you must use a minimum of Java 21 for your development environments&#x20;
* The SimplePets API module [_<mark style="color:red;">**SEE BELOW**</mark>_](./#maven)_<mark style="color:red;">****</mark>_
* BSPluginUtils <mark style="color:blue;">`[Optional]`</mark>

## Maven

For the sake of the example I will be using maven\
When developing an addon you need the SimplePets API

### Maven Repository

```xml
<repository>
    <id>bs-repo-releases</id>
    <url>https://repo.bsdevelopment.org/releases/</url>
</repository>
```

### Pet API Dependency

![Latest version of the SimplePets plugin](https://img.shields.io/maven-metadata/v?metadataUrl=https%3A%2F%2Frepo.bsdevelopment.org%2Freleases%2Forg%2Fbsdevelopment%2Fsimplepets%2Fapi%2Fmaven-metadata.xml\&style=for-the-badge\&label=Current%20Version\&color=red)

{% hint style="danger" %}
This must _<mark style="color:red;">**`NOT`**</mark>_ be shaded, it _<mark style="color:red;">**`WILL`**</mark>_ throw an error when you try to test it.
{% endhint %}

```xml
<dependency>
    <groupId>org.bsdevelopment.simplepets</groupId>
    <artifactId>api</artifactId>
    <version>R5-B308</version>
    <scope>provided</scope>
</dependency>
```

### BSPluginUtils Dependency

SimplePets already shades BSPluginUtils into its own jar, so you only need it to compile against

{% hint style="danger" %}
This must _<mark style="color:red;">**`NOT`**</mark>_ be shaded either, the copy inside SimplePets is the one that will be used
{% endhint %}

```xml
<dependency>
    <groupId>org.bsdevelopment.pluginutils</groupId>
    <artifactId>BSPluginUtils</artifactId>
    <version><!-- INSERT THE LATEST VERSION --></version>
    <scope>provided</scope>
</dependency>
```

## Gradle

The same two dependencies using the Kotlin DSL

```kotlin
repositories {
    maven("https://repo.bsdevelopment.org/releases/")
}

dependencies {
    compileOnly("org.bsdevelopment.simplepets:api:R5-B308")
    compileOnly("org.bsdevelopment.pluginutils:BSPluginUtils:VERSION")
}
```
