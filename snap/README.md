# Unofficial Snap Packaging for Bytecode Viewer

<!--
	Use the Staticaly service for easy access to in-repo pictures:
	https://www.staticaly.com/
-->
![(Placeholder) Icon of Bytecode Viewer](https://cdn.staticaly.com/gh/brlin-tw/snapcrafters-template-plus/bea3bc56/snap/gui/bytecode-viewer.png "(Placeholder) Icon of Bytecode Viewer")

**This is the unofficial snap for [Bytecode Viewer](https://bytecodeviewer.com/)**, *"An advanced yet user friendly Java Reverse Engineering suite"*. It works on Ubuntu, Fedora, Debian, and other major Linux distributions.

[![Build Status Badge of the `bytecode-viewer` Snap](https://snapcraft.io/bytecode-viewer/badge.svg "Build Status of the `bytecode-viewer` snap")](https://snapcraft.io/bytecode-viewer) [![Store trending badge](https://snapcraft.io/bytecode-viewer/trending.svg?name=0)](https://snapcraft.io/bytecode-viewer)

![Screenshot of the Snapped Application](local/screenshots/compare-view.png "Screenshot of the Snapped Application")

Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters

## Installation

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

### In a Terminal

    # Install the snap #
    sudo snap install --channel=beta bytecode-viewer
    #sudo snap install bytecode-viewer
    
    # Connect the snap to optional security confinement interfaces #
    ## Access files under /media, /mnt, and /run/media ##
    sudo snap connect bytecode-viewer:removable-media
    
    # Launch the application #
    bytecode-viewer
    snap run bytecode-viewer # If you have another existing installation

### The Graphical Way

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/bytecode-viewer)

<!-- Uncomment when you have test results
## What is Working
* [A list of functionallities that are verified working]

## What is NOT Working...yet 
Check out the [issue tracker](https://github.com/brlin-tw/bytecode-viewer-snap/issues) for known issues.
-->

## Support

* Report issues regarding using this snap to the issue tracker:  
  <https://github.com/brlin-tw/bytecode-viewer-snap/issues>
* You may also post on the Snapcraft Forum, under the `snap` topic category:  
  <https://forum.snapcraft.io/c/snap>
