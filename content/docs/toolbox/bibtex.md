---
title: "Installing Better BibTeX"
linktitle: "Better Bibtex"
type: book
weight: 20
---

Better BibTeX is an add-on extension for Zotero that will allow you to access the shared reference library directly and conveniently when writing notes and other documents. The extension serves two essential functions: it (1) assigns a unique "citation key" to each reference in the library and (2) automatically exports and keeps up-to-date a bibliography file on your computer that can be used to cite sources as you write. 

## Install Better BibTeX

Download the extension file (*.xpi) from [GitHub here](https://github.com/retorquere/zotero-better-bibtex/releases/tag/v6.4.2) and then [follow these installation instructions](https://retorque.re/zotero-better-bibtex/installation/). 

## Zotero Settings

Once Better BibTeX is installed, open Zotero and select ```Preferences > Better BibTeX``` (on Mac) or ```Edit > Preferences > Better BibTeX``` (on Windows). Under the ```Citation keys``` tab, ensure that the "Citation key format" is entered as ```auth.lower+year+shorttitle(3,3)```.

## Initial Export 

The final step to setup Better BibTeX is to run an initial export of the shared reference library data to a reference file on your local computer. You only need to do this once--after that, Zotero will keep the reference file up to date with any additions or changes you or others make to the shared reference library. 

After selecting the ```radish``` library in the left-hand pane of Zotero, click ```File > Export Library```. Then select "Better CSL JSON" under "Format" and ensure that the ```Keep updated``` box is checked. 

Zotero will then ask you to save the export as a file on your computer. You can name this file anything you like and locate it anywhere in your local filesystem (e.g. a file called "radish" in a new folder, Documents/Bibtex/). Click "Save", make a note of where you stored the file, and you're all done. 