---
date: 2024-02-06
categories:
  - MkDocs
---

# Build a blog with Material for MkDocs

Source: [https://squidfunk.github.io/mkdocs-material/setup/setting-up-a-blog/#blog-only](https://squidfunk.github.io/mkdocs-material/setup/setting-up-a-blog/#blog-only)

<!-- more -->

The minimal required directory structure:

```
.
├─ docs/
│  └─ posts/xxx.md
└─ mkdocs.yml
```

* `.authors.yml` is optional
* `index.md` will be created automatically

The `mkdocs.yml`:

```
theme:
  name: material
  language: en

plugins:
  - blog:
      blog_dir: .
```

Install required packages:

```
pip install mkdocs mkdocs-material
```

Preview the site:

```
mkdocs serve
```
