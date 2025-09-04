---
{"created":"2025-09-04T11:27","updated":"2025-09-04T12:00","id":17,"dg-permalink":"17-html-meaning","dg-publish":true,"permalink":"/17-html-meaning/","dgPassFrontmatter":true,"noteIcon":"1"}
---

HTML defines structure and meaning of web content, so our use of HTML tags should reflect this purpose. 

I use this tag hierarchy to support this: 
- semantic: `<aside><article><nav><h3><figure>`
- structural: `<p><ul><table>`
- custom (describing contents): `<user-profile><game-over><lotto-ticket>`
- generic containers [[prefer div and span as last resort\|when nothing else works]]: `<div><span>`

Reasons: 
- this order prioritises semantics and structure over other aspects
- human readability 
- custom html tags are standard
- no semantic loss: custom tags at least tell humans what's inside (in theory)

In other words, I agree with [replacing divs with custom elements](https://matthewjamestaylor.com/div-custom-elements)). 