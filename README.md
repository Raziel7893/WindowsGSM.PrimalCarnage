# WindowsGSM.PrimalCarnage
🧩WindowsGSM plugin that provides PrimalCarnage Dedicated server

## PLEASE ⭐STAR⭐ THE REPO IF YOU LIKE IT! THANKS!

### WindowsGSM Installation: 
1. Download  WindowsGSM https://windowsgsm.com/ 
2. Create a Folder at a Location you wan't all Server to be Installed and Run.
3. Drag WindowsGSM.Exe into previously created folder and execute it.

### Plugin Installation:
1. Download [latest](https://https://github.com/Raziel7893/WindowsGSM.PrimalCarnage/releases/latest) release
2. Either Extract then Move the folder **PrimalCarnage.cs** to **WindowsGSM/plugins** 
    1. Press on the Puzzle Icon in the left bottom side and press **[RELOAD PLUGINS]** or restart WindowsGSM
3. Or Press on the Puzzle Icon in the left bottom side and press **[IMPORT PLUGIN]** and choose the downloaded .zip

### Available options:
- ?AdminPassword=Password
- ?GamePassword=password
- ?RoundTimeLimit=0
- ?MatchScoreTarget=0
- ?bEnableDamage=0
- ?bEnableKilling=0
- ?bEnableKilling=True (Enables Killing)
- ?bEnableDamage=True (Enables Damage)
- ?bDisableKilling=True (Disables Killing)
- ?bDisableDamage=True (Disables Damage)
- ?BalanceTeams=True (Enables Team balance... which will also include auto balance)
- ?BalanceTeams=False (Gets rid of the team balance issues)

### Official Documentation
🗃️ more or less official, but it helped creating the CMD-Line https://steamcommunity.com/app/321360/discussions/1/494631967655276683/

### The Game
🕹️ https://store.steampowered.com/app/321360/Primal_Carnage_Extinction/

### Dedicated server info
🖥️ https://steamdb.info/app/224620/info/

### Port Forwarding (YOU NEED THIS, TO BE ABLE TO CONNECT FROM THE INTERNET(only for servers/pcs at home):
- If You don't know How: Google: YourRouterBrand + Portforwarding
- 7777 UDP - Default
- 27015 TCP - default query port

### Files To Backup
- Save Gane (You could only save serverfiles/PrimalCarnage/Saved , but that includes many big logs)
  - WindowsGSM\servers\%ID%\serverfiles/PrimalCarnage/Saved/SaveGames
  - WindowsGSM\servers\%ID%\serverfiles/PrimalCarnage/Saved/Config/WindowsServer", backupName="PrimalCarnage/PrimalCarnage/Saved/Config/WindowsServer
- WindowsGSM Config
  - WindowsGSM\servers\%ID%\configs

### Available Params
All these params are automatically set by WGSM
- -NOSTEAM                      Suggested StartParameters from the default start script, not sure what it does, changes nothing, so it is skipped by default. Maybe there is an update on release for it (cann be added in Additional Parameters)
- -log                          creates logfiles in serverId\serverfiles\PrimalCarnage\Saved\Logs

### How can you play with your friends without port forwarding?
- Use [zerotier](https://www.zerotier.com/) folow the basic guide and create network
- Download the client app and join to your network
- Create static IP address for your host machine
- Edit WGSM IP Address to your recently created static IP address
- Give your network ID to your friends
- After they've joined to your network
- They can connect using the IP you've created eg: 10.123.17.1:7777
- Enjoy

### Support
[WGSM](https://discord.com/channels/590590698907107340/645730252672335893)

### Give Love!
[Buy me a coffee](https://ko-fi.com/raziel7893)

[Paypal](https://paypal.me/raziel7893)

### License
This project is licensed under the MIT License - see the <a href="https://github.com/raziel7893/WindowsGSM.PrimalCarnage/blob/main/LICENSE">LICENSE.md</a> file for details

### Thanks
Thanks to ohmcodes for the Enshrouded and Palworld Plugins which i used for guidance to create this one
