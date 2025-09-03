---
{"created":"2025-09-04T11:27","updated":"2025-09-04T11:40","id":17,"dg-permalink":"17-html-meaning","dg-publish":true,"permalink":"/17-html-meaning/","dgPassFrontmatter":true,"noteIcon":"1"}
---

I've been reflecting on web development and design. 

In my opinion, we should strive to convey semantic information through HTML. 

To do this, I propose this hierarchy order of HTML tag use: 
- semantic tags: `<aside><article><nav><h3><figure>`
- non-semantic standard tags: `<p><ul><table>`
- custom tags: `<user-profile><game-over><lotto-ticket>`
- when nothing else works: `<div><span>`

Reasons: 
- preference for semantic meaning and standards over other aspects
- human readability 
- no semantic loss: custom tags at least tell humans what's inside (in theory)