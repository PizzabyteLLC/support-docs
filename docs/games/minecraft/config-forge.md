---
title: Configuring a Minecraft Forge Server
layout: default
parent: Minecraft
nav_order: 1
---

# Configuring a Minecraft Forge Server

In this support article we will be running through the processes to properly configure a Minecraft Forge server. This includes things such as setting the correct Minecraft version and Forge version. For this example we will be installing [RLCraft](https://www.curseforge.com/minecraft/modpacks/rlcraft), a modpack available on CurseForge.

## Instructions

1. Ensure your server is running as a Forge server and **_not_** a Vanilla server.
    - If you are running a Vanilla server you won’t see the same options as shown below and will need to open a ticket with support to change your server over to Forge.
2. Ensure your server is stopped.
    - You can do this by going to the "Console" tab and pressing the "Stop" button.

3. Go to the “Startup” tab and enter the Minecraft version and Forge version you wish to use.
    - RLCraft _requires_ Forge => `14.23.5.2860` and Minecraft `1.12.2`.

4. We’ll type these into the Minecraft Version box as `1.12.2` and the Forge Version box as `1.12.2-14.23.5.2860`

> **Note**
>
> RLCraft _requires_ Java 8 be installed to run. You can change the version of Java a server is using by setting the Docker Image dropdown to the required version.

![Startup settings fully configured for RLCraft.](/assets/images/games/minecraft/forge-settings.png)

5. Next go to the "Settings" tab and press the "Reinstall Server" button
    - This will trigger our systems to reinstall your server jar as the correct Forge version.

> **Warning**
>
> Some files may be **deleted or modified** during this process. Ensure you have a backup of any files you wish to keep.

6. Return to the "Console" tab and start the server.

> **Note**
>
> The Forge Version box requires that the Minecraft version be prefixed. In this case it will be entered as `1.12.2-14.23.5.2860`
