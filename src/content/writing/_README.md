Add each article as a `.md` file in this folder. Its filename becomes the URL slug. For example, `my-note.md` becomes `/writing/my-note`.

Start with this frontmatter, then write the article below the second `---`:

```yaml
---
title: A future article
description: A short summary shown on the writing index and in search previews.
pubDate: 2026-09-25
category: Notes
draft: true
tags: []
---
Article text goes here.
```

Use `draft: true` while an article is in progress. Drafts are available locally during development but omitted from public builds. Set it to `false` (or remove it) when ready to publish. `updatedDate` is optional.

Files beginning with an underscore are ignored by the content collection. `hello-from-markdown.md` is the small published example for this workflow.
