# vault-public

Public Obsidian vault for publishing knowledge posts.

## Purpose

- Contains only content safe to publish
- Acts as the content source for `myblog`

## Structure

- `posts/` - markdown posts to render
- `assets/` - public images/files referenced by posts

## Frontmatter Rules (required)

Each post in `posts/` must include:

```yaml
---
title: "Post title"
date: 2026-03-24
slug: "post-slug"
tags: [obsidian, blog]
description: "One-line summary"
---
```

## Linking Rules

- Prefer relative markdown links between posts/assets.
- If using Obsidian wiki links (`[[...]]`), ensure your blog build converts them.
- Do not link to private-only notes.
