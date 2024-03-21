<p align="center">
<img src="https://github.com/bananadroid/docs/blob/master/bananadroid_banner.png?raw=true" > 
</p>
-------------------------------------------------------------------------------------------------------

BananaDroid:
====================
Another cherry-picking ROM, developed by an usual person, nothing special


To initialize your local repository, use this command:
-----------------------------------------------------

    repo init -u https://github.com/BananaDroid-Revived/android_manifest.git -b 11 --git-lfs

To initialize Shallow-Clone, use this command:
---------------------------------------------

    repo init --depth=1 -u https://github.com/BananaDroid-Revived/android_manifest.git -b 11 --git-lfs

To sync the repository, use this command:
-----------------------------------------

    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags

To Build, use following commands:
---------------------------------
    
    . build/envsetup.sh
    lunch banana_<devicecodename>-userdebug
    make banana

---------------------------------------------------------------------------------------------------------

Join our [**Telegram Group**](https://t.me/bananadroid) and follow our [**Telegram Channel**](https://t.me/bananadroidchannel)

Thank you!

---------------------------------------------------------------------------------------------------------
