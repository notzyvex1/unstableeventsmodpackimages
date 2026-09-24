# Unstable Events Modpack — images

Images for the modpack's Modrinth and CurseForge pages. This repo exists only to host them:
both sites need absolute image URLs, and a relative path renders as a broken image.

## Layout

| Folder | What |
|---|---|
| `banner.gif` / `banner.png` | Page banner, animated and static |
| `logo.png` / `logo_large.png` | Wordmark, native and 8x |
| `headers/` | Section header images used by `DESCRIPTION.md` |
| `mod_icons/` | One icon per mod, taken from each mod's own jar |

## Using them

Images are served from:

```
https://raw.githubusercontent.com/notzyvex1/unstableeventsmodpackimages/main/<path>
```

For example:

```markdown
![Unstable Events Modpack](https://raw.githubusercontent.com/notzyvex1/unstableeventsmodpackimages/main/banner.gif)
```

`DESCRIPTION.md` already has every URL rewritten to point here — paste it straight into the
Modrinth or CurseForge description box after this repo is pushed and the images load.

> Push this repo first. The URLs only resolve once the files are on `main`.
