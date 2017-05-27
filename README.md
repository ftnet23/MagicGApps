## MagicGApps

	You may be asking yourself, "But... why?" 
	Well, this systemless implementation of GApps makes it very easy to customize and update the included Google setup. 
	For instance, ever seen that feature in Titanium Backup, "Integrate system app updates into /system?" Exactly. Now you can do that without writing to the system partition and then repack the module with the updated changes if you are into doing this sort of thing. 
	In addition to that, you can add/replace/remove things from the package to suit your needs the easiest and fastest way possible (you will see some of these cool tweaks below). One more advantage: your ROM updates will be slightly faster, since GApps don't have to be backed up and restored afterwards every time you flash a new version of your ROM (i.e., LineageOS adon.d backup feature). AND my favorite, you can make regular backups of your magisk.img file to simplify future ROM setups even further!

Core Google syncing APKs (Google Play Services, SetupWizard, Google Play Store)

Core Google libs (`Facelock,` TTS)

Google App

`Legacy support for swyping on AOSP LatinIME Keyboard`
***
**[Removed]** LatinIME libs and Facelock (proper systemless implementation of those is a work in progress. I need help with lib symbolic linking)

**[Patch]** Google Play Services removed from Doze Witelist to save battery by @otonieru

**[Added]** Nova Launcher
	
	
*If you find Google Play Services or any other app force closing after installation, just ignore it. Everything will normalize as you set up Android. A reboot afterwards is recommended.*


Thread: https://forum.xda-developers.com/apps/magisk/module-systemless-beansgapps-mini-7-1-x-t3611362

Credits:
	@The Flash, @BeansTown106, @Surge1223, @BaNkS & others
