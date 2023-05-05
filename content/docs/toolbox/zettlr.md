---
title: "Writing with Zettlr"
linktitle: "Zettlr"
type: book
weight: 30
---

You are probably used to doing most or all your writing in Microsoft Word or a similar word-processing program. A central tenant of writing at the Workshop is: ***word processors are bad for writing and bad for thinking***. We'll avoid using them whenever possible. There are simply much better ways to research and write based on the [key concepts](../../intro/concepts) you read about earlier in these docs.

Instead of using a word processor, we'll write almost everything in plain text using a minimal markup language called [Markdown](../../writing/markdown). This process will likely seem strange to you at first, but with a bit of practice it will free you up from all the unnecessary distractions and annoyances of a conventional word processor--many of which you have probably become so accustomed to that you've stopped noticing them.

Plain text files written in Markdown can be authored using any number of apps. We'll use an app called [Zettlr](https://zettlr.com) because it provides some basic functionality we need to build our knowledge ecosystem with notes and write longer academic papers and reports with full citations.

{{% callout warning %}}

**Obsidian**

Zettlr is still a great application for writing markdown notes and documents for our research, but an alternative tool called [Obsidian](https://obsidian.md) is gaining popularity and has some different features and advantages. The docs don't currently cover setup of Obsidian as an alternative to Zettlr, but if you want to experiment with this software let Jamie know.

{{% /callout %}}

## Installing Zettlr

Visit the [Zettlr download page](https://zettlr.com/download) and install the version of Zettlr appropriate to your operating system. 

Once you've installed the software, it is worth reviewing the [Zettlr documentation](https://docs.zettlr.com/en/) for an overview or further details as needed. 

## Setting up the Citations Function

You'll need to complete one final step in order to take advantage of Zettlr's ability to import citations directly from the shared reference library maintained by Zotero. 

Select ```Zettlr > Preferences > Citations```. You should see a box entitled "Citation Database (CSL, JSON or BibTeX)". This is where you'll select the local file on your computer that you [exported from Zotero using Better BibTeX](../bibtex#initial-export). Once you've located the reference file, close the Preferences dialog.

To test that your citations are working propertly, select ```File > New File > Markdown``` and once the new document is open type the "@" symbol. You should immediately see a drop-down list of the references available to cite. Further info on citing sources when writing in Markdown is contained in the [Citations section](../../writing/citations) of these docs.