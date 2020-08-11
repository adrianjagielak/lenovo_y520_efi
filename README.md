My Personal Hackintosh EFI for Lenovo Legion Y520
=============
# Do not use this EFI, it can make your laptop explode
=============

This is my personal clover efi for my current hackintosh (one drive, dual-boot macOS Catalina and Windows 10). If you have any questions you can always open an issue :)

What works:
- Almost everything (including Intel's wifi card)

Not working:
- Nvidia GTX1060 with all its video ports (HDMI and mini DisplayPort) and for some reason video output even in usb-c dock (and im sure its doabe but some patches are not correct etc, if you have any idea how to fix it any help would be great :) )

### Backstory:
Im making this EFI public after recent situation when I accidentally broke my laptop white traveling (windows update broke clover efi) and my recovery pendrive efi was in home. It was really frustrating hour of repairing using someones pc and pendrive (making bootable Hiren's BootCD PE USB, then erasing main efi to be windows efi, then booting windows, then downloading efi from my GitHub (I use password manager so I couldn't download it on my friends pc) and then finally copying this efi to main efi partition while copying newly created windows efi to separate windows efi partition :P )

Don't use it as it is, it will not work on your machines
