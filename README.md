# Modding

### Please note that this repo is WIP and is useless right now.

This repository contains VB code that contains the core functionality of ShiftOS for modding purposes. The repo contains:
 * Core of ShiftOS, including the window manager, skinning system and other useful core features.
 * The modification packer binaries
 * Documentation files
 * A sample modification showing off basic core functionality.
   - Source Code of this modification
   - Packed ShiftOS Mod File (.smf)
You can pull or fork this repository and create your own modifications, however we ask that you do not modify the skinning and window manager system, as we want to keep it the same as the two modules built into the [main ShiftOS repo](http://www.github.com/shiftos/shiftos) and Orion.

# Core

The Core is found in the "shift_core" directory and hosts the Color Picker, Infobox, Skinning and Window Manager modules and classes. It also contains a blank ShiftOS window in the "main.vb" file which inherits from the window manager.

# Modification Packer

This tool allows you to pack the binaries, DLLs and other files used in your mod to a ShiftOS compatible .smf file. When added to anywhere inside the ShiftOS root (i.e "_C:\ShiftOS_"), you can load the file up in the File Skimmer and it'll load as if it was a regular .saa (pirated Shiftnet application) file.

# Documentation

If you ever need help, see the Docs.pdf file in the root of the repo. This file can be read in applications like MS Word, Adobe Reader and most eBook applications. It is written by Michael VanOverbeek and contains everything you need to know about creating and curating mods for ShiftOS.