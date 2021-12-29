# Oxygen Not Included DK
This repo holds the mod- and translation files for the Oxygen Not Included Danish Translation. The mod is available at the [steam work shop](https://steamcommunity.com/sharedfiles/filedetails/?id=2429684154)

This is a continuation of an earlier translation project, lead by [Coronawalderen](https://steamcommunity.com/id/krautwalderen) - thanks for laying out the ground work!

# Contribution
You can contribute to the translation project by adding danish translation to the [`strings.po`](strings.po) file and opening a pull request. 

All strings with an empty `msgstr` needs translations, and any contributions are welcome, no matter how big or small.

The easiest way to edit the [`strings.po`](strings.po) file is directly from your browser by using the [github.dev web-based editor](https://github.com/Belenos-Mods/ONI-DK/): Simply go to the repo's ever-living translations branch [ongoing](https://github.com/Belenos-Mods/ONI-DK/tree/ongoing) and hit `.`.  

For more advanced editing, the [Poedit](https://poeditor.com/) tool is recommended.

##  Merging to master
All completed PR's to `master` should be accompanied by an [update to the steam mod](#uploading-updates). 

## Local testing
To check out translation efforts locally copy the `strings.po` file to the local translation mod folder (i.e. `C:\Users\[Username]\Documents\Klei\OxygenNotIncluded\mods\Steam\2429684154`) and restart the game.  

To check if the translation works, you can edit one of the strings on the splash screen (like `STRINGS.UI.FRONTEND.MOTD.NEWS_HEADER`), to quickly assert if the correct `strings.po` is being read by the game.

## Steam Mod Info  
A general introduction on how to do ONI translations is available at the [klei forums](https://forums.kleientertainment.com/forums/topic/74765-creatingusing-translation-files-updated-august-22nd-2017/). Start there.  

### Uploading updates
  - Use the ONI Uploader tool
  - tick the `Update Data` box and point to the repo folder to include the updated `strings.po` file. 
  - tick  the `Update Details` box to include an update of the progress so far
    - The progress bar is generated at [this url](http://scripts.cac.psu.edu/staff/l/n/lnm105/progressbar.html) and saved on imgur.  
    

## TODO
    - handling .pot file (update for newer versions of game)
    - explain `mod_info.yaml` and `strings.mo`
