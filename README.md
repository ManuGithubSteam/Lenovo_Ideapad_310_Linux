# Lenovo_Ideapad_310_Linux
Tipps and expiriences with the Lenovo Ideapad 310 with Linux, specially with Ubuntu. But it shoudl work with Linux mint and others too.

# Why

(2017) The Lenovo Ideapad 310 is a reasonable good machine from Lenovo and it is available in may configurations, from mid to upper range gaming (https://www.youtube.com/watch?v=AKwqNbup6qE) with Nvidia over mutlimedia with dvd player to office configurations. On youtube there are many tutorials on how to upgrade the 310 and it is well reciefed by review portals (75% - 85% in the Ratings)

So it has many usecases and is well estblished in the Windows world. However as I researched I could not find a good howto for Linux in this laptop series from Lenovo. So I'm writing my own one. As i will fit this machine for a friend who is a beginner in Linux i will also focus on makeing the Linux expirinence smooth as possible for new Linux users.

# Youtube Reviews and Stuff
https://www.youtube.com/results?search_query=Lenovo+ideapad+310-15ikp+80TV00XXIH

# Hardware

As my friend will use the Laptop mostly for multimedia, i did choose a configuration with a dvd plaxer.
Specificly i choose this one: https://www.amazon.de/Lenovo-ideapad-Notebook-i5-7200U-DVD-Brenner/dp/B01MTY2HTD/ref=sr_1_1?s=computers&ie=UTF8&qid=1492260062&sr=1-1&keywords=Lenovo+ideapad+310+ssd+dvd

Lenovo ideapad 310 80TV00RLGE

Main Specs:
- i5 Processor 3.1 Ghz (2 cores)
- 8GB RAM
- 512 GB SSD
- SD Card reader
- Wlan and Bluethooth
- Full HD Resoltution 1920x1080
- DVD player
- 1x USB 3.0 
- 2x USB 2.0
- HDMI and VGA
- Audio Headphonejack
- LAN
- Around 4 hours of Battery life when watching movies.
- Intel HD 620

# (Anticipated) Problems:

As I researched this laptop it became apparent, that there are not many posts about in in the Linux world.
This could mean that, not many problems are to be expected wich would be a good thing. 

However as only the Lenovo T and X series are shipped to RedHat and other big companies it does mean other model series do not neccarrily work as good with Linux.

The List of expected Problems:
- Secure Boot
- TPM
- Sound Issue (found on the Net )
- Wlan connection issues ( Found on the Net )
- UEFI ?
- RAID Controler (This seems to be the same issue as with the Yoga series, disableing RAID sould help...)

# Software

I will use the newest Kubuntu 17.04 for this Laptop. The reasion beeing, Ubuntu is still top notch in term of drivers for newer Hardware and of course do these changes tickle into other Distros and i certainly could get them to work but my reasoing is, that my friend should be able to update the system by iself and don't worry about manually installed drivers and config hacks.

KDE is the obvious choice as it is more intuitive for an ex-Windows user as for instead say Gnome. I won't go into Unity. Reason are all over the Internet. 

Also Plasma 5 from KDE offers some cool feature to make the workflow more powerfull and easy at the same time. Another cool feature is KDE Connect for your Android phone.

However i will not use snap! This is not needed and advised for normal user, as it tends to bloat the system for no reason. 

-> http://www.kubuntu.org/

# Install

Using an USB Stick with dd :-)

Something like this:

dd if=/kubuntu.iso of=/dev/sd? bs=4M && sync

Don't forget the sync.

**Bios**

**Booting Live System**

**Partitioning**

I will not use btfs but instead ext4 with some slight modifications for ssds. The reason is, that btfs can show you have no space left on the device because it runs out of inodes to adress the space but actually you have space left. Fixing this not not trivial so i want to avoid any obstickles in the future with this. 


**Install**

**Cleaning up**

# First Boot

**Maintanance**

# Conclusion




#Tags:

Linux, Ubuntu, Lenovo 310, Ideadpad 310, 
