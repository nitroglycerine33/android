android
=======

4.4 manifest

Welcome to Eclipse! You are free to build this for your own use. If you port it to another device I ask you to please link back to elementalxdesigns.com and would appreciate you sharing your work on there as well. Thanks!

To sync the source use the following commands:

repo init -u https://github.com/nitroglycerine33/android.git -b kk44

repo sync


To build:

source build/envsetup.sh
lunch
*choose device
make eclipse -j* (choose thread number)


For detailed building instructions:

http://www.elementalxdesigns.com/eclipse/showthread.php?120-AOSP-Elemental-X-Compiling-Guide-Linux-Mint-14-KDE


