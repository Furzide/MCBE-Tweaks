# MCBE-Tweaks
this guide mainly applies to the windows version of Minecraft Bedrock Edition, however some of these tweaks will carry over to other platforms.

## **Disable V-Sync**
go to  *%LOCALAPPDATA%\Packages\Microsoft.MinecraftUWP_8wekyb3d8bbwe\LocalState\games\com.mojang\minecraftpe\options.txt*
and set **gfx_vsync** to 0.
You may also have to disable Vertical Sync in Nvidia Control Panel or in the AMD Software.


## **Bedrock Edition Version Switcher**
This will allow you to upgrade and manage versions of bedrock edition.
- https://bedrocklauncher.github.io/


## **Optimise In-Game Settings**
**FULLSCREEN: ON** - *windowed mode causes HUGE input lag.*

**HIDE PAPER DOLL: ON** - *This hides the render of your skin in the corner of the screen, saving a small bit of performance.*

**SCREEN ANIMATIONS: OFF** - *this will remove the animation when opening various gui elements.*

**SCREEN SAFE AREA:** *set this to 100% for everything to fit properly, Make this value smaller if you want to make the gui alot smaller.*

**VIEW BOBBING: OFF** - *Bedrock's View Bobbing sucks.*

**FANCY LEAVES:** *Turn this off for slightly more frames, at the expense of looks.*

**BEAUTIFUL SKIES: ON** - *This barely affects performance and you need it to see the custom skyboxes.*

**SMOOTH LIGHTING: ON** - *This barely affects performance and if you do turn it off, you will need fullbright in order for it to not look terrible.*

**FANCY GRAPHICS: ON** - *This has negligible impact on performance and it will make entities look extremely flat and 2D when off, won't reccomend.*

**DYNAMIC FOV:** *depends on the gamemode you use, if you use very high fov, speed will cause alot of distortion. I keep it on for the visual feedback when sprinting.*

**GUI SCALE: -1** - *This is the lowest you can go and any larger looks horrendous.*

**RENDER DISTANCE:** **16** - **12** *for high and mid pc's, 8 for low end machines. Due to how bedrock works, having tiny renderdistance barely improves performance and can sometimes make it worse due to unbalanced load on the CPU and GPU.*

**ANTIALIASING: OFF**

## **Alternative Versions of Bedrock**
**1.18.12 x86** - This version uses the old engine, can get double or even triple the performance compared to renderdragon. this version won't be compatible with most mods/clients, beware of that. (servers will soon drop support for this version)

**1.12.1** - This old version has the best performance and better animations, but not many servers support it. There is an open-source proxy called Tedac that can allow you to connect to modern pvp servers on 1.12.
- https://github.com/TedacMC/releases/releases

## **Make Bedrock Edition less ugly**
**Clean HUD Pack** - This pack is made by me, and adds transparent Java Chat and a Clear scoreboard without numbers.
- https://mcpedl.com/clean-hud-pack/

![cleanhud1](https://api.mcpedl.com/storage/submissions/166701/images/better-hud-pack_7.png)

## **Java Animations**
Bedrock's vanilla animations are horrificly bad, this resource pack by ambient makes the animations look and feel like Minecraft Java 1.7x.
- https://mcpedl.com/java-1-7-animations/

## **Fog Remover Shader**
there is a pack for non renderdragon versions of minecraft, however for renderdragon I have compiled my own shader that you will have to drop into the game's files.

**Non-RenderDragon:** https://www.mediafire.com/file/33ibsfwwehokkvy/
Double-Click the MCPACK file to import.

**RenderDragon:** https://github.com/Furzide/RenderDragonFogRemover

**to import a shader for renderdragon:**  
open the game's install directory from within the bedrock launcher:
![blauncher1](https://cdn.discordapp.com/attachments/1037432674672967733/1037457911661731852/unknown.png)
navigate to **Data > Renderer > materials** and proceed to drop the bin file/s in this folder.
![blauncher2](https://cdn.discordapp.com/attachments/1037432674672967733/1037458242839777421/unknown.png)

## **Fix Performance on RTX GPUs**
download and run **Nvidia Profile Inspector 2.4.0.1** or later  
- https://github.com/Orbmu2k/nvidiaProfileInspector/releases  

search and open the profile for **Minecraft**  

scroll down until you see the **"Raytracing - (DXR) Enabled"** setting. Set this to **RT Disabled.**  

Click **Apply Changes** at the top right of the screen.  
![npi1](https://cdn.discordapp.com/attachments/1037432674672967733/1047221676254953472/image.png)  
![npi2](https://cdn.discordapp.com/attachments/1037432674672967733/1047221676686970950/image.png)
