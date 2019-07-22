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

## Support

For any problems or questions, please [join Rayzr's Discord server](https://discord.io/rayzrdevofficial)! We're more than happy to help.
