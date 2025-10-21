---
title: Performance Optimization
---

Hugo and Hextra are extremely fast by default, but here are a few tips to make builds even faster:

1. Use Hugo modules to avoid extra git dependencies.  
2. Minimize image sizes in the `static/` folder.  
3. Use page bundles and avoid unnecessary content duplication.  
4. Run `hugo --gc --minify` for a clean, compressed output.
