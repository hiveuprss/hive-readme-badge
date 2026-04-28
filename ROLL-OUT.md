# Rolling the badge into other READMEs

1. Pick **one** snippet: [Shields.io static badge](https://shields.io/badges/static-badge) (no hosting) **or** self-hosted `badge.png` / `badge.svg` from this repo (or your fork).
2. Add a **single line** after the project title or intro paragraph.

**Shields.io** (Simple Icons slug `hive_blockchain`, Hive palette):

```markdown
[![Hive](https://img.shields.io/static/v1?label=Hive&message=hive.io&color=E31337&labelColor=212529&logo=hive_blockchain&logoColor=white&style=flat)](https://hive.io/)
```

**Self-hosted PNG** (GitHub README–friendly raster):

```markdown
[![Hive](https://raw.githubusercontent.com/hiveuprss/hive-readme-badge/main/badge.png)](https://hive.io/)
```

## Suggested follow-up PR targets

Use the same snippet; adjust the link destination per audience (`hive.io` vs `developers.hive.io`).

| Repository | Notes |
|------------|--------|
| [openhive-network/dhive](https://github.com/openhive-network/dhive) | JS client; high visibility |
| [openhive-network/hive](https://github.com/openhive-network/hive) | Core `hive` repo (README may be more formal — coordinate with maintainers) |
| [waxwax/wax](https://github.com/waxwax/wax) | Wax transaction library |

Replace `hiveuprss` in the image URL if the canonical badge moves to an org-owned repo.
