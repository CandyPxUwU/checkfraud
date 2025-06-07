# checkfraud
Alternative sanitycheck for the Waydroid Steam Deck install script.

Credits to [ryanrudolfoba](https://github.com/ryanrudolfoba/SteamOS-Waydroid-Installer/commits?author=ryanrudolfoba) for making the waydroid steamdeck install script, and sanitycheck.sh.
## What is this?
This is a short replacement script for sanitycheck.sh, the changes are as follows.
- Replace the kernel check at Lines 14-22 with a dummy check.

```
sanity check - make sure kernel version is supported. exit immediately if not on the supported kernel
echo Checking if kernel is supported.
if [ 1 = 1 ]
then
	echo CandyPX Kernel Check skipper active, here be dragons, and green robots!
else
	echo This message should not be able to show, if you are seeing this, youre on your own.
	exit
fi
```
