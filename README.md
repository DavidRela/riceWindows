# WINDOWS 10 RICING
Tools, tutorials, and resources to get the best possible experience on an Microsoft Windows based system.

## Screenshots
This are some screenshots of the final result.
![Desktop Screenshot](/screenshots/screenshot01.jpg?raw=true "")
![Desktop Screenshot](/screenshots/screenshot02.jpg?raw=true "")
![Desktop Screenshot](/screenshots/screenshot03.jpg?raw=true "")

## Index
1. Download the needed files.
2. Download & Install the software you want / need for your daily use on Windows.
3. Tweak the system to get the best possible performance.
4. Customize the Windows Interface (ricing).
5. Clean everything up.

## Notes
- This is a long process, it can **break** your windows installation and harm your computer.
- This is only recommended for **advanced** users.
- Backup all your data **before** you start.
- Proceed at your own **risk**.

### 1.DOWNLOAD THE NEEDED FILES
Make sure you have downloaded:
- Cursors.
- Fonts.
- Icons.
- Software tweaks.
- Themes.
- Tweaks.
- Wallpapers (optional).

### 2. DONWLOAD & INSTALL THE SOFTWARE YOU WANT / NEED FOR YOURE DAILY USE ON WINDOWS
In my case I use:
- 3DS Max Autodesk
- 7zip.
- μTorrent (2.2.1).
- Adobe Creative Cloud.
- Google Chrome (Chromium).
- iTunes.
- Steam.
- Sublime Text 3.
- VLC.

### 3. TWEAK THE SYSTEM TO GET THE BEST POSSIBLE PERFORMANCE
1. Update Windows to the latest version.
2. Update GPU/Proccesor drivers.
3. Control Panel > Power Options > High Performance (Disable Sleep).
4. Let the system idle for 2 minutes to get every proccess loaded. Then exec this command on a *cmd* with admin priviledges: `winsat formal`.
5. Disable Windows Defender + Notifications.
6. Configure NVIDIA 3D Settings like this: ![Desktop Screenshot](/screenshots/screenshot04.png?raw=true "")
7. WINDOWS KEY + R > `msconfig`: Boot Tab > No GUI Boot > Timeout = 03 seconds > Advanced Options > Number of processors = Max availabes.
8. Task Manager > Startup > Disable everything you don't want.
9. System > Advanced System Settings > Performance Settings > Disable as much as you can without making your system look awful.
10. System > Advanced System Settings > System Protection > Configure > Disable System Protection > Delete File.
11. Control Panel > Uninstall a Program > Turn Windows Features ON/OFF > Turn everything off but `.NET 4.6 | Media Features | Print to PDF`.
12. *Reboot Your System*.
13. Open the `Tweaks` folder and exec both scripts with admin priviledges. (recomended to exec them twice both as admin and normal user)
14. Reboot and you are done.

### 4. CUSTOMIZE THE WINDOWS INTERFACE (RICING)
1. Open the `Themes` folder and install *UxStyle*.
2. On the `Themes` folder Install *OldNewExplorer* and configure it however you want.
3. Choose your theme and Copy it to `C:\Windows\Resources\Themes`.
4. Set the theme on `Personalization`.
5. Go to the `Fonts` folder select them all (CRTL + A) > Right click > Install.
6. Exec the `changeFontWin10.reg` script.
7. Go to `cursors` folder > choose your prefered cursor pack > exec `install.inf`.
8. To apply the cursors go to Personalization > Mouse Pointers.
9. Go to `Icons` folder and exec the ".exe" of your prefered icons.
10. Select and apply your favourite wallpaper. (My favourite ones are included on the `walls` folder)
11. Reboot to apply all changes.


### 5. CLEAN EVERYTHING UP
To make sure you have not downloaded any virus during the process install `Malwarebytes` and run a scan.
To clean registry and residual files install `Ccleaner` and go through the options.

After you are done with both things I recommend to uninstall both programs.


## License
All rights reserved. David Rela. 2016.
