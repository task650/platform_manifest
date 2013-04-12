platform_manifest
=================

****** For Linaro Builds ******

$ repo init -u https://github.com/task650/platform_manifest.git -b linaro

$ repo sync -jXX (you choose the amount of threads based upon your computer specs)

$ USE_CCACHE=1 . build/envsetup.sh && time brunch d2att mka bacon
