platform_manifest
=================

$ repo init -u https://github.com/task650/platform_manifest.git -b kitkat

$ repo sync -jXX (you choose the amount of threads based upon your computer specs)

$ . build/envsetup.sh && time brunch <device> mka bacon
