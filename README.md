## MagicGApps [7.1.x]

You may be asking yourself, "But... why?" 
Well, this systemless implementation of GApps makes it very easy to customize and update the included Google setup. 
For instance, ever seen that feature in Titanium Backup, "Integrate system app updates into /system?" Exactly. Now you can do that without writing to the system partition and then repack the module with the updated changes. If you are into doing this sort of thing, you'll need this: https://forum.xda-developers.com/apps/magisk/flashable-zip-magisk-img-resizer-t3593207.

In addition to that, you can add/replace/remove things from the package to suit your needs the easiest and fastest way possible (you will see some of these cool tweaks below). One more advantage: your ROM updates will be slightly faster, since GApps don't have to be backed up and restored afterwards every time you flash a new version of your ROM (i.e., LineageOS adon.d backup feature). AND my favorite, you can make regular backups of your magisk.img file to simplify future ROM setups even further!
***
Core Google syncing APKs (Google Play Services, SetupWizard, Google Play Store)

Google Play Services removed from Doze Whitelist to save battery

Google TTS

Google App

Nova Launcher
***
If you find Google Play Services or any other app force closing after installing this module, just ignore it. Everything will normalize as you set up Android. A reboot afterwards is recommended.


Credits:

The Flash, BeansTown106, Surge1223, BaNkS & otonieru


Thread: https://forum.xda-developers.com/apps/magisk/module-systemless-beansgapps-mini-7-1-x-t3611362
