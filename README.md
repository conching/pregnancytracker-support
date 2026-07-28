# BumpTrackr — Support Site

Support, FAQ, and privacy pages for **BumpTrackr**, an iOS app for expecting
parents that runs from the first positive test through delivery and into the
newborn chapter, with iCloud partner sync so both parents track together.

> The repository name is historical: the app was originally *Pregnancy Tracker*
> and now ships as **BumpTrackr**. The path is preserved because the published
> support URL points here.

## Live pages

| Page | URL |
|------|-----|
| Home | https://conching.github.io/pregnancytracker-support/ |
| Support & FAQ | https://conching.github.io/pregnancytracker-support/support |
| Privacy Policy | https://conching.github.io/pregnancytracker-support/privacy |

These URLs are published on the app's App Store listing and must stay reachable.

## Stack

Static [Jekyll](https://jekyllrb.com/) site, built and served by GitHub Pages
from `main`. There is no local build step.

| Path | Purpose |
|------|---------|
| `index.md`, `support.md`, `privacy.md` | Page content (kramdown, `parse_block_html` on so inline HTML works) |
| `_layouts/default.html` | Shared page shell, nav, and styles |
| `_config.yml` | Site title, description, and `baseurl` |
| `app-icon.png` | App icon used in the page header |

## Making changes

Edit the relevant `.md` file and push to `main`. GitHub Pages rebuilds
automatically, usually within a minute. Confirm the live URL afterward —
a broken support link is an App Store review issue.

Contact: conching@me.com
