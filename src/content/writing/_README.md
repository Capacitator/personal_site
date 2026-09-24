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

New articles default to drafts, so an omitted `draft` field is safe. Keep `draft: true` while writing; drafts are available locally during development but omitted from public builds. Set `draft: false` when ready to publish. `updatedDate`, `image`, and `imageAlt` are optional; an article image is used for social previews, while the shared default image is used otherwise. Include descriptive alt text for every image in the article body. The page title becomes the article’s single H1, so start body sections at `##`.

Files beginning with an underscore are ignored by the content collection. `hello-from-markdown.md` is the small published example for this workflow.
