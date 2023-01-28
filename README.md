# CrossCode Speedrunning Resources
A community-managed repository of resources for speedrunning CrossCode!

This repository contains a growing collection of save presets, blank splits for LiveSplit, and autosplitters for CrossCode speedrunning categories.

## CrossCode Speedrun Setup Guide

If you've arrived here and wish to know more about these resources and how they are useful for speedrunning, you might be interested in the [CrossCode Speedrun Setup Guide](https://docs.google.com/document/d/1d-CyFdjIGCTe6IbWznGMGgA6R9gG4A6U0pj15fPHV14/edit?usp=sharing).

## Using This Repository

In order to make use of these resources, you'll first want to download everything by selecting **Code** around the top-right of this page, then **Download Zip**

![image](https://user-images.githubusercontent.com/32598419/215237322-473aa912-7b72-4bf1-bcad-848ab9c3a3b7.png)

The currently available resources exist in 3 types:

## Save Presets

These are used in combination with [CCPresetRevivalPlus](https://github.com/EpicYoshiMaster/CCPresetRevivalPlus), check there for more information on how to create your own and how to organize them using the mod.

## LiveSplit Blank Splits

These are blank split files for [LiveSplit](https://livesplit.org/), a widely used speedrun timer program. Splits in these files will match their associated splitters in the next section, so it's nice to have these as a base.

## CCTimer Autosplitters

These are autosplitter files for use with [CCTimer](https://github.com/CCDirectLink/CCTimer). Each (completed) category folder includes a `settings.json` file for doing full runs of the category and an `autosplitters` folder, which contains additional splitters for each of the segments in the run. These folders are organized so they can be easily copied directly into the `timer` folder of CCTimer.

## Contributing

Contributions are absolutely welcomed!

If you make a fork of this repository, you can submit a **Pull Request** including the resources you'd like to add/modify.

Alternatively, you can contact **EpicYoshiMaster#0693** on Discord, or mention in the **#speedrunning** channel of the [Official CrossCode Discord](https://discord.gg/crosscode) to send resources to be added here.

## Full Formatting Guide

Abbreviations for \<Category Name\> are acceptable in circumstances where it may be more convenient and generally unambiguous, but favor the full name for the Root folder.

Check **Any% NMG** for a complete example using this form of styling.

**Root**:
- \<Category Name\> (Folder)

**\<Category Name\>**:
- CCTimer Autosplitters (Folder)
- LiveSplit Blank Splits (Folder)
- Save Presets (Folder)

**Timer Autosplitters**:
- autosplitters (Folder)
- settings.json (Primary autosplitter for running the full category)

**autosplitters**:
- ##-\<Segment-Name\>.json (Set of segment autosplitters for running the category)

**LiveSplit Blank Splits**:
- CrossCode - \<Category Name\>.lss (Blank Splits for full category)
- CrossCode Segments \<Category Name\> - ## \<Segment Name\>.lss (Set of segment blank splits)

**Save Presets**:
- \<Save Preset Folder Name\> (Folder)

**\<Save Preset Folder Name\>**:
- ##-\<Presets Segment Name\> (Folder)

**\<Presets Segment Name\>**:
- ##-\<Category-Name\>-\<Preset-Name\>.json (Save Preset file)
