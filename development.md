---
layout: page
title: UWPX - /Dev
description: All topics related with the UWPX development.
sitemap:
    priority: 1.0
    lastmod: 2018-08-01
    changefreq: monthly
---
## How do I build UWPX

### Prerequisites
* [Visual Studio 2017](https://visualstudio.microsoft.com/downloads/) with all packages required for Windows C# and C++ UWP development
* [GitHub Extension for Visual Studio](https://visualstudio.github.com/) (recommend)

### Cloning
1. Once you have successfully install Visual Studio open it and select the `Team Explorer`. Then select `Clone` under `Local Git Repositories`.
    <br/>
    <img src="{{ "/images/development/0.jpg" | absolute_url }}" width="400rm" height="auto">

2. Now visit the UWPX GitHub repository and click on `Clone or download`. Then click the `copy` icon to copy the git repository url.
    <br/>
    <img src="{{ "/images/development/1.jpg" | absolute_url }}" width="200rm" height="auto">

3. Switch back to Visual Studio and paste the repository url into the appropriate textbox. Once done click on `Clone` and Visual Studio will clone the repository for you.
    <br/>
    <img src="{{ "/images/development/2.jpg" | absolute_url }}" width="200rm" height="auto">

### Starting the solution
1. Once Visual Studio finished cloning the repository, it will show you the `Solution Explorer`. There click on the UWPX solution (`UWPX_XMPP_Client.sln`) to open it.
    <br/>
    <img src="{{ "/images/development/3.jpg" | absolute_url }}" width="200rm" height="auto">

2. The last step is to build and run the solution. For this select your target architecture and click on the green arrow to run it.
    <br/>
    <img src="{{ "/images/development/4.jpg" | absolute_url }}" width="400rm" height="auto">