---
title: "Creating Wii Game Shortcuts"
---

{% include toc title="Table of Contents" %}

If you need help for anything regarding this tutorial, please join [the RiiConnect24 Discord server](https://discord.gg/rc24) (recommended) or [e-mail us at support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

Do you use a USB Loader and want to create game shortcuts to launch them on your Wii Menu? Then try WiiGSC (Wii Game Shortcut Creator), previously known as Crap.

In the case of a brick, [installing Priiloader is a must](priiloader). Also, install BootMii (as Boot2 if you have an early Wii). Installing brick protection along with following the guide correctly should keep you safe from bricks. DO NOT CONTINUE UNTIL YOU HAVE INSTALLED PRIILOADER AND BOOTMII!
{: .notice--warning}

Do NOT make a shortcut for the games "Mario Party 9" or "A Boy and His Blob". It will brick your Wii.
{: .notice--danger}

#### What you need

* A Wii
* A USB drive or SD card
* A WAD Manager ([yawmME](yawmme) is recommended)
* A computer running Windows
* [WiiGSC](https://wiidatabase.de/downloads/pc-tools/wiigsc-ehemals-crap/)

#### Instructions

1. Install WiiGSC, then right click on it and choose **Run as administrator**. If you do not do this, WiiGSC will throw an error when you open it.
1. Select the path to the ISO or WBFS file on your USB drive or SD card, and select the USB Loader you use. The other options should be fine the way thy are.
1. Copy the generated `.wad` file to a folder named `WAD` on your SD card.
1. Install the generated WAD with a WAD Manager. We recommend YAWM ModMii Edition.

If you get an error saying "The system files are corrupted", don't panic as long as you installed Priiloader. <br>
Turn off your Wii, then hold down the RESET button down and turn on your Wii. <br>
You should be able to boot into the Priiloader menu, where you have the option to launch the Homebrew Channel. <br>
Simply launch YAWM ModMii Edition and uninstall the WAD.
{: .notice--warning}
