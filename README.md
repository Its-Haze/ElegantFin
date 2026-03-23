# HazeFin

An opinionated Jellyfin theme, forked from [ElegantFin](https://github.com/lscambo13/ElegantFin) by lscambo13.

This is a personal fork with UI/UX changes that differ from the upstream project. It is not intended to be merged back.

**Author:** [Its-Haze](https://github.com/Its-Haze)

---

## Install

Paste the following in your Jellyfin **Custom CSS** box:

> Dashboard → Branding → Custom CSS

```css
@import url("https://cdn.jsdelivr.net/gh/Its-Haze/ElegantFin@main/Theme/haze.css");
```

---

## What's changed from ElegantFin

- **Detail page info block** (Genres, Studio, Writer) — label and value are now left-aligned next to each other instead of stretching across the full screen width
- Info block is constrained to fit its content rather than spanning the full page
- Genre list no longer wraps to a second line

---

## Development

The theme source lives in `Theme/haze.css`. It imports ElegantFin's nightly build as a base and applies overrides on top.

To make changes:
1. Edit `Theme/haze.css`
2. Commit and push to `main`
3. jsDelivr will serve the updated file (allow a few minutes for CDN cache to clear)
4. Hard refresh Jellyfin (`Ctrl+Shift+R`) to pick up the new styles

---

## Credits

- Base theme: [ElegantFin](https://github.com/lscambo13/ElegantFin) by lscambo13
