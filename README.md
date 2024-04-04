<img src="logo.jpg" height="240" alt="Beast Face" align="right">

# Beast [![Dev Build](https://github.com/HomoMC/Beast/actions/workflows/dev-build.yml/badge.svg)](https://github.com/HomoMC/Beast/actions/workflows/dev-build.yml)

A Paper 1.12.2 fork aims to provide extreme performance, bug fixes, and improvements.

*This project is based on Reaper 1.12.2*

## Features

- **Beast is a fork of [Paper-1.12.2](https://github.com/PaperMC/Paper)** designed for performance, new fun and exciting gameplay features.
- **Contains [Lithium](https://github.com/CaffeineMC/lithium-fabric) patches** that optimizing many areas in game.
- **Bug fixes** for several Minecraft issues.
- **Backports** bug fixes of Mojang.
- **Plugin compatibility** with Spigot & Paper plugins.
- **Completely** removed Timings to save your server performance.
- **Various optimizations** for vanilla methods.
- **Brings back** some vanilla features.
- **More events make your server more fun**.

## How To (Server Admins)

Beast uses the same paperclip jar system that Paper uses.

You can download the latest release of Beast by going [here](https://github.com/HomoMC/Beast/releases/latest) but I highly recommend to use the latest [dev build](https://nightly.link/HomoMC/Beast/workflows/dev-build/ver%2F1.12.2/Beast-JDK8.zip).

## How To (Plugin Developers)

Maven repository:
```xml
<repository>
    <id>github-homomc-beast</id>
    <name>GitHub Apache Maven Packages</name>
    <url>https://maven.pkg.github.com/HomoMC/Beast</url>
</repository>
```

Beast-API maven dependency:
```xml
<dependency>
    <groupId>com.homomc.beast</groupId>
    <artifactId>beast-api</artifactId>
    <version>1.12.2-R0.1-SNAPSHOT</version>
    <scope>provided</scope>
</dependency>
```

Beast-Server maven dependency:
```xml
<dependency>
    <groupId>com.homomc.beast</groupId>
    <artifactId>beast</artifactId>
    <version>1.12.2-R0.1-SNAPSHOT</version>
    <scope>provided</scope>
</dependency>
```