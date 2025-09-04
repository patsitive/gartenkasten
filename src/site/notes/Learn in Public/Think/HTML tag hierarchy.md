---
{"created":"2025-09-04T13:01","updated":"2025-09-04T14:59","id":"17b","dg-permalink":"17b-html-hierarchy","dg-publish":true,"dg-path":"Think/HTML tag hierarchy.md","permalink":"/17b-html-hierarchy/","dgPassFrontmatter":true,"noteIcon":"1"}
---

[**Prev**:: [[HTML tag use should convey meaning\|HTML tag use should convey meaning]]] because HTML defines structure and meaning of web content.

So why keep using `<div>` and `<span>`? 🤔

I use this tag hierarchy to support this: 
1. semantic: `<aside><article><nav><figure>`
2. structural: `<p><ul><table>`
3. custom (descriptive): `<user-profile><game-over><lotto-ticket>`
4. generic containers [[prefer div and span as last resort\|when nothing else works]]: `<div><span>`

This order prioritises semantics and structure over other aspects and aims to be accessible and SEO-friendly. 