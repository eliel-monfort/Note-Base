---
title: Configuration Guide
---

You can customize Hextra through the `hugo.yaml` file.  
Some common configuration areas include:

- **Site title**: Changes the top bar title  
- **Menu structure**: Defines sidebar and header links  
- **SEO options**: Enables meta tags, Open Graph, and Twitter cards  
- **Language settings**: Supports multi-language documentation

Here is a basic example:

```
baseURL: "https://example.com"
title: "My Documentation Site"
defaultContentLanguage: "en"
menu:
main:
- name: Home
pageRef: /
```