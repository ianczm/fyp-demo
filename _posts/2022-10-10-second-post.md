---
title: Jekyll | First Use
date: 2022-10-10 15:17 +800
categories: [fyp]
tags: [studies, tech, computer science, jekyll]
published: true
---

## Installation Steps

- Install WSL2 (if using Windows)
- Install `homebrew`
- Install latest Ruby version - `3.1.2` via `ruby-install`
- Install `bundler` and `jekyll` via `gem`
- Duplicate repository from [ChirpyStarter](https://github.com/cotes2020/chirpy-starter)
- `git clone` repository from GitHub and `cd` into it
- Run `bundler` to install dependencies

## Quick Start

- Edit `_config.yml` provided in the starter repository to quickly set up author profile and other settings
- Create first post in `_posts` folder with name format `year-month-day-title.md`
- Create front-matter yaml header (example below)
  ```yaml
  ---
  title: Jekyll | First Use
  date: 2022-10-10 15:17 +800
  categories: [fyp]
  tags: [studies, tech, computer science, jekyll]
  published: true
  ---
  ```
- Add content in markdown format below the front-matter header
