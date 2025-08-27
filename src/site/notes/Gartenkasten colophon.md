---
{"created":"2025-08-02T18:22","updated":"2025-08-25T09:23","dg-permalink":"colophon","dg-publish":true,"permalink":"/colophon/","dgPassFrontmatter":true,"noteIcon":"1"}
---

## ## Gartenkasten Tech Stack ✨️ 🖥 

### Engine
This gartenkasten website runs on a few moving parts: 
- [ObsidianMD](https://obsidian.md/)—for writing and containing ideas in Markdown files
- [Digital Garden Obsidian Plugin](https://obsidian.md/plugins?id=digitalgarden)—pushes changes from ObsidianMD vault to Github
- Eleventy—generates static web pages
- GitHub—enables version control 
- MyHostNZ—for custom domain 
- [Vercel](https://vercel.com/new/clone?repository-url=https://github.com/oleeskild/digitalgarden)—builds, deploys and hosts website

### Extends 
Additional pieces: 

- [OpenMoji](https://openmoji.org/)– provides images of open-source emoji. License: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/#)
- Canva Pro - I just use it a lot 

> [!tip] Want to look under the hood? 
> [patsitive/gartenkasten: Digital garden + zettelkasten setup for Patsitive](https://github.com/patsitive/gartenkasten) to view the source code on GitHub

> If you are interested in my main website's colophon, I am still working on that 🙆

---
## How to setup 
I know, it's so cool, right? Very [IndieWeb](https://indieweb.org/). 🥰

### I want a digital garden site like yours! 
- Step 1: Download Obsidian
- Step 2: Use the Digital Garden plugin 
	- [dg-docs.ole.dev](https://dg-docs.ole.dev/) for how to set up the Digital Garden plugin and Vercel

### I want that visual garden in your header!
- That's based on Topobon (mix of javascript and CSS)
	- [Visual garden graph JS](https://github.com/uroybd/topobon/tree/main)—adds pretty visual garden view of notes to the header, using Javascript.
- Note: I made some changes to the Topobon component, based on my needs. 
- Step 1: Set-up digital garden website or fork Topobon (or mine!)
	- If you just forked the entire Topobon or my Gartenkasten, then it should work out of the box, but you'll also have all of [uroybd/topobon](https://github.com/uroybd/topobon/commits?author=uroybd)'s notes or my notes on your website...
	- So Step 2a: delete the pages you don't need? 😅 
- Step 2b: Already have a website? 
	- You need to copy over some elements from Topobon to make this work
		- forest.njk — this inserts the garden into your index page 
		- userUtils.js — this generates the garden
		- custom-style.scss — the relevant section dictates how the garden should look 
		- .svg images — these are the elements that are populated in the garden 
		- See: [Topobon issue #33](https://github.com/uroybd/topobon/issues/33) for notes on integrating Topobon into your garden (you do not need to fork the whole thing if you already have a digital garden set-up)
		- Or see: [Swamp website stack](https://www.paologabriel.com/swamp/website-stack/#a-href-https-hermitage-utsob-me-target-blank-class-external-link-hermitage-a-forest) for extended instructions on deploying Topobon (and also where I saw Topobon in the real world)
- To change the images for the garden map, you need to update the `noteLabels` in `userUtils.js` and update CSS as well


- [Topobon issue #33](https://github.com/uroybd/topobon/issues/33) for notes on integrating Topobon into your garden (you do not need to fork the whole thing if you already have a digital garden set-up)
	- `src/site/_includes/components/user/index/header/forest.njk` — created a copy of the forest.njk file from topobon — 
	- `src/helpers/userUtils.js` — replaced with topobon version —
	- `src/site/styles/custom-style.scss` — copied section of styling into existing file — this 
	- `src/site/_includes/layouts/index.njk` — inserted `include` for forest.njk

-  Add `noteIcon` to Digital Garden plugin's **pass-through fields**
    
-  Save & re-publish notes to push new frontmatter values
    
-  Icons are pulled from `noteLabels` in `userUtils.js`
    
-  Any value that's a number gets treated like `tree-[x]`
    
-  Any value that matches a `noteLabels` key (e.g. `bee`) works
    
-  Add matching CSS icons separately later
    