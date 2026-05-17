# Dell-Optiplex-3040-SFF-Hackintosh-EFI

Okay this might be an L for me, but I kinda guided myself using Opencore-Simplify. Because high-key I hvae some skill issue with the Dortania Guide, this might be selfish to say to me but lowkey, the Dortania guide didn't need to put allat extra effort in the post install of the cosmetic guide, like how genuinely tryna make hackintosh as 1:1 as a genuine Mac/Macbook, like at that point just go buy a real one lol.

Also I've spent countless reading and trying to force my brain to understand every single piece of letter in the damn guide, that shit genuinely fried my brain, but afterall, a Hackintosh is more of a hobby instead of a serious stuff, It's like installing Arch Linux but the RTFM has a cleaner and friendlier interface and everything, compare to Arch RFTM where it just bashest every single information out of you.

This Dell Optiplex has the following specs (iirc):

CPU: i5-6500T (6th-generation)
GPU: Intel HD530 (Skylake)
Motherboard: Ion, search that shit up yourself, Google exist for a reason.
Storage: 128GB SATA San-Disk
Touchpad/Touch Device: N/A (Obviously no lol)
BIOS: Ion know, some old ass 2014 BIOS that i haven't updated
Wifi: Some Intel card
Ethernert: Realtek Gb/PCIe Family controller or sum.
RAM: 4GB DDR3L (When I have the money, am gonna upgrade it to 8GB. It probably burning the SSD with Swaps lmao)

What works:
QI/CE (Graphic/Hardware Acceleration)
iService? (haven't tested YET)
Wifi (Gonna fix it after I finish writting this)
Bluetooth (Same with Wifi)

What doesn't work
Airdrop
Sleep
iPhone Mirroring
Screen Saver thingy (My Screen flickers so hard so i'll consider it not working)
Dynamic Wallpaper or Moving Wallpaper from login (same reason as Screen Saver)

Last Note: 

If I have the time and money, there are few things I really want to fix in order to call this a "perfect" Hackintosh, first is the definetly the RAM upgrade, because I think this is the main bottleneck of the Hackintosh, am not gonna last long with a burn SSD that keeps paging files every second because of the RAM shit. And another thing is that I really want to make Dynamic Wallpaper and Screen Saver to work, everytime I put it in that state. My HDMI screen flickers like crazy, and mind you am using a generic SAMSUNG Monitor with a 75hz and 1920x1080 16:9, so I think it just mainly HD530 fault, either it's the iGPU or I did something wrong with my config.plist that I fucked up the framebuffer or fucked up spoofing the Skylake iGPU to Kabylake iGPU.

with nothing else to put, Imma drop the EFI just incase in the future I'll need it.
