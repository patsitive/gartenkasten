---
{"created":"2025-09-04T11:27","updated":"2025-09-04T11:52","id":17,"dg-permalink":"17-html-meaning","dg-publish":true,"permalink":"/17-html-meaning/","dgPassFrontmatter":true,"noteIcon":"1"}
---

HTML defines structure and meaning of web content, and therefore our use of HTML tags should reflect this purpose. 

To do this, I propose this hierarchy order of HTML tag use: 
- semantic tags: `<aside><article><nav><h3><figure>`
- structural tags: `<p><ul><table>`
- custom tags that describe its contents: `<user-profile><game-over><lotto-ticket>`
- generic containers [[prefer div and span as last resort\|when nothing else works]]: `<div><span>`

Reasons: 
- this order prioritises semantics and structure over other aspects
- human readability 
- custom html tags are standard
- no semantic loss: custom tags at least tell humans what's inside (in theory)

In other words, I agree with [replacing divs with custom elements](https://matthewjamestaylor.com/div-custom-elements)). 