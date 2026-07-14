---
icon: cubes
---

# Modpack Information

The modpack must currently be installed manually. It is a **Fabric 26.2** modpack with around 200 mods. Many of these are library or performance-based mods. We will once again be using the Modrinth launcher for this modpack.

{% hint style="warning" %}
If you're unable to use the Modrinth launcher, it is possible to download the .mrpack file and exchange it for a ZIP file by visiting [this website](https://fabulously-optimized.github.io/mrpack-to-zip/) and providing the .mrpack file. You can then install the mod files manually - however, **we strongly recommend using the Modrinth launcher if possible.**
{% endhint %}

### Installation

{% file src="../.gitbook/assets/The Chertia Wastes 8.0.mrpack" %}

| Step                                                                                                                                                                                                            | Image                                                                     |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| Download the .mrpack file above.                                                                                                                                                                                | <img src="../.gitbook/assets/image (21).png" alt="" data-size="original"> |
| Open the Modrinth launcher and click the "+" button on the left-hand side to create a new instance.                                                                                                             | <img src="../.gitbook/assets/image (22).png" alt="" data-size="original"> |
| Select "Install modpack".                                                                                                                                                                                       | <img src="../.gitbook/assets/image (25).png" alt="" data-size="original"> |
| Select "Import modpack" and select the downloaded .mrpack file.                                                                                                                                                 | <img src="../.gitbook/assets/image (26).png" alt="" data-size="original"> |
| You can select "Install anyway". However, I recommend leaving this warning enabled for general use of Modrinth. The mudpack only contains mod files downloaded directly from Modrinth and configuration files.  | <img src="../.gitbook/assets/image (27).png" alt="" data-size="original"> |
| Done! The modpack is installed and ready to play. You can follow the additional instructions below to improve performance.                                                                                      |                                                                           |

{% hint style="info" %}
**3 GB of Distant Horizons files will be downloaded to your instance by default.**

Please note: when you first join the server, your client will begin to download around 3 GB of Distant Horizons data. This will slowly download all of the server's LODs so you can essentially have infinite render distance on the server. If you wish to disable this, you can either disable Distant Horizons or open the mod's settings and set "Enable Server Generation" to false.
{% endhint %}

***

***

### Performance Improvements / Fixes

#### RECOMMENDED: Increasing Allocated RAM & Adjusting Garbage Collector

If you have RAM to spare, it is recommended that you increase the allocation from 6 GB to at least 8  GB. Additionally, Distant Horizons recommends using ZGC as Minecraft's garbage collector, which is easy to do.

| Step                                                                                                                             | Screenshot                                                                |
| -------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| Allow the modpack to download. When finished, open the instance and select "Instance settings" at the top right.                 | <img src="../.gitbook/assets/image (30).png" alt="" data-size="original"> |
| Under "Java and memory", check "Custom meory allocation" and adjust the slider. Changing it to 8 GB, or 8192 MB, is recommended. | <img src="../.gitbook/assets/image (34).png" alt="" data-size="original"> |
| Check "Custom Java arguments" and enter `-XX:+UseZGC`.                                                                           | <img src="../.gitbook/assets/image (35).png" alt="" data-size="original"> |
| Here is what the finished screen should look like. You can now launch the game.                                                  | <img src="../.gitbook/assets/image (36).png" alt="" data-size="original"> |

#### Fixing Crashes Related to Vulkan / Using Shaders

If you wish to use shaders or you are having crashes due to the modpack's preference of Vulkan over OpenGL, you can follow these steps.

**Using Shaders is not recommended as the Minecraft rendering engine is in a weird place, and compatibility issues are frequent.** It's worth noting that I personally receive a 20%-50% increase in FPS by using Vulkan (the modpack's default setting).&#x20;

| Step                                                                                                                     | Screenshot                                                                |
| ------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------- |
| On the instance screen, select "Open folder". Ensure the game is closed.                                                 | <img src="../.gitbook/assets/image (37).png" alt="" data-size="original"> |
| Find "options.txt" and open it. Find "preferredGraphicsBackend" and change the value from "vulkan" to "opengl".          | <img src="../.gitbook/assets/image (38).png" alt="" data-size="original"> |
| Save the file.                                                                                                           | <img src="../.gitbook/assets/image (39).png" alt="" data-size="original"> |
| Back in the folder, navigate to the "config" folder and find "DistantHorizons.toml". Open the file with any text editor. | <img src="../.gitbook/assets/image (41).png" alt="" data-size="original"> |
| Using control+f or command+f, find "renderingEngine" and change the value from "BLAZE\_3D" to "OPEN\_GL".                | <img src="../.gitbook/assets/image (42).png" alt="" data-size="original"> |
| Save the file.                                                                                                           | <img src="../.gitbook/assets/image (43).png" alt="" data-size="original"> |
| If you want to use shaders, return to the instance screen, find "Iris Shaders", and enable the mod.                      | <img src="../.gitbook/assets/image (40).png" alt="" data-size="original"> |
