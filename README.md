[![](https://img.shields.io/github/v/release/Ich73/DQM2-FanTranslation?include_prereleases&label=Release)](https://github.com/Ich73/DQM2-FanTranslation/releases/latest)
[![](https://img.shields.io/github/downloads/Ich73/DQM2-FanTranslation/total?label=Downloads)](https://github.com/Ich73/DQM2-FanTranslation/releases)
# DQM2 Fan Translation
This repository is a place to develop fan translations for _Dragon Quest Monsters 2: Cobi and Tara's Marvelous Mysterious Key_ for several different languages. It contains only `.xdelta`, `.patJ` and `.patE` patch files so no copyrighted material is shared.  

## Structure
The folder structure in this repository is based on the structure of extracted `.cia` or `.3ds` files.  
Most foldernames consist of the basename of the folder and the locale of the translation, e.g. `Message_EN` contains the messages for the english language. Folders without a locale extension are used for every language except for the original language japanese.  
  
The content of the folders is as follows:
  * `Banner` contains the logo that is shown on the top screen in the 3DS home menu (see [Editing the Banner](https://github.com/Ich73/DQM2-FanTranslation/wiki/Editing-the-Banner))
  * `ExeFS` contains the code of the game (see [Editing the Code](https://github.com/Ich73/DQM2-FanTranslation/wiki/Editing-the-Code) and [Code Modifications](https://github.com/Ich73/DQM2-FanTranslation/wiki/Code-Modifications))
  * `Event` contains `.e` files storing the cutscene and dialog texts (see [Editing .e Files](https://github.com/Ich73/DQM2-FanTranslation/wiki/Editing-.e-Files) and [Event Files](https://github.com/Ich73/DQM2-FanTranslation/wiki/Event-Files))
  * `Font` contains the `.bcfnt` fonts that are used in game (see [Editing .bcfnt Files](https://github.com/Ich73/DQM2-FanTranslation/wiki/Editing-.bcfnt-Files))
  * `Layout` contains `.arc` archives storing `.bclim` images for icons, pictures, frames, etc. (see [Editing .arc Files](https://github.com/Ich73/DQM2-FanTranslation/wiki/Editing-.arc-Files))
  * `Message` contains `.binJ` files storing texts (see [Editing .binJ Files](https://github.com/Ich73/DQM2-FanTranslation/wiki/Editing-.binJ-Files) and [Message Files](https://github.com/Ich73/DQM2-FanTranslation/wiki/Message-Files))
  * `NaviMap` contains `.arc` archives storing `.bclim` images for icons, pictures, frames, etc. (see [Editing .arc Files](https://github.com/Ich73/DQM2-FanTranslation/wiki/Editing-.arc-Files))

The current progress for each language can be found here:
  * `DE` [German](https://github.com/Ich73/DQM2-FanTranslation/wiki/Progress-DE-(German))
  * `EN` [English](https://github.com/Ich73/DQM2-FanTranslation/wiki/Progress-EN-(English))
  * `ES` [Spanish](https://github.com/Ich73/DQM2-FanTranslation/wiki/Progress-ES-(Spanish))
  * `FR` [French](https://github.com/Ich73/DQM2-FanTranslation/wiki/Progress-FR-(French))
  * `IT` [Italian](https://github.com/Ich73/DQM2-FanTranslation/wiki/Progress-IT-(Italian))

## Setup / Installation
If you are interested in installing a release as a `.cia` file read [Installing Releases](https://github.com/Ich73/DQM2-FanTranslation/wiki/Installing-Releases).  
If you are interested in installing the latest updates using Luma's LayeredFS Patching read [Installing LayeredFS](https://github.com/Ich73/DQM2-FanTranslation/wiki/Installing-LayeredFS).  
If you want to contribute to this translation read [Developing Translations](https://github.com/Ich73/DQM2-FanTranslation/wiki/Developing-Translations).
