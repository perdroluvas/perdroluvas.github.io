# perdro's devblog

My personal devblog built with [Jekyll](https://jekyllrb.com/) and the [Papicu](https://github.com/lucasrla/papicu) theme, hosted on [GitHub Pages](https://pages.github.com/).

**Live at:** [perdroluvas.github.io](https://perdroluvas.github.io)

## Writing a new post

Create a new file in `_posts/` with the format `YYYY-MM-DD-title.md`:

```markdown
---
layout: post
title: "My Post Title"
description: "A short description of the post."
categories: topic-name
tags: [tag1, tag2]
---

Your content here in Markdown.
```

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open [http://localhost:4000](http://localhost:4000).
