# DQM2-FanTranslation
This repository is a place to develop fan translations for _Dragon Quest Monsters 2: Iru and Luca's Marvelous Mysterious Key_ for several different languages. It contains only `.xdela` and `.patJ` patch files so no copyrighted material is shared.  

## Structure
The folder structure in this repository is based on the structure of extracted `.cia` or `.3ds` files.  
Most foldernames consist of the basename of the folder and the locale of the translation, e.g. `Message_EN` contains the messages for the english language. Folders without a locale extension are used for every language except for the original language japanese.  
  
The content of the folders is as follows:
  * `Banner` contains the logo that is shown on the top screen in the 3DS home menu (see [Editing the Banner]())
  * `Font` contains the `.bcfnt` fonts that are used in game (see [Editing .bcfnt Files]())
  * `Layout` contains `.arc` archives storing `.bclim` images for icons, pictures, frames, etc. (see [Editing .arc Files]())
  * `Message` contains `.binJ` files storing texts that can be edited using [BinJ Editor](https://github.com/Ich73/BinJEditor) (see [Editing .binJ Files]())
  * `NaviMap` contains `.arc` archives storing `.bclim` images for icons, pictures, frames, etc. (see [Editing .arc Files]())

The current progress for each language can be found here:
  * `DE` [German]()
  * `EN` [English]()
  * `ES` [Spanish]()
  * `FR` [French]()
  * `IT` [Italian]()

## Setup / Installation
If you are interested in installing a release on your 3DS read [Installing Releases](https://github.com/Ich73/DQM2-FanTranslation/wiki/Installing-Releases).  
If you want to contibute to this translation or want the install the latest version read [Developing Translations](https://github.com/Ich73/DQM2-FanTranslation/wiki/Developing-Translations).
