# hive-readme-badge

[![Hive](./badge.png)](https://hive.io/)

Static SVG badge for GitHub README files: **Hive** label, brand colors, and the Font Awesome Hive brands glyph (see [NOTICE](NOTICE)).

Inspired by the pattern described in [Adding Custom GitHub Badges to Your Repo](https://css-tricks.com/adding-custom-github-badges-to-your-repo/) (badges are remote images; GitHub may cache them for several minutes).

## Canonical image URLs

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
