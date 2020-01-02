---
layout: page
title: UWPX - /Dev
description: All topics related with the UWPX development.
sitemap:
    priority: 1.0
    lastmod: 02-01-2020
    changefreq: monthly
---
## How do I build UWPX

### Prerequisites
* [Visual Studio 2019](https://visualstudio.microsoft.com/downloads/) with all packages required for Windows C# and C++ UWP development.
* [GitHub Extension for Visual Studio](https://visualstudio.github.com/) (recommend)

### Cloning
1. Once you have successfully install Visual Studio 2019 open it and select the `Clone or check out code`.
    <br/>
    <img src="{{ "/images/VS2019_1.png" | absolute_url }}" width="400rm" height="auto">

2. Now visit the [UWPX GitHub repository](https://github.com/UWPX/UWPX-Client) and click on `Clone or download`. Then click the `copy` icon to copy the git repository url.
    <br/>
    <img src="{{ "/images/development/VS2019_2.png" | absolute_url }}" width="200rm" height="auto">

3. Switch back to Visual Studio and paste the repository url into the appropriate textbox. Once done click on `Clone` and Visual Studio will clone the repository for you.
    <br/>
    <img src="{{ "/images/development/VS2019_3.jpg" | absolute_url }}" width="200rm" height="auto">

### Starting the solution
1. Once Visual Studio finished cloning, it will show you the `Solution Explorer`. There click on `Switch Views` to switch from the folder view to the project view.
    <br/>
    <img src="{{ "/images/development/VS2019_4.jpg" | absolute_url }}" width="200rm" height="auto">

2. This should open a new dialog where you can select the solution you want to switch to. Click on the UWPX solution (`UWPX-Client.sln`) to open it.
    <br/>
    <img src="{{ "/images/development/VS2019_5.jpg" | absolute_url }}" width="200rm" height="auto">

3. The last step is to build and run the solution. For this select your target architecture and click on the green arrow to run it.
    <br/>
    <img src="{{ "/images/development/VS2019_6.jpg" | absolute_url }}" width="400rm" height="auto">
    <br/>
    <img src="{{ "/images/development/VS2019_7.jpg" | absolute_url }}" width="400rm" height="auto">