# umvc3-120
a Ultimate Marvel vs Capcom 3 mod for 120fps game content

I have been worked on this mod now and then in my spare time for like 1 year, and hosted the files previously here: https://1drv.ms/f/s!AgheTV2uw-epkmrrniIRP1jfs7Lb. But decided recently to move to github for better version info.

## what it is
It is a mod (current just a patched main program) to run the game (Ultimate Marvel vs Capcom 3) at 120fps, rather than the original 60fps.

The benefits of 120fps content are:

1. eye-tracking-based-blur control: 120fps by nature is with less persistence (8ms), so it is with less eye-tracking-based-blur. Not to mention you can use monitor with strobe to totally remove the blur.

2. smoother animation. It can be only subtle, but if you play 120fps hack and go back to 60fps version you will see the difference.

3. a little less input lag, perhaps.

## how to use
First you need a 120hz monitor, a powerful enough PC (actually an intel i3 + an old gtx750 are enough for 1080p play), and of course a steam account with the UMVC3 game purchased and installed.

Then you can download the zipped file (umvc3-120.zip here), put the unzipped content in the umvc3.exe installation location, which normally is "C:\Program Files (x86)\Steam\steamapps\common\ULTIMATE MARVEL VS. CAPCOM 3". (It won't replace any file, but put an extra patched program, usually named umvc3-120.exe)

Then just run the patched program (with steam up and logged in) to enjoy the smoothness.

## files description
src/umvc3-120.1337         : the patch "source" made/used with x64dbg.

src/umvc3.7z               : the "ida pro 7 free" database, with comments/function-namings. It is incomplete (of course not every instruction is analyzed) and some comments can be misleading since they were done at different time. Also it may not be always up-to-date.

Old\_Revision\_history.txt   : the revision-history of the mod before being put here.
