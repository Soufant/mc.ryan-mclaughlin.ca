# mc.Ryan-McLaughlin.ca Client and Server Modifications
 - Click arrows next to links for more information like features and required mods.
 - Hold Ctrl While Clicking Links, or Click The Scroll Wheel On Links To Open Them In A New Tab.

## Client Modifications
Please Note That:
 - No modifications are required to join the server, but some are required for full functionality.
 - Minecraft Bedrock players are unfortunately unable to use any client modifications due to how Microsoft has developed this version of the game.

### Required For Server Features
 - A Mod Loader For Minecraft Version **1.19+**
   - <details>
     <summary><a href="https://fabricmc.net/use/installer/">Fabric (Recommended)</a></summary>
       Typically Releases A Few Hours After A New Minecraft Update <br> 
       Lightweight <br>
       Modular <br>
       Modern <br>
       <details>
       <summary><a href="https://modrinth.com/mod/fabric-api">Fabric API</a></summary>
         Required By Many Fabric Mods <br>
         Official Mod By Fabric Developers
       </details>
     </details>
   - <details>
     <summary><a href="https://quiltmc.org/install/">Quilt (Fork of Fabric)</a></summary>
       Typically Releases Same Day As New Minecraft Update <br> 
       Lightweight <br>
       Modular <br>
       Modern <br>
       <details>
       <summary><a href="https://modrinth.com/mod/qsl">Quilted Fabric API and Quilt Standard Libraries (QFAPI/QSL)</a></summary>
         Required By Many Fabric/Quilt Mods <br>
         Official Mod By Quilt Developers
       </details>
     </details>
   - <details>
     <summary><a href="https://files.minecraftforge.net/net/minecraftforge/forge/">Forge (Not Recommended)</a></summary>
       Releases After New Minecraft Updates Can Take Days or Even Longer <br> 
       Contains Lots of Old Code To Maintain Compatibility With Older Mods <br>
       Larger Catalog of Mods
     </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/simple-voice-chat">Simple Voice Chat</a></summary>
     Proximity and Group Voice Chat
   </details>
   
### Recommended For Client Performance

#### Fabric / Quilt[^Quilt]
 - <details>
   <summary><a href="https://modrinth.com/mod/sodium">Sodium</a></summary>
     Modern Rendering Engine <br>
     Framerates Usually Increase By 250%-500%
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/starlight">Starlight</a></summary>
     Makes Lighting Updates Over 25X Faster
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/ferrite-core">FerriteCore</a></summary>
     Memory Usage Optimizations
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/lithium">Lithium</a></summary>
     Game Logic Optimization <br>
     Speeds Up Game Calculations With No Changes To Vanilla Mechanics
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/ebe">Enhanced Block Entities</a></summary>
     <strong>REQUIRES FABRIC API or QFAPI/QSL</strong> <br>
     Reduces Lag Around Block Entities Like Chests <br>
     Fixes Smooth Lighting On Block Entities
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/krypton">Krypton</a></summary>
     Optimizes The Networking Stack
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/memoryleakfix">Memory Leak Fix</a></summary>
     Patches Memory Leaks To Prevent 'Out Of Memory' Crashes
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/entityculling">EntityCulling</a></summary>
     <strong>REQUIRES FABRIC API or QFAPI/QSL</strong> <br>
     Doesn't Render Hidden Entities
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/dashloader">DashLoader</a></summary>
     Caches Minecraft Assets So They Dont Need To Be Loaded Everytime
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/lazydfu">LazyDFU</a></summary>
     Makes The Game Boot Faster <br>
     Doesn't Load Certain Elements Until They Are Needed
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/indium">Indium</a></summary>
     <strong>REQUIRES SODIUM</strong> <br>
     Allows Fabric Rendering API Mods To Use Sodium Rendering
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/dynamic-fps">Dynamic FPS</a></summary>
     Reduces The Framerate To 1 FPS When Minecraft Is In The Background
   </details>

#### Forge

### Recommended For Client Features

#### Fabric / Quilt[^Quilt]
 - <details>
   <summary><a href="https://modrinth.com/mod/modmenu">Mod Menu</a></summary>
     Adds A Menu To View and Configure Installed Mods
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/cloth-config">Cloth Config API</a></summary>
     Needed To Access Some Mod Configuration Menus
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/iris">Iris Shaders</a></summary>
     <strong>REQUIRES SODIUM</strong> <br>
     Modern Shaders <br>
     Compatible With Most Optifine Shaders
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/lambdynamiclights">LambDynamicLights</a></summary>
     <strong>REQUIRES FABRIC API or QFAPI/QSL</strong> <br>
     Dynamic/Handheld Lighting Without Shaders
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/wthit">What The Hell Is That?</a></summary>
   <strong>REQUIRES BAD PACKETS</strong> <br>
   <details>
   <summary><a href="https://modrinth.com/mod/badpackets">Bad Packets</a></summary>
     Packet Translation Layer
   </details>
     Displays What You're Looking At
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/appleskin">AppleSkin</a></summary>
     <strong>REQUIRES FABRIC API or QFAPI/QSL</strong> <br>
     Allows You To See Your Saturation Level <br>
     Hold or Hover Over Food To See Hunger and Saturation Values
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/cit-resewn">CIT Resewn</a></summary>
     Allows Resource Packs To Use Different Item Texture Based On Factors Such As Durability, Name, etc.
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/continuity">Continuity</a></summary>
     <strong>REQUIRES FABRIC API or QFAPI/QSL</strong> <br>
     <strong>REQUIRES INDIUM IF SODIUM IS INSTALLED</strong> <br>
     Allows Resource Packs To Use Connected Textures <br>
     Includes Resource Pack With Default Connected Textures
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/betterf3">BetterF3</a></summary>
     <strong>REQUIRES FABRIC API or QFAPI/QSL</strong> <br>
     Makes The F3 Menu Customizable And Colour Coded
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/reeses-sodium-options">Reese's Sodium Options</a></summary>
     <strong>REQUIRES SODIUM</strong> <br>
     Nicer Looking Options Menu For Sodium
   </details>
 - <details>
   <summary><a href="https://modrinth.com/mod/sodium-extra">Sodium Extra</a></summary>
     <strong>REQUIRES FABRIC API or QFAPI/QSL</strong> <br>
     <strong>REQUIRES SODIUM</strong> <br>
     Extra Settings Options For Sodium
   </details>
#### Forge

[^Quilt]: Not all modifications are guaranteed to work as intended with Quilt

## Server Modifications
These modifications are implemented server-side, you as a player do not need to do anything.
