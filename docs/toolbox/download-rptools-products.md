---
layout: page
title: Download
permalink: /toolbox/download-rptools-products/
---

To download either MapTool or TokenTool, click on the buttons provided below that will take you to the download page for the latest stable version. (When you get there, read the notes at the top and then expand the Assets dropdown to see the list of items.)  All the downloads are installation executables that install the products on your computer and come packaged with a version of Java that works with the program.

<u>Follow the guidelines below and read through our FAQ at the bottom of the page.</u>

***

<section markdown="1">
## TokenTool 2.2.2

### Windows

Use either .MSI (recommended) or .EXE.

If you have added custom overlays, they should still be accessible when installing this version over previous versions.

We’re seeing notes from Windows users that they double-click the icon after installing and no window appears. This seems to be an antivirus issue, so check your AV if you have this problem.  See the download page for more information.

[TokenTool 2.2.2](https://github.com/RPTools/TokenTool/releases/tag/2.2.2) _(released Sat, 30 Mar 2024 12:25:11 GMT)_

### Mac

Use either .PKG (recommended) or .DMG.

Apple won’t recognize the application as being from an “identified developer”. You will have to allow it to open through System Preferences  > Security & Privacy, and even then some Ctrl-click fanciness is required.  See the download page for more information.

The macOS Gatekeeper may flag the DMG file as broken. The DMG isn’t actually broken, but GateKeeper doesn’t like that it’s not signed.  See the download page for more information.

[TokenTool 2.2.2](https://github.com/RPTools/TokenTool/releases/tag/2.2.2) _(released Sat, 30 Mar 2024 12:25:11 GMT)_

### Linux

Use either .deb or .rpm (depending on which packager your system uses). 

The deb version installs under /opt/tokentool/bin as TokenTool.

It seems that some Linux distributions ship a native library that can’t handle some of the provided overlays.  See the download page for more information.

[TokenTool 2.2.2](https://github.com/RPTools/TokenTool/releases/tag/2.2.2) _(released Sat, 30 Mar 2024 12:25:11 GMT)_

</section>

***

<section markdown="1">
## MapTool 1.18.6

### Windows

Windows users are encouraged to use the MSI.

Since RPTools is not a “known software publisher” by Microsoft, you will need to click through the prompts to install MapTool and when starting MapTool for the first time you will prompted to allow network access.  See the download page for more information.

[MapTool 1.18.6](https://github.com/RPTools/maptool/releases/tag/1.18.6) _(released Thu, 30 Oct 2025 16:51:10 GMT)_

### Mac

Mac Users are encouraged to use the PKG version of the install.

Apple won’t recognize the application as being from an “identified developer”. You will have to allow it to open through System Preferences  > Security & Privacy, and even then some Ctrl-click fanciness is required.  See the download page for more information.

[MapTool 1.18.6](https://github.com/RPTools/maptool/releases/tag/1.18.6) _(released Thu, 30 Oct 2025 16:51:10 GMT)_

### Linux

Use either .deb or .rpm (depending on which packager your system uses).

The deb version installs under /opt/maptool/bin as MapTool.  See the download page for more information.

[MapTool 1.18.6](https://github.com/RPTools/maptool/releases/tag/1.18.6) _(released Thu, 30 Oct 2025 16:51:10 GMT)_

</section>

***

<section markdown="1">
## FAQ
### Which version to download?

All of the tools by the RPTools Team follow a consistent versioning scheme. There is always a stable (also known as release) version available that can be used by those that have concerns as to the stability of a development version.

That said, it is frequently the case that a late development build is effectively as stable as a release version. It is a good idea to ask around on the forum or on Discord to determine which is the best build for you.

If you're looking for the latest nightly build, or a beta release, or other specific type of download, visit the [GitHub wiki page for MapTool](https://github.com/RPTools/maptool/wiki/Finding-the-MapTool-release-you're-looking-for...).

### What can you tell me about the versions that are in development?

Development versions are where all of the glitz and new features are added. Because of the constant additions that occur in this version of the code, external file formats are likely to change, functionality may be introduced in one build only to be removed in the next build, and there can be usability issues as well. Anything major is normally corrected in a very short time but this can lead to head-scratching and a loss of sleep for those who like to live on the edge.

### Will I be helping the community by using the latest version?

Yes. You would help the community more by using the latest and greatest and report back any issues to the community through our forum, blog or discord. Still, nothing’s worse than a game night ruined by a crashing program. Ideally, you can recruit your players to test the new versions but use the stable versions for when it counts.

### Do I need to do anything before I update?

If you are only going to keep one version of MapTool installed, it is highly recommended that you uninstall the previous version and delete any files or directories left behind in the install location before installing the new version.

Best practice is to keep your resource libraries, campaign files and other user content in a separate location.  If you have stored those files in your MapTool installation folder, ensure they are backed up or moved before uninstalling and installing the new version.

### The downloaded installer won't run or the installation hangs, now what?

If the installer won't run, make sure you have sufficient permissions on your computer to install software, and that you have granted the installer the required permissions. 

Antivirus checks should be suspended during installation.

Installation of MT can take several minutes, especially if you use the Windows .exe file format for installation.

Some users may find it necessary to uninstall all previous versions of MT and reboot before installation.

If you are still unable to get your installer to run, please ask in general_support on our Discord channel.

### Is there a JAR file available?

A JAR file version may be downloaded as well but is only recommended for developers or other advanced users. For most users, we suggest the executable version which will install the Tools as an application you execute like any other.

The latest version of MapTool requires JavaFX and Java 16. If you have sufficient development background, you may be able to puzzle this out, but we are only supporting our packaged builds at this time.

You can find the download on our Github page.

### Where can I find older versions

All our versions can be found on this page:

<https://github.com/RPTools/maptool/releases>

</section>

{% include md-links.md %}
