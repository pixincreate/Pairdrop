# Pairdrop

Android app for [Pairdrop.net](https://pairdrop.net) - Local file sharing in your browser. Inspired by Apple's Airdrop.

This app is a wrapper around [pairdrop project](https://github.com/schlagmichdoch/pairdrop) using webview and some javascript interface for downloads.

Install from **[APK release](https://github.com/pixincreate/Pairdrop/releases)**.

## Features

[PairDrop](https://pairdrop.net) is a sublime alternative to AirDrop that works on all platforms.

Send images, documents or text via peer to peer connection to devices in the same local network/Wi-Fi or to paired devices.
As it is web based, it runs on all devices.

You want to quickly send a file from your phone to your laptop?  
You want to share photos in original quality with friends that use a mixture of Android and iOS?  
You want to share private files peer to peer between Linux systems?  
AirDrop is unreliable again?

_Send it with PairDrop!_

Developed based on [Snapdrop](https://github.com/RobinLinus/snapdrop)

## Differences between Snapdrop and Pairdrop

### Device Pairing

* Pair devices via 6-digit code or QR-Code
* Pair devices outside your local network or in complex network environment (public Wi-Fi, company network, Apple Private Relay, VPN etc.).
* Connect to devices on your mobile hotspot.
* Paired devices will always find each other via shared secrets even after reopening the browser or the Progressive Web App
* You will always discover devices on your local network. Paired devices are shown additionally.
* Paired devices outside your local network that are behind a NAT are connected automatically via [Open Relay: Free WebRTC TURN Server](https://www.metered.ca/tools/openrelay/)

### [Improved UI for sending/receiving files](https://github.com/RobinLinus/snapdrop/issues/560)

* Files are transferred only after a request is accepted first. On transfer completion they are downloaded automatically if possible.
* Multiple files are downloaded as ZIP file
* On iOS and Android the devices share menu is opened instead of downloading the files
* Multiple files are transferred at once with an overall progress indicator

### Send Files or Text Directly From Share Menu, Context Menu or CLI

* [Send files directly from context menu on Windows](/docs/how-to.md#send-files-directly-from-context-menu-on-windows)
* [Send directly from share menu on iOS](/docs/how-to.md#send-directly-from-share-menu-on-ios)
* [Send directly from share menu on Android](/docs/how-to.md#send-directly-from-share-menu-on-android)
* [Send directly via command-line interface](/docs/how-to.md#send-directly-via-command-line-interface)

### Other changes

* [Paste Mode](https://github.com/RobinLinus/snapdrop/pull/534)
* [Prevent devices from sleeping on file transfer](https://github.com/RobinLinus/snapdrop/pull/413)
* Warn user before PairDrop is closed on file transfer  
* Open PairDrop on multiple tabs simultaneously (Thanks [@willstott101](https://github.com/willstott101))
* [Video and Audio preview](https://github.com/RobinLinus/snapdrop/pull/455) (Thanks [@victorwads](https://github.com/victorwads))
* Node-only implementation (Thanks [@Bellisario](https://github.com/Bellisario))
* Automatic restart on error (Thanks [@KaKi87](https://github.com/KaKi87))
* Lots of stability fixes (Thanks [@MWY001](https://github.com/MWY001) [@skiby7](https://github.com/skiby7) and [@willstott101](https://github.com/willstott101))
* To host PairDrop on your local network (e.g. on Raspberry Pi): [All peers connected with private IPs are discoverable by each other](https://github.com/RobinLinus/snapdrop/pull/558)

## Advantages of using Pairdrop as an app

* You can select files on your phone share it directly using this app, instead of opening a browser and searching for the files
* I'm also planning to add a download/upload history section once the following issues are fixed

### Known issues

* It changes the downloaded file name.
* Might not support downloading some file types. (Please create an issue, mention the file type and attach the file too, if possible.)

### Credits

[Snapdrop](https://github.com/robinlinus/snapdrop/) by [Robin Linus](https://twitter.com/robin_linus)

[Snapdrop app](https://github.com/tanujnotes/Snapdrop) by [Tanuj](https://twitter.com/tanujnotes)

See more from Tanuj [**_here_**](https://play.google.com/store/apps/dev?id=7198807840081074933)

[Pairdrop](https://github.com/schlagmichdoch/Pairdrop) by [Schlagmichdoch](https://github.com/schlagmichdoch)
