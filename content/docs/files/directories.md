---
title: "Directory Structure"
linktitle: "Directories"
type: book
weight: 2
---

We want the directory structure used to store files on [NextCloud](../../toolbox/nextcloud) to be as "flat" as possible. The goal is to avoid several layers of nested sub-folders that make it difficult to locate information because they create an inflexible structure for information--one that fails to reflect how discrete pieces of knowledge actually connect to one another.

{{% callout warning %}}

Apart from a few high-level folders, use ***tags*** rather than folders to organize information. 

{{% /callout %}}

## Basic folder structure on NextCloud

Below is a schematic for the basic layout of high-level folders in the cloud drive (NextCloud). 

- **admin**: administrative files, such as project descriptions and metadata, task lists, or files dealing with other administrative matters.

- **notes > literature**: all literature notes (written in [Markdown](../../writing/markdown))--one for each source corresponding to a citation stored in Zotero--stored in a single folder.

- **notes > research**: all research notes (written in [Markdown](../../writing/markdown)) stored in a single folder. Here, tags are especially crucial for being able to locate and link relevant notes through [Zettlr](../../toolbox/zettlr).

- **projects**: each project gets its own dedicated sub-folder, which holds images and other media files, data files, and longer writing pieces (articles, briefs, reports, etc) specific to that project. 

- **resources**: technical and learning resources to support your work.

## Directory Diagram

Here is a sample directory structure in graphical form to help you visualize:

```
NextCloud Directory Structure
*****************************

admin
|  projects.md

notes
|
|___literature
|   |  rose1986comedy.md
|   |  goodrich1991eating.md
|   |  ...
|___research
    |  202110130914.md
    |  202201041245.md
    |  202203211522.md

projects
|
|___project01
|   |  blog_post.md
|   |  image.png
|   |  ...
|
|___project02
    |  longer_article.md
    |  ...

resources
|  howtotakenotes.pdf

```

For most purposes, you should *not* need to create a new NextCloud directory. Anytime you want to ensure that it is easy to retrieve a file in the future, consider what tags and other metadata should be included with the file itself (see [Front Matter](../frontmatter)). 