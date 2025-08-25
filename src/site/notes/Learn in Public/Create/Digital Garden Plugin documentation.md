---
{"created":"2025-08-26T10:06","updated":"2025-08-26T10:37","dg-publish":true,"noteIcon":"log","dg-path":"Create/Digital Garden Plugin documentation.md","permalink":"/create/digital-garden-plugin-documentation/","dgPassFrontmatter":true}
---

We are working on making the [oleeskild/obsidian-digital-garden](https://github.com/oleeskild/obsidian-digital-garden) documentation EVEN BETTER. This is a draft project page lol. I am posting this online because Discord said my message is too long (rude).

## Goals: 
1. Easy to publicly access and comment,
2. Multiple moderators,
3. Easy to maintain and update by different people

## Options to host 

### Fork dgdocs repo
> Unfortunately, I think this rules out just cloning digitalgardendocs repo because there's some transliteration that occurs from plugin to repo, and it's one way; if we initiate pull-requests, Ole's not really able to implement them without some heavy lifting.

I'm not sure what this means, but I'm all good with not cloning the docs repo

- requires Ole to accept changes to main docs website 
- but will be its own standalone website on Vercel (so it is publicly available for people to access)
- because it's independent we need to work on SEO for people to find the website (if Ole doesn't accept our changes)
- if changes are accepted, then all DG plugin docs are in one place 
- all 3 of us can edit (and so can more people if they have GitHub)

### IndieWeb wiki
> IndieWeb wiki

So as @palol said, we just need to have a website to be able to log in and edit their wiki—add, modify, or delete content or pages. 

FYI, I just updated the [Obsidian - IndieWeb](https://indieweb.org/Obsidian) page last night to more clearly show what options are there to use Obsidian to build a personal website. 🌟

- has a bigger reach (established website and SEO)
- can introduce the DG plugin to more people
- already pages about Obsidian, digital garden concept, etc 
- IndieWeb focus is about owning your data and identity—which is aligned with DG plugin just post your raw text online 
- We can have a sub-page that's about planning what info to publish online 
- requires a website to login and edit 
- not standalone website (not specific to DG plugin)
- all 3 of us can edit (and so can anyone on the IndieWeb wiki)—more collaboration 
- no blockers (anyone can push / edit and revert if needed)

### GitHub pages / DG plugin

> I think publishing with something like [GitHub Pages is a nice middle ground](https://nicolas-van.github.io/easy-markdown-to-github-pages/ ; it's entirely managed in GitHub, uses a version of Markdown, and we could do all management from one site.

So to my understanding GitHub pages is just another static site generator like DG plugin. So technically we could use this or another Obsidian vault equipped with digitalgarden plugin, and in theory the effect is the same? 

- all 3 of us can edit (and anyone with GitHub via PR)
- is its own standalone website that people can view online
- will need to work on SEO to get people looking at this 
- maybe blockers if people have forked and trying to get PR accepted (e.g. all 3 of us not available for some reason)

## What I think 

#### Hybrid approach 

- Digital Garden-plugin-based website to showcase how CSS, templates, components work or look in practice; points to IndieWeb wiki or official DG docs website where appropriate 
- IndieWeb wiki for how-to, background info, examples of people using it, etc (which is a common practice on the wiki)

Benefits: 
- DG-plugin-based website showcases the DG-plugin by being made from DG-plugin
	- we can set up from an Obsidian vault once and then do manual tinkering on GH! 
- Boosted visibility and SEO from IndieWeb audience 
- We can still request for Ole to add a link to the showcase site from the Discord and/or DGdocs website 

@palol, I think we can grab a lot of the content from the DG-plugin GH Discussions as use it to seed our own site :) 