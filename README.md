# hive-readme-badge

**Self-hosted** (this repo): [![Hive](./badge.png)](https://hive.io/)

**Shields.io** (same palette + [Simple Icons](https://simpleicons.org/) bee): [![Hive (Shields.io)](https://img.shields.io/static/v1?label=Hive&message=hive.io&color=E31337&labelColor=212529&logo=hive_blockchain&logoColor=white&style=flat)](https://hive.io/)

Static badge assets for GitHub READMEs: **Hive** label, Hive Black `#212529` and Hive Red `#E31337` ([hive.io/brand](https://hive.io/brand)). The self-hosted SVG uses the Font Awesome brands glyph (see [NOTICE](NOTICE)).

Inspired by the pattern described in [Adding Custom GitHub Badges to Your Repo](https://css-tricks.com/adding-custom-github-badges-to-your-repo/) (badges are remote images; GitHub may cache them for several minutes).

## Shields.io ([Static Badge](https://shields.io/badges/static-badge))

Use Shields when you want the usual OSS badge look (~20px tall `flat` style), no files to host, and a logo from **Simple Icons** (`logo` query — slug from [slugs list](https://github.com/simple-icons/simple-icons/blob/master/slugs.md)). For Hive **blockchain**, the slug is **`hive_blockchain`** (there is also a `hive` entry; pick the icon you want on [simpleicons.org](https://simpleicons.org/)).

**Canonical URL** (tweak `style` if you like: `flat-square`, `plastic`, `for-the-badge`, `social`):

```
https://img.shields.io/static/v1?label=Hive&message=hive.io&color=E31337&labelColor=212529&logo=hive_blockchain&logoColor=white&style=flat
```

**Markdown** (clickable → hive.io):

```markdown
[![Hive](https://img.shields.io/static/v1?label=Hive&message=hive.io&color=E31337&labelColor=212529&logo=hive_blockchain&logoColor=white&style=flat)](https://hive.io/)
```

**Markdown** (clickable → developers.hive.io — short message keeps width reasonable):

```markdown
[![Hive](https://img.shields.io/static/v1?label=Hive&message=docs&color=E31337&labelColor=212529&logo=hive_blockchain&logoColor=white&style=flat)](https://developers.hive.io/)
```

**Markdown** (“Powered by” on the right — `message` is URL-encoded spaces):

```markdown
[![Powered By Hive](https://img.shields.io/static/v1?label=Hive&message=Powered%20By%20Hive&color=E31337&labelColor=212529&logo=hive_blockchain&logoColor=white&style=flat)](https://hive.io/)
```

**Path-style** equivalent (label, message, color in the path — see Shields docs for `_` / `--` escaping):

```
https://img.shields.io/badge/Hive-hive.io-E31337?labelColor=212529&logo=hive_blockchain&logoColor=white&style=flat
```

| Approach | Notes |
|----------|--------|
| **Shields** | Standard dimensions; SVG served by Shields; logo from Simple Icons. |
| **Self-hosted** `badge.png` / `badge.svg` | Full control (e.g. 128×32, Font Awesome path); you maintain the repo. |

## Canonical image URLs (self-hosted)

Replace `main` with your default branch if different.

**PNG** (most reliable in GitHub READMEs; proxied without SVG quirks):

```
https://raw.githubusercontent.com/hiveuprss/hive-readme-badge/main/badge.png
```

**SVG** (vector; avoid `clip-path` / `url(#…)` if you fork the art):

```
https://raw.githubusercontent.com/hiveuprss/hive-readme-badge/main/badge.svg
```

If you fork this repo, swap `hiveuprss` / repo name in your README snippets.

## Markdown (links to hive.io)

```markdown
[![Hive](https://raw.githubusercontent.com/hiveuprss/hive-readme-badge/main/badge.png)](https://hive.io/)
```

## Markdown (developer docs)

```markdown
[![Hive](https://raw.githubusercontent.com/hiveuprss/hive-readme-badge/main/badge.png)](https://developers.hive.io/)
```

## HTML equivalent

```html
<a href="https://hive.io/" title="Hive blockchain">
  <img
    src="https://raw.githubusercontent.com/hiveuprss/hive-readme-badge/main/badge.png"
    alt="Hive"
    width="128"
    height="32"
  />
</a>
```

## Preview in this repo

The live badge above uses **`./badge.png`** so it renders reliably on GitHub (SVG badges are often broken by the image proxy when they use internal `url(#id)` references). **Other repositories** should use the absolute `raw.githubusercontent.com/.../badge.png` URL unless you know SVG works for your case.

Vector source: `./badge.svg` (regenerate `badge.png` after editing the SVG, e.g. `magick badge.svg PNG32:badge.png`).

## See also

- [hive.io/brand](https://hive.io/brand) — official colors and logo package
- [developers.hive.io](https://developers.hive.io) — developer documentation
