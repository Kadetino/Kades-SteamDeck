## Lutris
### General steps
* Install Lutris
* Install ProtonUp-Qt
* Create Lutris folder for prefixes
* Focus Lutris app
* Top right - Add locally installed game
* Game info - Enter name, select `Wine` as runner
* Game options - Select wine prefix folder that was created earlier
* Runner options - Select `lutris-GE-Proton#-##`
* Save changes
* Click on newly created game
* Run EXE inside wine prefix
* Select installer
* After the installation is done, right click the game, configure
* Game Options - select Executable path (what was installed)
* Try launching the game
* if it doesn't work, check SteamDB for dependencies (your package/game), depots tab
* click on game, winetricks, windows dll or components, select needed ones (better one by one)
* Right click on game, add steam shortcut
* if didn't work, Steam -> add custom game -> Lutris
* Change properties of this game
* target: "flatpak"
* Start in: ""
* Launch options: run net.lutris.Lutris lutris:rungame/<here-goes-identifier-from-lutris-game-info>
