# accountswitcher
Switch between your PSN accounts on your Vita

#Usage:
##Adding accounts:
###Current Account:
Open the app, and dump your current profile (second option)

###Other Account:
* First unslave SD card (third option, this will allow you to keep your SD intact)
* Restore the device (Format->Restore This System)
* When asked if you want to deactivate, choose "No"
* When asked if you want to format the card, choose "No"
* Log in with your new credentials
* Activate the Vita
  * Since 3.61 you can't do that directly, you have to do one of the following:
    * ~~use [vita-activator](https://github.com/ZombieWizzard/vita-activator)~~
    * ~~use the Activate option I included in AccountSwitcher~~
    * From Henkaku Release 3 onwards, PSN spoofing is included. Activate the device normally from Settings or just by downloading anything from store
* Open the app and dump your new profile (second option)

##Loading an account:
* Select "Load Account"
* Choose a profile
* Reboot system

##Backup folder
* Profiles are stored on __ux0:/data/AccountSwitcher__

#ToDo
~~* Trial account support~~

#Credits:
* vitasdk and henkaku devs for making this possible
* [xerpi](https://github.com/xerpi) for vita2dlib
* [kprinssu](https://github.com/kprinssu) for vitamenulib
* [ZombieWizzard](https://github.com/ZombieWizzard) for vita-activate

