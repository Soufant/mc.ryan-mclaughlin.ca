# mc.Ryan-McLaughlin.ca Client and Server Modifications

## Client Modifications
Please Note That:
 - No modifications are required to join the server, but some are required for full functionality/features.
 - Minecraft Bedrock players are unfortunately unable to use any client modifications due to how Microsoft has developed this version of the game.

### Required For Server Features
 - A Mod Loader For Minecraft Version **1.19.2**
   - [Fabric (Recommended)](https://fabricmc.net/use/installer/)
     - <details open>
       <summary><a href="https://modrinth.com/mod/fabric-api">Fabric API</a></summary>
         Required By Many Fabric Mods <br>
         Official Mod By Fabric Developers
       </details>
   - [Quilt (Fork of Fabric)](https://quiltmc.org/install/)   
   - [Forge (Not Recommended)](https://files.minecraftforge.net/net/minecraftforge/forge/)   
 - [Simple Voice Chat](https://modrinth.com/mod/simple-voice-chat) Proximity & Group Voice Chat

### Recommended For Client Performance

#### Fabric / Quilt[^Quilt]
 - <details open>
   <summary><a href="https://modrinth.com/mod/sodium">Sodium</a></summary>
     Modern Rendering Engine <br>
     Framerates Usually Increase By 250%-500%
   </details>
 - <details open>
   <summary><a href="https://modrinth.com/mod/ferrite-core">FerriteCore</a></summary>
     Memory Usage Optimizations
   </details>
 - <details open>
   <summary><a href="https://modrinth.com/mod/lithium">Lithium</a></summary>
     Game Logic Optimization <br>
     Speeds Up Game Calculations With No Changes To Vanilla Mechanics
   </details>
 - <details open>
   <summary><a href="https://modrinth.com/mod/entityculling">EntityCulling</a></summary>
     <strong>REQUIRES FABRIC API</strong> <br>
     Doesn't Render Hidden Entities
   </details>
 - <details open>
   <summary><a href="https://modrinth.com/mod/lazydfu">LazyDFU</a></summary>
     Makes The Game Boot Faster <br>
     Doesn't Load Certain Elements Until They Are Needed
   </details>
 - <details open>
   <summary><a href="https://modrinth.com/mod/indium">Indium</a></summary>
     <strong>REQUIRES SODIUM</strong> <br>
     Allows Fabric Rendering API Mods To Use Sodium Rendering
   </details>

#### Forge

### Recommended For Client Features

#### Fabric / Quilt[^Quilt]
 - <details open>
   <summary><a href="https://modrinth.com/mod/modmenu">Mod Menu</a></summary>
     Adds A Menu To View and Configure Installed Mods
   </details>
 - <details open>
   <summary><a href="https://modrinth.com/mod/iris">Iris Shaders</a></summary>
     <strong>REQUIRES SODIUM</strong> <br>
     Modern Shaders <br>
     Compatible With Most Optifine Shaders
   </details>
#### Forge

[^Quilt]: Not all modifications are guaranteed to work as intended with Quilt

## Server Modifications
These modifications are implemented server-side, you as a player do not need to do anything.
