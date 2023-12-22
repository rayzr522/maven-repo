# Maven Repository

This is the personal Maven repository for [@Rayzr522](https://github.com/Rayzr522). To use this repository, all you have to do is add the following to the `<repositories>` section of your `pom.xml`:

```xml
<repository>
    <id>rayzr-repo</id>
    <url>https://rayzr.dev/repo/</url>
</repository>
```

That's it! Now, for example, if you wanted to add [JSONMessage](https://github.com/Rayzr522/JSONMessage), you would add this to the `<dependencies>` section of your `pom.xml`:

```xml
<dependency>
    <groupId>me.rayzr522</groupId>
    <artifactId>jsonmessage</artifactId>
    <version>1.2.0</version>
</dependency>
```

## Disclaimer

I have various dependencies in here which are NOT MY OWN. I take no credit for them. I simply have them here because I needed to reference them in my own projects and I could not find a proper Maven repository for them. If anyone has an issue with a dependency I have in this repo, please open an issue to let me know and I will take appropriate action.
