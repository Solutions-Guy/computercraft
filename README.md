# Create a simple house in ComputerCraft

Pre-requisites:
* Minecraft Java 1.19.4
* Download and execute Fabric Installer: https://fabricmc.net/use/installer/
* Download Fabric API Jar file: https://www.curseforge.com/minecraft/mc-mods/fabric-api/files
* Download ComputerCraft Jar file: https://www.9minecraft.net/cc-tweaked-mod/#CC_Tweaked_Mod_1194_1182_Download_Links
* Download Mod Menu Jar file: https://modrinth.com/mod/modmenu/version/6.2.2
* Move all 3 mods into the mods folder: users/username/AppData/Roaming/.minecraft/mods // search for %appdata% on Windows

## Load the game and setup the following:
* Computer
* Disk Drive // with Floppy Disk
* Turtle
Note: The turtle should be on an elevated platform to be deployed in a straight line, it will starts placing blocks beneath it.

## Turtle setup:
Go into Turtle command line 
```
$ Command: refuel all // only needs a stack to complete this house)
```
Note: Make sure the Turtle has fuel

## Setup 4 different items
* Wall material // slot 1
* Door // slot 2
* Roof material // slot 3
* Torch // slot 4
  
## Deploy the Turtle
Create a program and save it to a disk drive. 

Go into Turtle command line
```
$ dir // you should see 'disk' and 'rom'
$ cd disk //change to the disk drive
$ edit <program_name, eg: simple_house> // opens a new window to enter the code
$ print("Hello World") // This is just temporary
```
Note: Press CTRL, save the File and Exit.

At this point, you can exit the game and edit the code outside of the game.
* In Windows, the disk file should be under .minecraft/saves/<world_name>/computercraft/disk/<disk_#>
* Edit the <program_name> and save it. //open .lua file in text editor, copy and paste the <simple_house> code
```
$ Command:<program_name, eg: simple_house>
```
