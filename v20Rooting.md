
# PREREQUISITES:

## Download 10p

If you aren't on 10p or 10q, grab the H918 10p KDZ: here.
<script><a href="https://www.androidfilehost.com/?w=files&flid=282709">AndroidFileHost </a> Downloads for runningnak3d </script>

# I guess still FWUL which is a clusterfuck, but whatever

# Installing TWRP
Again, this will ONLY install TWRP onto download mode. What you do with TWRP when it is done is up to you. Flash Magisk or SuperSU. Flash a ROM, or just make a backup of your phone. It is up to you.
I would suggest flashing TWRP onto recovery as well, otherwise you will need to use the vol up + USB cable method to get to TWRP. There is no key combination to get to download mode.

Boot from your FWUL USB stick.
Put your phone into download mode. With the phone powered off, hold vol up and plug in the USB cable. You do not need to touch the power button -- the phone will power on and enter download mode.
Once booted, login. The password is: linux

# FWUL
Double click the LG folder that is on the desktop <br>
Double click on LG LAF (runningnak3d) icon and you will be at a terminal prompt. <br>
The following are the commands that you enter into that terminal. You can copy / paste them if you like.
Code:
git pull
git checkout h918-miscwrte
./step1.sh
When you are told to, pull the USB cable, and the phone will power off. You now have TWRP on your laf partition.

__It must be said again, flash TWRP onto recovery so you can easily get to TWRP.__

*OPTIONAL* <br>
If you would like to restore download mode onto your laf partition AFTER you have installed TWRP onto recovery:
Boot to TWRP that is on recovery
Flash this zip: laf_restore.zip
This can be done at any time after you are rooted. About the only reason you would want to flash laf back is if you use LG Backup.
TWRP has the ability to backup your phone, so I am not sure why someone would want this (maybe you are more comfortable with it?).
Also, flashing back to 100% unrooted stock can be accomplished by flashing a zip in TWRP, you don't NEED to flash a KDZ, but again, maybe you are more comfortable doing it that way.
The bottom line is TWRP on both laf and recovery is FAR FAR more useful than flashing laf back. You can test new versions of TWRP while keeping your old known working version (for example).


If you are having problems flashing a ROM, ask in the appropriate ROM thread.
If you are having problems with Magisk, ask in the Magisk thread.
If you are having problems with SuperSU, Lineage, or even TWRP itself, ask in the appropriate thread.

This thread is ONLY for problems if TWRP doesn't boot when you are done.

CREDITS:
Lekensteyn -- His base work on the G2 / G3 gave me a GREAT headstart!
@steadfasterX - He added some real nice features, great guy to bounce ideas off, and just testing crazy ideas because he wasn't afraid to brick his phone :) Also, for FWUL
tuxuser - Helping with my lacking in Python
@smitel - His original reverse engineering of LG UP. Great inspiration!
@me2151 - His original DirtySanta exploit. Without it, the V20 would probably still not be rooted.

-- Brian

XDA:DevDB Information
lafsploit, Tool/Utility for the LG V20

Contributors
runningnak3d
Source Code: https://gitlab.com/runningnak3d/lglaf


Version Information
Status: Stable
Current Stable Version: 1.1
Stable Release Date: 2018-07-15

Created 2018-04-05
Last Updated 2018-07-16
