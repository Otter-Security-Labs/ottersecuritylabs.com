+++
title = "Post Title"
# Use ISO 8601 with timezone
date = 2025-09-21T10:00:00-05:00
lastmod = 2025-09-21T10:00:00-05:00
draft = true

# SEO / summaries
description = "One-sentence summary shown in cards and meta tags."
summary = "Short abstract that appears in list views."

# Taxonomies
tags = ["hugo", "static-sites", "tutorial"]
categories = ["Engineering"]
series = ["Hugo Tips"]  # optional

# Slug/URL (pick one; url is absolute path, slug joins section)
# slug = "my-post"
# url = "/blog/my-post/"

# Redirects
aliases = ["/old/my-post/", "/blog/2020/my-post/"]

# Open Graph / Twitter cards (many themes read 'images')
images = ["hero.png"]

# Theme-specific (safe defaults; ignore if your theme doesn’t use them)
[cover]
  image = "hero.png"    # relative to this bundle
  alt = "Hero image alt text"
  caption = "Optional caption"
  relative = true

# Turn on a table of contents if your theme supports it
toc = true
+++

> **TL;DR:** What will readers learn in 2–3 lines?

## Introduction
Set context. Who is this for? What problems are we solving?

## Prerequisites
- Hugo v0.xx+
- Basic Markdown
- Optional: a theme like PaperMod

## Key Takeaways
- Takeaway 1
- Takeaway 2
- Takeaway 3

## Setup
Explain the initial steps. If you reference another post: see {{< relref "another-post/index.md" >}}.

## Step-by-Step
### 1) Do the first thing
Explain why, then how.

```bash
hugo new site mysite
