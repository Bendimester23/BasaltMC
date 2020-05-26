Basalt ![Java CI with Maven](https://github.com/Bendimester23/Basalt/workflows/Build/badge.svg)
===========

High performance Paper fork that aims to add more gameplay and mechanics.


**Support and Project Discussion:**
 - [Discord](https://discord.io/skyv)

Planned Features
------
 * API for NMS files
 * Custom Items / Blocks / Materials
 * Play custom audio files client side (without browser)

How To (Server Admins)
------
Basaltshard is a jar file that you can download and run just like a normal jar file.

You cant download it right now.

Run the Paperclip jar directly from your server. Just like old times

  * Documentation on using Paper: [paper.readthedocs.io](https://paper.readthedocs.io/)
  * For a sneak peak on upcoming features, [see here](https://github.com/PaperMC/Paper/projects)

How To (Plugin Developers)
------
 * See our API patches [here](Spigot-API-Patches)
 * See upcoming, pending, and recently added API [here](https://github.com/PaperMC/Paper/projects/6)
 * Paper API javadocs here: [papermc.io/javadocs](https://papermc.io/javadocs/)
 * Maven Repo (for paper-api):
```xml
<repository>
    <id>papermc</id>
    <url>https://papermc.io/repo/repository/maven-public/</url>
</repository>
```
 * Artifact Information:
```xml
<dependency>
    <groupId>com.destroystokyo.paper</groupId>
    <artifactId>paper-api</artifactId>
    <version>1.15.2-R0.1-SNAPSHOT</version>
    <scope>provided</scope>
 </dependency>
 ```

How To (Compiling Jar From Source)
------
To compile Paper, you need JDK 8, maven, and an internet connection.

Clone this repo, run `./paper jar` from *bash*, get files.

How To (Pull Request)
------
See [Contributing](CONTRIBUTING.md)
