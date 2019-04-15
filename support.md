---
layout: page
title: UWPX - Need Help?
description: All support related topics for UWPX
sitemap:
    priority: 1.0
    lastmod: 2019-15-04
    changefreq: monthly
---
## Where do I get UWPX from and how do I install it?
There are three ways how you can get access to the app.

### 1. Microsoft Store:
The simplest way is to just download it via the [Microsoft Store](https://www.microsoft.com/store/apps/9NW16X9JB5WV).

[<img src="https://assets.windowsphone.com/85864462-9c82-451e-9355-a3d5f874397a/English_get-it-from-MS_InvariantCulture_Default.png" width="150">](https://www.microsoft.com/store/apps/9NW16X9JB5WV?ocid=badge)

### 2. Sideload:
If you don't want to use the [Microsoft Store](https://www.microsoft.com/store/apps/9NW16X9JB5WV) for getting access to UWPX you can also sideload a pre build app.  
For this head over to [releases](https://github.com/UWPX/UWPX-Client/releases) and download the latest `UWPX_UI_X.Y.Z.0.zip`.  
Once downloaded, unpack and right click `Add-AppDevPackage.ps1` -> `Execute with PowerShell` to install it.

**For this to work you first have to enable `Sideload app` in your Windows settings! Click [here](https://www.windowscentral.com/how-enable-windows-10-sideload-apps-outside-store) for more information about this.**

### 3. Build it by your own
#### Short version:
1. Install [Visual Studio 2017](https://www.visualstudio.com/de/downloads)
2. Clone the repo with Visual Studio 2017
3. Build the project for your target platform (e.g. `x64`)
4. Install the app on your target system:
[Here](https://docs.microsoft.com/en-us/windows/uwp/get-started/enable-your-device-for-development) you can find more information about: How to install UWP apps, using the developer mode.

#### Long version:
An extended guide on how to build UWP with images to guide you through can be found [here](https://uwpx.org/development/).

## What kind of account do I need?
Because XMPP is like email a federated protocol (=> there are no "__official__" XMPP accounts), everybody can host his own server providing XMPP accounts.

## Where can I get an account from?
Because XMPP is like email a federated protocol there are two ways of obtaining an XMPP (Jabber) account:
- There are [a bunch](https://list.jabber.at/) of providers which provide __free__ XMPP (Jabber) accounts. Like with your email provider make sure your XMPP provider is [**trustworthy**](https://xmpp.net/). Some Popular choices:
    - [jabber.de](https://www.jabber.de/anmeldung/)
    - [jabber.at](https://jabber.at/account/register/)
    - [jabber.ru](https://www.jabber.ru/register)
    - [404.city](https://404.city/#registration)
- You also can host your own [server](https://xmpp.org/software/servers.html).
- Some email providers also provide you with an XMPP account:
    - [mailbox.org](https://userforum.mailbox.org/knowledge-base/article/was-ist-jabber-xmpp)
    - [dismail](https://dismail.de/)
    - [mail.de](https://mail.de/hilfe/chat-jabber-einstellungen)

## Which devices are supported?
In theory **all UWP devices** that run an Windows 10 build >= `10.0.15063.0` are able to run UWPX.
But because I'm only able to test it on a Windows Phone and a Windows PC these are the only devices the official [Microsoft Store](https://www.microsoft.com/store/apps/9nw16x9jb5wv?ocid=badge) build will run on.

If there are additional devices you tested UWPX on that are able to run UWPX without any problems, let me know and I will add them to the list.
