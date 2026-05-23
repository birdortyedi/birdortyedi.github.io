---
title: "Introducing the New Modern Look"
date: 2026-05-23
permalink: /blog/introducing-the-new-look/
tags:
  - website
  - design
  - development
header:
  teaser: blog-placeholder.png
---

![][teaser]{: .img-rounded}

Welcome to the new look of my academic personal website! In this post, I want to briefly outline the motivations and details behind the recent major design overhaul of this site, transitioning it to a sleek, modern developer-focused portfolio.

## Motivations for the Redesign

The previous layout utilized standard typography and color patterns which, while functional, lacked visual personality. The goal of this redesign was to introduce a state-of-the-art dark theme that balances readability with premium aesthetic details.

Here is a breakdown of the key elements updated:

### 1. Modern Typography Scale
We've integrated Google Fonts to create a clean visual hierarchy:
* **Outfit**: A sharp, geometric sans-serif for titles and headings.
* **Inter**: A highly legible sans-serif for paragraph text.
* **Fira Code**: A programming-focused monospace font with beautiful ligatures for code blocks.

### 2. Deep Slate Color Scheme
Normally, I am a black/gray guy, but we decided to experiment with a **deep slate dark mode** (`#0b0f19`). Accent link colors are now mapped to a vibrant sky blue (`#38bdf8`) with glowing hover states.

### 3. Glassmorphic Sidebar Card
The profile sidebar now features backdrop blur, a subtle border, and soft drop shadows to give a "floating glass" effect. The avatar has a hover scaling and glowing rotation animation.

### 4. Lifted Publication Cards
Listings now float inside translucent card elements (`.list__item`) that lift up slightly on hover to invite interaction.

---

## Code Highlighting Showcase

Here is a quick showcase of the new hybrid **One Dark / GitHub Dark** code highlighting theme that makes code blocks and BibTeX citations highly readable:

```python
# A simple showcase of the new syntax theme
def greet_visitor(name):
    greeting = f"Welcome to the new site, {name}!"
    print(greeting)
    return True

greet_visitor("Furkan Kınlı")
```

I hope you enjoy browsing the new site! Feel free to explore the publications and CV tabs.

[teaser]: /images/blog-placeholder.png
