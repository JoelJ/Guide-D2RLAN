# Guide-D2RLAN
This is notes from the official guide video found here: https://www.youtube.com/watch?v=XIaw-XNrrzo

1. Download D2RLAN from the [official download page](https://www.d2rmodding.com/d2rlaunch). For Single Player mods, you can use the "D2RLaunch" button. For TCP/IP support choose the "D2RLAN" button. Always be sure to download mods/managers for ANY game from official sources. 
2. Unzip the contents of the ZIP somewhere convinient. I put it in the "Documents" directory and created a "D2Modding" directory there. So after unzipping I have a "C:\Users\{me}\Documents\D2Modding\D2RLAN" directory, where `{me}` is your usename. The remainder of this guide will assume you did the same.
3. In the `C:\Users\{me}\Documents\D2Modding\D2RLAN` directory there should be a `Beacon.exe` and a `D2RLAN.exe` file. Beacon is for finding/hosting LAN games. D2RLAN is the mod launcher. The folders are just translation files. And the other files in that directory are libraries and config files you can ignore. You can make a shortcut of the `D2RLAN.exe` and `Beacon.exe` files on your desktop, for example.
4. Launch `D2RLAN.exe`. You might be prompted to install the .NET framework or other dependencies if your computer doesn't already have them installed. Those prompts should only be taking you to the official Microsoft download pages. Please pay attention to where you're downloading these files from. :)
5. In the screen that pops up, there's a `Download New Mod` button. Click that.
6. A little mini window pops up with a couple dropdowns. In the top dropdown select `Base TCP Files` to begin downloading the TCP/IP mod.
7. A progress bar will appear and complete fairly quickly. You might get a couple prompts with "OK". Go ahead and click "OK" until you get a prompt that has a "YES" and a "NO" option.
8. This YES or NO prompt is asking you if you want to DOWNLOAD 26GB (By choosing NO) or point to an existing game data directory downloaded by D2RLAN previously (By choosing YES).
9. Select NO and wait a long time (took a couple hours on my high speed connection) for 26GB worth of data to be downloaded. Note that this step will detect if it's been partially done before and will pick up where it left off. So don't worry if your computer crashes or Windows Update tries to ruin your day. When resuming, notice the "Progress" says something like "23456 / 146689 files". If resuming that second number will be SMALLER (based on how far you got previously) but the first number will still start at 0. This is expected behavior!
10. If you've selected "NO" before, you can skip the download by saying "YES" this time and browing to the "data" directory from befor. This directory will contain "config", "data", and "indicies" directories.
11. Notice now in your `C:\Users\{me}\Documents\D2Modding\D2RLAN` directory now has a fourth folder called `D2R`. This contains the game files.
12. Inside the new `D2R` directory there will be a `Mods` directory. This is where the TCP mod (and others) will be downloaded to.
13. At the bottom of the main D2RLAN window, there's a `Mod Choice` dropdown. You should now be able to select `TCP` to play the Vanilla 2.4 D2R game with TCP/IP support.
15. The [remainder of the video](https://youtu.be/XIaw-XNrrzo?si=wR7g0TxqoBgEZ8uX&t=564) is an overview of the UI. Linked is a quick link to that portion of the video.
16. Click "Play Mod" to launch the game.
17. In the game there should be a "TCP/IP" button. You can click this to HOST or JOIN a game.
