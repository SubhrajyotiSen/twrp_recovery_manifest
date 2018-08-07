## Getting Started ##
---------------

To initialize your local repository using the OmniROM trees, use a command like this:

    repo init -u git://github.com/MOTO-M8916/twrp_recovery_manifest.git -b android-7.1

Then to sync up:

    repo sync

Then to build:

     build/envsetup.sh && make clean && breakfast osprey &&  make -j8 recoveryimage

