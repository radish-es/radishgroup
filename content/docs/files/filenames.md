---
title: "Filenames"
linktitle: "Filenames"
type: book
weight: 3
---

In addition to properly locating files within the directory structure on NextCloud, filenames themselves are important for good data organization. There are two types of naming conventions you should follow, depending on the type of file.

## Literature Notes

Literatures notes written in Markdown (with the extension .md) and corresponding to a source stored in Zotero should be named using the ```CitationKey``` generated automatically by Zotero, which takes the form AUTHOR|YEAR|TITLE (e.g., `goodrich1991eating.md`). 

## Research Notes

Research notes written in Markdown (with the extension .md) should be named with a date-time identifier (a string of 12 numbers) in the format: YEAR|MONTH|DAY|HOUR|MINUTE (e.g. 202203160824.md). This format has two purposes: (1) it provides a unique identifier for each file that you don't have to choose yourself and (2) it automatically logs the date and time the file was created. 

You can set up [Zettlr](../../toolbox/zettlr) to create new notes with this filename pattern automatically by doing the following:

1. Select ```Zettlr > Preferences > Advanced```;

2. In the "Pattern for new filenames" box, type: ```%Y%M%D%h%m.md```

Now, when you select ```File > New File``` in Zettlr, a new note will be created with a filename in the correct format for a research note. 

## Other files 

For all other files stored on NextCloud, strict naming conventions are not as important but please try to follow the general pattern: ```date_created-short_descriptive_title``` (e.g. ```20220316-CommonLandOwnership.md```)