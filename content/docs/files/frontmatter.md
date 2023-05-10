---
title: "Front Matter"
linktitle: "Front Matter"
type: book
weight: 3
---

Front matter (or "metadata") is information included in a special section at the beginning of every [Markdown](../writing/markdown) file--like a literature or research note--that describes various key characteristics of that file (such as its title, the date it was created, etc). All metadata in Markdown comes in the form of key-value pairs, such as:

> ```title: "Why food systems governance is complicated"```

Multiple entries under a given key should be separated by a carriage return, two spaces, and a dash like so:

```
author:
  - Author One
  - Author Two
  ```

Whenever you create a new Markdown file you need to add a minimal amount of front matter, depending on the type of file. This metadata goes at the very beginning of the file between two enclosing lines of three consecutive dashes: ```---```. 

Below are some front matter templates for different types of files that you can simply copy and paste from the docs whenever you need.

### Literature Notes

```
---
title:
author:
  - 
type: literature
year: 
tags:
  - 
  -
---
```

### Research Notes

```
---
title:
author:
  - 
type: research
projects:
  - 
  -
tags:
  - 
  -
---
```

### Working Documents

These are generally longer documents used to create reports, academic articles, and the like.

```
---
title:
abstract: 
author:
  - 
type: doc
projects:
  - 
  -
tags:
  - 
  -
---
```