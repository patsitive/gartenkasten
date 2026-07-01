---
{"created":"2025-09-04T13:01","updated":"2026-01-08T09:29","id":"17b","dg-permalink":"17b-html-hierarchy","dg-publish":true,"noteIcon":"2","source":"personal","dg-path":"Think/HTML tag hierarchy.md","permalink":"/17b-html-hierarchy/","dgPassFrontmatter":true,"dg-note-properties":{"created":"2025-09-04T13:01","updated":"2026-01-08T09:29","id":"17b","noteIcon":"2","source":"personal"}}
---

[**Prev**:: [[Learn in Public/Think/HTML tag use should convey meaning\|HTML tag use should convey meaning]]] because HTML defines structure and meaning of web content.

So why keep using `<div>` and `<span>`? 🤔

I use this tag hierarchy to support this: 
1. semantic: `<aside><article><nav><figure>`
2. structural: `<p><ul><table>`
3. custom (descriptive): `<user-profile><game-over><lotto-ticket>`
4. generic containers [[Learn in Public/Think/Prefer div and span as last resort\|when nothing else works]]: `<div><span>`

This order prioritises semantics and structure over other aspects and aims to be accessible and SEO-friendly. 

#html #tech