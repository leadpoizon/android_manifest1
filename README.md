Getting Started
---------------

To build PureNexus from source, you'll need to be familiar with
[Git and Repo](http://source.android.com/download/using-repo).


To initialize your local repository, use this command:

	repo init -u https://github.com/leadpoizon/android_manifest.git -b mm

Then to sync source, use this command:

	repo sync

After syncing is done, use these commands to build:

    For UserDebug Builds
    1.) . build/envsetup.sh
    2.) brunch xxxx    xxxx= device name aka shamu

    For User Builds
    1.) . build/envsetup.sh
    2.) breakfast
    3.) Pick Device
    4.) mka shamu
