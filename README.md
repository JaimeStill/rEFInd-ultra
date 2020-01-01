## Ultra rEFInd theme

[rEFInd](http://www.rodsbooks.com/refind/) is an easy to use boot manager for UEFI
based systems. This is a clean and minimal theme with ultrawide monitors in mind.

![rEFInd Ultra](https://i.imgur.com/AvNgL46.png)

### Usage

 1. Locate your refind EFI directory. This is commonly `/boot/EFI/refind`
    though it will depend on where you mount your ESP and where rEFInd is
    installed. `fdisk -l` and `mount` may help.

 2. Create a folder called `themes` inside it, if it doesn't already exist

 3. Clone this repository into the `themes` directory.

 4. To enable the theme add `include themes/rEFInd-ultra/theme.conf` at the end of
    `refind.conf`.

Entries that are autodetected should show the proper icons.

### Attribution

This is modified from a fork of Evan Purkhiser's [rEFInd Minimal](https://github.com/EvanPurkhiser/rEFInd-minimal) theme.

The OS icons are from [Lightness for burg][icons] by [SWOriginal][icon-author].

> I have not had any luck finding attribution for the background image. If it is known, I'll gladly update here. Was found on an Imgur wallpaper dump.


[icons]: http://sworiginal.deviantart.com/art/Lightness-for-burg-181461810
[icon-author]: http://sworiginal.deviantart.com/