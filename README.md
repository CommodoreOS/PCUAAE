# PCUAAE
PCUAE has just had a baby, its called PCUAAE - Project Carousel USB Amiga Anniversary Edition.

Project Carousel USB Amiga Anniversary Edition(PCUAAE) for THE A500 Mini. PCUAAE Autoboot Start-up Script v1.0.0. PCUAAE - Manhattan Skyline v1.0.0/1.1.0

This is for THE A500 Mini or THE A500 Maxi, Its early days yet, THEA500 Mini was released on the 8th April 2022 and not everyone has got there's yet but just wanted to put this out there that this it been made and will get better in time as we learn more about the machine.

And as mods get made for it, I will try and add them to it.

This will be like PCUAE and use some of it, I will port some of the stuff from it to this, I will not be porting the carousel from THEC64(PCUAE Mode), it was not made for this machine and it should stay on the machine it meant to be for, THE A500 Mini has its own carousel and I do not need to turn it into THEC64 and I want to try to respect Retro Games LTD who made these machines, I will probably port VICE Mode over, we will see.

Thanks for reading

Spannernick.

Pandory Mode added to The Mode Changer and with New Background Music and 50/60hz switch under Bash Playlist, this only works in PCUAAE if you run Pandory from USB Menu then it will load Pandory normal.

Pandory and PCUAAE in Action... https://youtu.be/lteh5z8EYc8

RA Mode has now been removed, no point having 2 Retroarch Modes and this makes less work for me, Team Pandory will keep it up to date so it will always work on the A500... :)

Pandory Download link ... https://github.com/emuchicken/pandory-a500/?fbclid=IwAR1pvE_1kYJXwSttG64coDvgdeyOiIUmXojErOfDvR6ij9soWvNO4oTnvM4

IMPORTANT
INSTALL PCUAAE AND ACTIVATE AUTOBOOT MODE BEFORE installing The NEW UPDATE FROM RGL v1.1.0 or 1.1.1, HOST RUN had been REMOVED from Amiberry now, HOST RUN Works IN PCUAAE only.
You WILL NOT be able to run PCUAAE if you have updated before installing PCUAAE Autoboot Mode.
You will now have to wait for another hack to come out that will allow you to run Linux code from within the carousel, like the Fake Update on PCUAE and THEC64.

How to install PCUAAE on the USB Stick
Make Sure the USB Stick uses Fat32 and Master Boot Record.
Install PCUAAE to USB Stick,
Run PCUAAE Startup LHA file in A500-Games Folder in the USB Menu.
Activate Autoboot Mode, it will ask you if you want to when you start PCUAAE from PCUAAE Startup LHA.
Once its finished activating Autoboot Mode, let it restart the machine, if it installed correctly it will reboot back into PCUAAE.
Turn off A500 and install Pandory to the root of the USB Stick.
Plug USB Stick back in A500 and turn it on and wait for PCUAAE to boot up.
start The Mode Changer, hold down Home button and X button together for 2 seconds or until screen goes black. when the menu comes up pick Pandory Mode and wait for it to load Pandory.
Your done... :) if you want to run another Mode just do the same but install and pick a different Mode, the modes are on Github too, download them from PCUAAE Release 1.0.7.
The Carousel Version Changer
You can change the carousel version from TheCarousel Manhattan v1.0.0 to v1.1.1 and back.
Press Home+Y or CTRL+F3 on a keyboard to load up The Carousel Changer.
Pick one of the carousels in the menu, TheCarousel Manhattan v1.0.0 or TheCarousel Manhattan v1.1.1 and it will load that version.
Host-Run support is on TheCarousel Manhattan v 1.0.0 and ADF support is on TheCarousel Manhattan v1.1.1.
and thats it for now, hope this helps.
The Mode Changer
You can change the Modes with Home+X buttons or on the keyboard CTRL+F5.
You need to install the Modes you want, just run the Mode Set Pack you want to install and install it to the root of the USB Stick.
You can download the Mode packs from PCUAAE v1.07... https://github.com/CommodoreOS/PCUAAE/releases/tag/PCUAAEv1.0.7.
You install the modes the same way as PCUAAE, install them to the USB Stick your using for PCUAAE and to the root of the USB Stick.
There was a error in the Autoboot Mode Setup PCUAAE Autoboot Mode First Boot Up it was making 2 Autoboot scripts in the firmware cause one line had a t missing on the end of its line, this is fixed now.

Rerun the setup using the PCUAAE_StartUp.LHA file but remove first the file on the root of the USB Stick called autoboot_fake_update_disabled otherwise it will skip it, it should refresh Autoboot Mode and remove the other script from the firmware if it's there, so there is only one then reboot PCUAAE.

or you could do a clean install but keep all the modes(WORKBENCH_Mode, LINUX_Mode, VICE_Mode and so on) and delete the PCUAE_Mode folder too, that way you do not need to install the Modes again, just reinstall PCUAAE again.

I made a mistake, in Workbench Mode I say press Menu button when I mean press Home Button so to get out of Workbench Mode press Home and pull out the Power cable for 2 seconds then plug it back in and The Mode Changer should come up then select PCUAAE Mode to get out of it.
Or you can use a keyboard, plug the keyboard in before turning on the A500 otherwise the keyboard will not work, then on the Workbench Screen press CTRL+F5 to load THE Mode Changer.

So to do things in PCUAAE you need to press Home Button and then the other button so like: Home+F5 for The Mode Changer and Home+F3 for The Carousel Version Changer but you can not do that in Workbench Mode cause Amiberry crashes when you press the Home button its better to use the keyboard.

