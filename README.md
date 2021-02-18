# 1. Installing the Modpack

This section will walk you through the process of installing the BTE modpack required for building and contributing to the project.

This page is split into 3 parts, using the automated installer, performing a manual installation, and installing Optifine. Use the contents on the right to easily navigate through the page.

## 1.1. Using the Automated Installer <a id="using-the-automated-installer"></a>

To begin you first need to download the correct installer for your operating system. These can be found in \#downloads on the discord, or below.

* [Windows Installer](https://bte-installer.s3.amazonaws.com/public/installer/v1.11/BTEInstaller-1.11-windows.zip)
* [Mac Installer](https://bte-installer.s3.amazonaws.com/public/installer/v1.11/BTEInstaller-1.11-mac.dmg)
* [Linux Installer](https://bte-installer.s3.amazonaws.com/public/installer/v1.11/BTEInstaller-1.11-linux.tar.gz)

Next, simply run the file by double clicking it.

Common problems that can occur:

* Windows: Press “More Info”, then “Run Anyways” if Windows blocks the installer
* Mac: The installer unfortunately only runs on MacOS 10.15.x, you will need to do a manual install, listed below

## 1.2. Performing a Manual Installation <a id="performing-a-manual-installation"></a>

In a manual installation, you will download the files and add them to your mods manually. Please note that this method will have a harder time updating, should any updates come. A manual install may also have issues with worlds, and the automated installer is always recommended over a manual install, if possible. There are two ways to perform a manual install:

1. MultiMC
2. Forge

We recommend MultiMC for use with the Modpack, as the install won’t affect your existing Minecraft installation.

### 1.2.1. MultiMC <a id="multimc"></a>

First, lets make sure you have MultiMC installed. [Download MultiMC](https://multimc.org/#Download)

Install and launch MultiMC, then follow the instructions below.

1. First, set your account by clicking on the Accounts on top right and pressing “Manage Accounts”
2. Click the `Add` button, and log in using your Mojang username and password.
3. Create a new MultiMC profile by pressing `Add Instance` in the top left.
4. Switch to the `Import from zip` tab, then paste `https://bte-installer.s3.amazonaws.com/public/modpack_versions/BuildTheEarthPack_1.6.zip` into the text box.
5. Once the importing has finished, click the `Edit Instance` button, and then the `Settings` tab.
6. Check the `Memory` box, and use the arrow buttons to change the maximum memory allocated. The recommended amount of memory is about 4-8 GB.
7. Launch the modpack by double clicking the icon.

### 1.2.2. Forge <a id="forge"></a>

1. Install forge from [this link](https://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.12.2.html).
2. Download the modpack file [here](https://bte-installer.s3.amazonaws.com/public/modpack_versions/BuildTheEarthPack_1.6.zip)
3. Extract the file a folder of your choice.
4. Go into the extracted folder, then the overrides folder.
5. Move all the mods from the `mods` folder to your mods folder of `.minecraft`
6. Move the `Build The Earth (new projection)` folder from the `saves` folder to your own `saves` folder
7. Run the forge 1.12.2 profile in the minecraft launcher, then make a new world with [these settings](https://cdn.discordapp.com/attachments/691034211464773684/711678233179062283/settings.png)

## 1.3. Installing Optifine <a id="installing-optifine"></a>

This section is split into parts based on how you installed the modpack. Use the sidebar to navigate to each one.

Before starting, download the most recent version of Optifine 1.12.2 from [here](https://optifine.net/downloads)

### 1.3.1. Automated Installer <a id="automated-installer"></a>

Use the section corresponding to your operating system to install optifine.

#### 1.3.1.1. Windows <a id="windows"></a>

1. Open up your `.buildtheearth` folder. Press `Win + R`, paste `%AppData%/.buildtheearth` , and press enter.
2. Go into the `mods` folder.
3. Move or copy the Optifine jar from the download location to the folder.

#### 1.3.1.2. Mac <a id="mac"></a>

1. Open up your `.buildtheearth` folder. Open Spotlight with `⌘ + Space`, paste `~/Library/Application Support/buildtheearth` , and press enter.
2. Go into the `mods` folder.
3. Move or copy the Optifine jar from the download location to the folder.

#### 1.3.1.3. Linux <a id="linux"></a>

1. Open up your `.buildtheearth` folder. Navigate to your main directory and go into `.buildtheearth`
2. Go into the `mods` folder.
3. Move or copy the Optifine jar from the download location to the folder.

### 1.3.2. MultiMC <a id="id2"></a>

1. Open MultiMC, click the `Build the Earth` profile, and press `Edit Instance`
2. Click the `Loader Mods` tab, and then `Add` on the top right.
3. Naviage to where you downloaded Optifine, and double click it.
4. You’re done!

### 1.3.3. Forge <a id="id3"></a>

#### 1.3.3.1. Windows <a id="id4"></a>

1. Open up your `.minecraft` folder. Press `Win + R`, paste `%AppData%/.minecraft` , and press enter.
2. Go into the `mods` folder.
3. Move or copy the Optifine jar from the download location to the folder.

#### 1.3.3.2. Mac <a id="id5"></a>

1. Open up your `.minecraft` folder. Open Spotlight with `⌘ + Space`, paste `~/Library/Application Support/minecraft` , and press enter.
2. Go into the `mods` folder.
3. Move or copy the Optifine jar from the download location to the folder.

#### 1.3.3.3. Linux <a id="id6"></a>

1. Open up your `.minecraft` folder. Navigate to your main directory and go into `.minecraft`
2. Go into the `mods` folder.
3. Move or copy the Optifine jar from the download location to the folder.

