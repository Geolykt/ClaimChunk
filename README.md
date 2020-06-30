![ClaimChunk Logo](imgs/icon64.png)
![ClaimChunk Title](imgs/logo_carrier.png)

[![Version Info](https://img.shields.io/static/v1?label=Version&message=0.0.20&color=blueviolet&style=for-the-badge)](https://github.com/cjburkey01/ClaimChunk/releases)
[![Download Info](https://img.shields.io/static/v1?label=Spigot&message=1.16.1&color=blueviolet&style=for-the-badge)](https://www.spigotmc.org/resources/claimchunk.44458/)
[![Servers Using Claimchunk](https://img.shields.io/bstats/servers/5179?label=Servers&color=cornflowerblue&style=for-the-badge)](https://bstats.org/plugin/bukkit/ClaimChunk)
[![Players Using Claimchunk](https://img.shields.io/bstats/players/5179?label=Players&color=cornflowerblue&style=for-the-badge)](https://bstats.org/plugin/bukkit/ClaimChunk)

**Join us on our [Discord server](https://discord.gg/zGYrqcq) (*zGYrqcq*) for bug reports, support, and general chatting!**

Info
----
Spigot plugin for 1.8+ allowing the claiming of chunks.

*The destiny of chunks is to unite not to divide*<br />
*Let's make the world ours.*

Usage and more information can be found [on the wiki](https://github.com/cjburkey01/ClaimChunk/wiki).

* **1.8 - 1.16.1** | Works seamlessly.
* **1.6 - 1.7.10** | Works when the config disables titles.

For even more information, the SpigotMC page can be found [here](https://www.spigotmc.org/resources/claimchunk.44458/).

Download
--------
Downloads are available in the [**releases section**](https://github.com/cjburkey01/ClaimChunk/releases).

Optional Features:
* [Vault](https://www.spigotmc.org/resources/vault.34315/) (for currency support you will also need an economy plugin like [Essentials](https://www.spigotmc.org/resources/essentialsx.9089/)).
* [WorldGuard](https://dev.bukkit.org/projects/worldguard) (VERSION **7.0.0+** REQUIRED and, as such, [WorldGuard support](https://github.com/cjburkey01/ClaimChunk/wiki/WorldGuard-Integration) is only available for **1.13+**)

Building
--------
![Version Info](https://img.shields.io/static/v1?label=Repository%20Version&message=0.0.21-SNAPSHOT&color=ff5555&style=for-the-badge)

If you want to obtain a version of the plugin that isn't availble yet (like a snapshot), you can do so by asking on the Discord or building it yourself. Here's how to build it yourself:

First, you'll need to clone the repo either using the Git command:<br />
`git clone git@github.com:cjburkey01/ClaimChunk.git`<br />
or downloading the repository source using the button above that says "Clone or download".

Once you have obtained the repo, inside of the local repository, you'll just need to execute this Gradle Wrapper command:<br/>
* `./gradlew jar` for Unix/Mac
* `gradlew jar` for Windows

Your built jar file can be found at:<br />
`<REPO>/OUT/claimchunk-VERSION.jar`
