---
title: "This is a Test Blog"
date: "2026-11-10"
description: "A full feature test: images, video, audio, code blocks, links, lists, blockquotes, and more."
---

## Introduction

Welcome to the feature test post. This page exists to make sure every element — images, video, audio, code, links, tables, blockquotes, and lists — renders correctly and looks good.

If you're reading this, the blog system is working. Here's a photo taken somewhere over the Arabian Peninsula at dusk.

![Anime sky wallpaper](/assets/blogs/2026/anime-sky-wallpaper-2026.webp)

Click the image above to expand it in the lightbox. Every image in a post is clickable.

## Embedded Video

Below is a YouTube embed. The player is lazy-loaded so it won't slow down the page.

[youtube](https://youtu.be/dQw4w9WgXcQ)

Video renders at a 16:9 ratio and is fully responsive on mobile.

## Audio Player

Audio posts work too. The browser's native `<audio>` element is used so it works everywhere without a library.

![Audio test](https://www.w3schools.com/html/horse.mp3)

The audio tag above loads a sample clip. Replace the path with any `.mp3`, `.ogg`, `.wav`, `.flac`, or `.aac` file in your `assets/` folder.

## Typography

This section tests basic inline formatting.

Here is **bold text**, *italic text*, ***bold and italic***, and `inline code`. You can also write [external links](https://abdulazizhu.com) that open in a new tab.

A bare URL auto-links too: https://github.com/Abdulaziz-hu

### Headings Nest Properly

This `h3` shows up indented in the table of contents on the right. Headings at `##` level create the main TOC entries; `###` nests one level under them.

## Blockquotes

> The best way to get started is to quit talking and begin doing.
> — Walt Disney

> Sometimes a blockquote runs longer. Here is one:
> Good design is as little design as possible. Less, but better — because it concentrates on the essential aspects, and the products are not burdened with non-essentials. Back to purity, back to simplicity.
> — Dieter Rams

## Lists

Unordered list:

- Cybersecurity fundamentals
- Audio engineering and mixing
- Side projects and open-source
- Photography when the light is right
- Gaming — non-negotiable

Ordered list:

1. Clone the repository
2. Run `npm install` to install dependencies
3. Copy `.env.example` to `.env` and fill in your values
4. Start the dev server with `npm run dev`
5. Open `http://localhost:5173` in your browser

## Code Blocks

A JavaScript snippet:

```javascript
// Simple debounce utility
function debounce(fn, delay = 300) {
  let timer;
  return (...args) => {
    clearTimeout(timer);
    timer = setTimeout(() => fn(...args), delay);
  };
}

const onScroll = debounce(() => {
  console.log('scroll position:', window.scrollY);
}, 100);

window.addEventListener('scroll', onScroll, { passive: true });
```

A Bash snippet:

```bash
# Update system and install essentials
sudo apt update && sudo apt upgrade -y
sudo apt install -y git curl build-essential

# Clone and set up the project
git clone https://github.com/Abdulaziz-hu/rssflow.git
cd rssflow
npm install
cp .env.example .env
```

A Python snippet:

```python
import hashlib
import os

def hash_password(password: str) -> str:
    """Hash a password with a random salt using SHA-256."""
    salt = os.urandom(32)
    key = hashlib.pbkdf2_hmac('sha256', password.encode(), salt, 100_000)
    return salt.hex() + ':' + key.hex()

print(hash_password("hunter2"))
```

## Horizontal Rule

A thematic break between sections:

---

## Links

Some useful links for reference:

- [GitHub — Abdulaziz-hu](https://github.com/Abdulaziz-hu)
- [Codeberg — Abdulaziz-hu](https://codeberg.org/Abdulaziz-hu)
- [Twitter / X — @Azizif220](https://x.com/Azizif220)
- [LinkedIn — abdulaziz-alhuzami](https://www.linkedin.com/in/abdulaziz-alhuzami/)
- [Lucide Icons](https://lucide.dev) — the icon set used on this site
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) — the monospace font

## Final Thoughts

That covers every major element the blog renderer supports. If something looks off or broken, this is the post to debug with — everything should render cleanly, be readable, and feel right on both mobile and desktop.

Thanks for reading.
