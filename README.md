# Homebrew PESUECC website

This repository contains Homebrew's website. For the staff members to contribute to this repo, please follow the given instructions below to clone 
this repo and setup the preview.

## Getting Started

- Clone this repository with `git clone https://github.com/homebrew-ec-foss/homebrew-internethome.git`,

- Navigate to the newly created repository on your machine.

- Install dependencies with `yarn install`

- Serve the site locally with `yarn dev`

- Use `yarn build` to build a production version of the site.

- You can now access the website locally by going to `http://localhost:8080` on your browser.

Note: Requires nodejs to be installed.

## Manually Edit contents

### Homepage

Edit the homepage content at `src/index.md`.

Sample frontmatter for homepage.

```
---
layout: home
title: 'Eleventy Duo'
---

Contents
```

### About page

Edit the about page content at `src/about.md`.

Sample frontmatter for about page.

```
---
title: About Aidan Charles Powell
layout: about.njk
name: Aidan Charles Powell
image: '/images/me.jpeg'
---

Contents
```

### Blog posts

Blog contents is at `src/posts`. Delete placeholder blog posts. Do not delete the `posts.json` file. Create blog posts in markdown format.

Sample frontmatter for blog posts.

```
---
title: Even yet another post with rich media
date: '2020-12-24'
tags: [demo-content, media]
decription: The last person we talked to said this would be ready action item, and what do you feel you would bring to the table if you were hired for this position bells and whistles. #optional
---

Contents
```

### Generic pages

You can create generic pages in markdown format that use a base layout.

Sample frontmatter for generic pages.

```
---
layout: base
permalink: /generic-page
title: Generic page
---

Contents
```

*** ***

## What is Homebrew?

Homebrew aims to be a community of FOSS enthusiasts, as well as the one-stop shop for those
curious about and interested in FOSS. It aims to be a forum where enthusiasts can discuss their
favorite open source technologies, and discuss them with other enthusiasts, while also keeping track
of alternatives and suggesting different software.
Students can also exhibit their projects in the "Homebrew Expo" that occurs every week, akin to the
actual Homebrew.

## Who is Homebrew catering to?

The students of PES university, EC campus. As well as every human on earth interested in FOSS.

## Why Homebrew?

There's no major FOSS Community in PES, which is somewhat detrimental to the FOSS situation on
campus. It's necessary to have a bunch of enthusiasts who are open about their ideals as well as their
software to ensure the free software and FOSS message gets passed on to future generations.


*The template used is [Eleventy Duo by Yinka Adadire](https://github.com/yinkakun/eleventy-duo/)*
