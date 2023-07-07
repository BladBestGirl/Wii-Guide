---
title: "Updating Wii Menu to v4.3"
---

{% include toc title="Table of Contents" %}

If you need help for anything regarding this tutorial, please join [the RiiConnect24 Discord server](https://discord.gg/rc24) (recommended) or [e-mail us at support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

This tutorial will explain how to update your Wii Menu to version 4.3, if you have already homebrewed your Wii.

It is safer and easier to use [ModMii](https://modmii.github.io) (Windows only) to update your Wii to 4.3.
{: .notice--warning}

#### What you need

* An SD card or USB drive
* A computer running Windows
* [NUS Downloader](https://github.com/WiiDatabase/nusdownloader/releases/latest)
* [YAWM ModMii Edition](https://oscwii.org/library/app/yawmme)

If you don't have a Windows computer, please join [the RiiConnect24 Discord server](https://discord.gg/rc24) (recommended) or [e-mail us at support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

#### Instructions

##### Section I - Downloading

Your Wii must be modded in order to perform this. If it isn't, then it's best to follow [the guide](get-started) first before doing this.
{: .notice--info}

It is recommended to [make a NAND backup](bootmii) before and after performing this update.
{: .notice--warning}

You must [install Priiloader](priiloader) before proceeding with this guide.
{: .notice--danger}

1. Extract the .zip file for NUS Downloader Wii and open the application.
1. Go to `Database...` > `System` > `0000000100000002 - System Menu` and select the version corresponding to your region as shown in the table below.
1. Make sure `Pack WAD` is checked.
1. Press `Start NUS Download!`.
1. Open the `titles` -> `0000000100000002` -> (Wii Menu version) and copy the .wad file to a folder called `wad` on your SD Card or USB drive.
1. Repeat steps 2-5 with `IOS` -> `000000010000003A` -> `Latest Version`.
1. Repeat steps 2-5 with `IOS` -> `0000000100000050 - IOS80` -> `Latest Version`.

| Region | Wii Menu version                                                               |
| ------ | ---------------------------------------- |
| Japan  | v512 (4.3J) |
| USA    | v513 (4.3U) |
| Europe | v514 (4.3E) |
| Korea  | v518 (4.3K) |

##### Section II - Installing

1. Put your SD card or USB drive in your Wii.
1. Launch the Homebrew Channel on your Wii.
1. Launch YAWM ModMii Edition.
1. Select the source device corresponding to whether you are using an SD card or USB drive.
1. The `wad` folder should open automatically. If not, navigate to it and open it.
1. Navigate to the the IOS80 `.wad` file, and press A twice to install it. [`Make sure the installation is successful, otherwise abort.`]
1. Navigate to the the WiiSystemMenu `.wad` file, and press A twice to install it. [`Make sure the installation is successful, otherwise abort.`]
1. Navigate to the the IOS58 `.wad` file, and press A twice to install it.
1. After they are successfully installed, press the HOME Button to exit back to the Homebrew Channel.

If you have an SD card, [continue to making a NAND Backup using BootMii](bootmii).<br>
Making a NAND backup with BootMii at this point is highly recommended.
{: .notice--info}
