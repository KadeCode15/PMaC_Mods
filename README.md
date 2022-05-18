# PMaC_Mods
A collection of all the mods needed to play on the PMaC server.

## Getting Started with Mods
1. Click the `Code` button above and select `Download ZIP`
     ![image](https://user-images.githubusercontent.com/49326307/169130125-87d62702-c760-41d1-8c79-15e7c00facac.png)

2. Open the run application on your computer on Mac this is the Go application (I think).
    * Just press the windows key then type `run`. It should be the first app that comes up.
3. Type `%appdata%\.minecraft` into it and press enter. On Mac type in `~/Library/Application Support/minecraft` (Users/**user**/Library/Application Support/minecraft)
    * This will open up your file explorer to your installation directory for Minecraft.
    * ![image](https://user-images.githubusercontent.com/67335671/147997552-99e1408c-40d8-44ff-8fd5-21cfac203dc5.png)
4. If you don't have a folder named `mods` in that directory, create one spelled exactly like that.
5. Move the `.zip` file you downloaded into the `mods` directory.
6. Unzip the file.
    * At this point, you will choose between the `Optifine` and `IrisSodium` folders. Delete the one you don't want. They are both performance mods, but have slightly different features.
      * `Optifine` - Easier to configure (recommended).
      * `IrisSodium` - More dificult to configure, but roughly 2x as many fps as Optifine.
    * Make sure all the `.jar` files from either the `Optifine` or `IrisSodium` folder (whichever you chose) are placed directly in the `mods` folder. They cannot be in a subdirectory.
     ![image](https://user-images.githubusercontent.com/67335671/147997090-0d032d28-f97c-4085-b3cf-c29de36df14f.png)

7. Install fabric by running the fabric installer in the repo: `fabric-installer-0.10.2.exe`. You can run this in any directory, but move it out of your mods folder (a good spot would be in your downloads or something, then double click it). The default settings will be fine, just make sure the version is the same. Our version is **1.18.2**, and you don't have to change the loader version or install directory.
     ![image](https://user-images.githubusercontent.com/49326307/169109756-7d0d7b7f-b8df-44fb-97c5-55efa02e3478.png)
8. Restart Minecraft and select `fabric-loader-1.18.2` as your version of minecraft.
     ![image](https://user-images.githubusercontent.com/49326307/169110162-618a37ed-ec07-49dc-add3-59176c4c3a94.png)
9. Play PMaC!

