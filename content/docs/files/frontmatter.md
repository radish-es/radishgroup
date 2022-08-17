---
title: "Front Matter"
linktitle: "Front Matter"
type: book
weight: 3
---

Front matter (or "metadata") is information that tells you about the various characteristics of a given file (like its title, author, etc). 

Whenever you are creating a new Markdown file--whether for a research note or a longer document--you should include a short snippet of front matter that describes some of its basic characteristics, including its relevant [tags](../tags). This takes the following form:

```
---
title: Why good exit strategies are important for common farmland arrangements
author: Your Name
tags: [farmland, commons, note]
---
```

For more than one author, front matter takes this form:

```
---
author:
  - Person 1
  - Person 2
---
```

Other fields you might include in your front matter are:

- ```shorttitle:``` - a short version of the full title
- ```subtitle:``` - sub-title of an article or other document
- ```abstract``` - a brief description of the content (mainly used for longer docs)

