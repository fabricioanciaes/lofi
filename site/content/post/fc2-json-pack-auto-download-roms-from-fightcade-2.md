---
title: FC2 JSON Pack (Auto Download roms from Fightcade 2)
date: '2020-11-20T01:36:22-03:00'
---
### Download `fc2roms.zip` and extract the `.json` files in the `Fightcade/emulator` folder just like the images on the How to use it section:

# [Download the fc2roms.zip](https://fightcade.download/fc2json.zip)

If you enjoy my work with either this or the other stuff I do you can support me here: https://ko-fi.com/lofi1048


[![buy me a coffee](https://i.imgur.com/T2KqPMB.gif)]("https://ko-fi.com/lofi1048")

If the json file link gives you a HTTPS error, make sure to click on advanced and then click _proceed to..._

**If the script breaks for some reason come back here and check if there's a newer one.**

---
### Changelog:

**FRM JSON PACK - 06/24/2022 (V10)**


- Included naomi 2 roms (All versions of Virtua fighter 4 + Beach Spikers and Virtua Striker 3)
- Reuploaded over 1200 roms that needed minor fixes (removing unused archives inside their zips), Thanks *anonymous*
- Fixed 50 roms that were broken
- Fixed rom dependencies for the following hacks:

```
sfa3aism,
xmcotabh,
vsavae,
mshbh,
hsf2pp,
wwfmanac,
msvsfbh,
mvscbh,
vampjbh,
sfa3sp2,
brkrevext,
marmatcp,
cybotsam,
kof98ratio,
mslug3rb,
mslug4ar,
mslug5sgf,
mslug5wd,
sfiii2bh,
sfiii3bh,
sfiii2bh,
sfz3mix,
umk3p,
umk3uk,
dinore,
doubledrsp,
kof2k1rp,
mslug2unity,
mslug3unity,
mslug4unity,
mslug5unity,
mslugunity,
mslugxunity,
ssf2xjr1trn,
```


### How to use it:

Download `fc2roms.zip` and extract the `.json` files in the `Fightcade/emulator` folder just like the images below

![https://i.imgur.com/J28ztQM.png](https://i.imgur.com/J28ztQM.png)

![https://i.imgur.com/KT4FU1d.png](https://i.imgur.com/KT4FU1d.png)

To download a game, just join a room and if you don't have the rom already it will auto download for you.

If something goes wrong, make sure to delete the rom inside the respective emulator folder, delete the problematic rom itself and some tmp files that might be there.

----

### Fixing the `Unknown encoding: CP655001` Error

Sometimes the built in downloader from fightcade just wont work on some systems
usually this is manifested by the console quickly closing without downloading the game, you can catch a glimpse of what happens:

![Unknown encoding: CP655001](https://cdn.discordapp.com/attachments/867081421531906059/993218694765355008/2022-07-03_134605.png)

Steps to fix:

1) Go to control panel and click "Clock and Region"
2) Click "Region"
3) Click the Administrative tab and then click the "Change system locale..." button
4) Uncheck the button for "Beta: Use Unicode UTF-8 for worldwide language support"
5) Restart computer
