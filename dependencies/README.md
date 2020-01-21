#### Dependencies

Since it uses some NMS/OBC codes, It is necessary to manually add the spigot jars here.

Note that gradle will use the Bukkit api from the first jar loaded and thus
**you must prefix the latest Bukkit jar with `!!` so that gradle loads it first.**
If you do not do this **TuSKe will not compile**. 

1_12_R1: `spigot-1.12-R0.1-SNAPSHOT`  
1_11_R1: `spigot-1.11-R0.1-SNAPSHOT`  
1_10_R1: `spigot-1.10-R0.1-SNAPSHOT`  
1_9_R2: `spigot-1.9.4-R0.1-SNAPSHOT`  
1_9_R1: `spigot-1.9.2-R0.1-SNAPSHOT`  
1_8_R3: `spigot-1.8.8-R0.1-SNAPSHOT`  
1_7_R4: `spigot-1.7.10-SNAPSHOT`

---

In this folder is included all jars for dependencies. Most of them are old plugins which isn't supported anymore, so I might remove it from TuSKe soon.

Sources:
* [SimpleClans](https://www.spigotmc.org/resources/5269/)
* [LegendChat](https://www.spigotmc.org/resources/6268/)
* [Marriage](https://www.spigotmc.org/resources/18998/)
* [ProtocolSupport](https://www.spigotmc.org/resources/7201/)
* [Landlord](https://www.spigotmc.org/resources/2735/)
* [Generex](https://github.com/mifmif/Generex) - This is not a bukkit plugin, it's compiled with plugin and uses a "lite" version compiled by myself.