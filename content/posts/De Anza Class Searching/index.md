+++
date = '2025-10-19T20:07:14-07:00'
draft = false
title = 'De Anza Class Searching'
description = "Class Searching — a Tiny Static Link Builder"
summary = "Help you to find the hidden classes on De Anza website"
tags = ["web", "javascript", "static-site", "posts"]
+++

You can try it here: 👉 **[da-class.shunyao.xyz](https://da-class.shunyao.xyz/)**

## Overview
A minimal, **static** web page that builds De Anza schedule URLs from a few inputs and opens them in a new tab. No backend, no dependencies. It’s perfect for hosting on GitHub Pages / Netlify / Vercel / Cloudflare Pages.

- **Base URL**: `https://www.deanza.edu/schedule/listings.html`
- **Params**:
  - `dept`: Department code (official dropdown options)
  - `t`: `<QuarterLetter><Year>`; e.g. `W2026`
    - Spring = **S**, Summer = **M**, Fall = **F**, Winter = **W**

## Features
- Centered, lightweight UI (pure HTML/CSS/JS, no frameworks).
- Official department `<select>` options for convenience.
- Live URL preview.
- **Open in new tab** and **Copy link** actions.

## How to Use
1. Pick the **Department Code** from the dropdown.
2. Choose **Quarter** and enter **Year** (4 digits).
3. Click **Open in New Tab** (or **Copy Link**).
4. The page composes `?dept=<DEPT>&t=<LETTER><YEAR>` and navigates in a new tab.

## Quarter Mapping
- Spring → `S`
- **Summer → `M`** (note the custom mapping)
- Fall → `F`
- Winter → `W`
