# UMD Launcher
<img src="https://github.com/Nathanael321/umd-launcher/blob/master/icon_128.png?raw=true">


## Description

This repository contains the program for a Google extension that serves to assist University of Maryland students in accessing websites that a typical student would visit daily. This program utilizes two languages:
- HTML to insert the text and links
- CSS to design the icons, font, and page

###
The different files that make up all the code for this project are listed below:
- manifest.json
- popup.html

## Download

In order to download this Google extension, click the following link: https://chrome.google.com/webstore/detail/umd-launcher/kmimehnhdhjfanicgiikhnopeaepflba

## manifest.json

This file contains the name, description, version, and icons that this will be displayed in the Chrome web store. This also specifies the browser action.

## popup.html

Uses both HTML and CSS to develop the main functioning of the extension. HTML is used to create the inital webpage and import images. These images are then 
set to links to make them now serve as icons that the user can  different webpages.

In order to give this newly created webpage a more appealing look, CSS is then used to change the font, color, alignment of the icons, etc.

This file also specifies a URL of an external file, popup.js, which isn't displayed in the repository as that file is currently empty. This is because this extension doesn't need to use JavaScript, but if it did, it would be in the popup.js file.
