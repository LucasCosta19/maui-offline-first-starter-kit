# Maui Offline-First Starter Kit — Landing v4 Commercial

Static landing package prepared for:

https://lucascosta19.github.io/maui-offline-first-starter-kit/

## Product facts preserved

- v1.0.0
- 375 automated tests
- Windows functionally validated
- Android functionally validated
- Developer License: US$79
- Team License · 5 seats: US$199

## What changed

- Fixes the responsive image-height defect by applying `height: auto` to hero, demo, and gallery images.
- Rewrites the hero around the commercial outcome instead of a generic offline claim.
- Adds a Product Flow section directly after the hero.
- Provides an accessible mobile navigation menu below the 1040 px breakpoint.
- Prevents header overflow on narrow mobile screens.
- Unifies mobile gutters between `.shell` and `.container`.
- Consolidates release confidence and platform validation into one section.
- Replaces visually clickable but inactive pricing buttons with honest availability notices.
- Places license, support, and refund links beside pricing.
- Moves Support before the final commercial CTA.
- Reduces repeated proof and excess vertical spacing.
- Adds an SVG favicon.

## Publish on GitHub Pages

Replace the public repository contents with the contents of this folder, then commit and push to `main`.

Keep GitHub Pages configured as:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`

## Included product demo

The Product Flow section includes the finished 68-second demo:

```text
assets/MauiOfflineFirstKit-1.0.0-demo-web.mp4
```

Video properties:

- H.264 / MP4
- 1600 × 900
- 30 fps
- no audio track
- approximately 725 KB

The poster is extracted from the demo opening frame and stored at:

```text
assets/maui-offline-first-demo-poster.webp
```

The video uses controls, `playsinline`, `muted`, and `preload="metadata"`. It does not autoplay, which keeps the page lightweight and avoids unexpected playback.

## When live checkout is available

Replace each `.availability-note` in `index.html` with a real `<a class="button">` pointing to the matching live Lemon Squeezy checkout:

```text
Get Developer License — US$79
Get Team License — US$199
```

Also change the header `Pricing` link and the final CTA if you want them to go directly to checkout. Never publish Test Mode checkout URLs.
