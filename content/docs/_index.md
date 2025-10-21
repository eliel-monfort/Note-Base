---
date: '2025-10-20T20:29:04+03:00'
draft: true
title: "Introduction"
---

Welcome to your site powered by the **Hextra theme** for Hugo.  
This page demonstrates how headings and subheadings create a **right-hand table of contents** automatically.

***

## What is Hextra?

Hextra is a modern, responsive, documentation-style theme built using Hugo and Tailwind CSS.  
It is designed for **speed, readability, and ease of customization**.  

### Key features

- Automatic sidebar and table of contents generation  
- Built-in full-text search engine (FlexSearch)  
- Syntax highlighting and Markdown enhancements  
- Dark mode support  
- SEO-ready configuration out of the box  

***

## How the Right Sidebar Works

The right-hand sidebar in Hextra is generated from your Markdown headings.  
Every heading level (`##`, `###`, etc.) becomes a link in the sidebar (Table of Contents).

### Example

If your document has the following:
```markdown
## Section One
### Subsection A
### Subsection B
```
Then your right sidebar automatically lists:
- Section One  
  - Subsection A  
  - Subsection B  

***

## How to Create Pages

You can create new pages using Hugo’s CLI:
```bash
hugo new path/to/page.md
```
Each page can include front matter like this:
```yaml
---
title: "New Page"
description: "Describe your topic here"
---
```

***

## Markdown Formatting Examples

### Code Block
```bash
hugo server --buildDrafts
```

### Quote
> “Static sites are fast, simple, and secure.”

### Lists
- Item one
- Item two
- Item three

***

## Next Steps

Now that your site is running:
1. Add more pages under `content/` with proper headings.  
2. Update your sidebar menu in `hugo.yaml` if necessary.  
3. Customize your theme by editing `assets/css/custom.css` or adding configs in `params:`.

You should now see multiple sections appear in your right sidebar — “What is Hextra?”, “How the Right Sidebar Works”, “How to Create Pages”, “Markdown Formatting Examples”, and “Next Steps”.