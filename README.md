# Jamulus Accessible Build
This is a modified version of [corrados/jamulus.](https://github.com/corrados/jamulus)

## Download 
Build Released on 10/18/2020.

* [Mac](https://github.com/chigkim/jamulus/releases/download/alpha.7/Jamulus-Accessible-Mac.zip)
* [Windows](https://github.com/chigkim/jamulus/releases/download/alpha.7/Jamulus-Accessible-Win.zip)

Mac Users, this is an unsigned app. If right clicking and choosing open doesn't work, you might need to [dequarantine the app.](https://derflounder.wordpress.com/2012/11/20/clearing-the-quarantine-extended-attribute-from-downloaded-applications/)

## Changelogs
* Changes from [corrados/jamulus.](https://github.com/corrados/jamulus/commits/master)
* Added alias and instrument to mute, solo, group buttons.
* Fixed bug to play sound when changing profile
* Crash when changing genre rapidly
* Cleanup connect/disconnect button
* User info
* Currently connected server name
* Sound alert when someone joins/leaves
* Sound alert for new message
* Delay indicator
* Buffer indicator
* Pan value
* Server List

## Original README

![Homepage picture](src/res/homepage/jamulusbannersmall.png)

[![Build Status](https://travis-ci.org/corrados/jamulus.svg?branch=master)](https://travis-ci.org/corrados/jamulus)

Jamulus - Internet Jam Session Software
=======================================
<img align="left" src="src/res/homepage/mediawikisidebarlogo.png"/>

The Jamulus software enables musicians to perform real-time jam sessions over the internet.
There is one server running the Jamulus server software which collects the audio data from
each Jamulus client, mixes the audio data and sends the mix back to each client.

Jamulus is __Open Source software__ ([GPL, GNU General Public License](http://www.gnu.org/licenses/gpl-2.0.html))
and runs under __Windows__ ([ASIO](http://www.steinberg.net)),
__MacOS__ ([Core Audio](https://developer.apple.com/documentation/coreaudio)) and
__Linux__ ([Jack](http://jackaudio.org)).
It is based on the [Qt framework](https://www.qt.io) and uses the [OPUS](http://www.opus-codec.org) audio codec.

The project is hosted at [Sourceforge.net](http://sourceforge.net/projects/llcon).
![Sourceforge logo](http://sflogo.sourceforge.net/sflogo.php?group_id=158367&amp;type=5)


Required Hardware Setup
-----------------------

The required minimum internet connection speed is 200 kbps (0.2Mbps) for the up and down-stream.
The ping time (i.e. round trip delay) from your computer to the server should not exceed 40 ms average.

For the Jamulus software to run stable it is recommended to use a PC with at least 1.5 GHz CPU frequency.

On a Windows operating system it is recommended to use a sound card with a native ASIO driver.
This ensures to get the lowest possible latencies.


Download and Installation
-------------------------

Download the latest version for [Windows, Macintosh or Linux here](https://sourceforge.net/projects/llcon/files/). 

**Windows users**: The Jamulus client software requires an ASIO sound card driver to be available in the system.
If your sound card does not have native ASIO support, you can try out [this alternative](http://www.asio4all.org/)


Help
----

Official documentation for Jamulus is on the [Github wiki](https://github.com/corrados/jamulus/wiki)

See also the [discussion forums](https://sourceforge.net/p/llcon/discussion)

Bugs and feature requests can be [reported here](https://github.com/corrados/jamulus/issues)


Compilation and Development
---------------------------

See the [compile Instructions](INSTALL.md) 

For setting up and running a server, see [this guide](https://github.com/corrados/jamulus/wiki/Running-a-Server)


Acknowledgments
---------------

This code contains open source code from different sources. The developer(s) want
to thank the developer of this code for making their efforts available under open
source:

- Qt cross-platform application framework: http://www.qt.io

- Opus Interactive Audio Codec: http://www.opus-codec.org

- Audio reverberation code: by Perry R. Cook and Gary P. Scavone, 1995 - 2004
  (taken from "The Synthesis ToolKit in C++ (STK)"):
  http://ccrma.stanford.edu/software/stk
  
- Some pixmaps are from the Open Clip Art Library (OCAL): http://openclipart.org

- Country flag icons from Mark James: http://www.famfamfam.com

We would also like to acknowledge the contributors listed in the
[Github Contributors list](https://github.com/corrados/jamulus/graphs/contributors).
