# KM Ultimate — Official Site 🥏

Website of **Kid Mafia Ultimate · Laguna** — a community developing ultimate frisbee players across Laguna.

**Live site:** https://YOUR-USERNAME.github.io/km-ultimate/  ← update after publishing

## Pages
| Page | Path |
|---|---|
| Main site (Welcome / About / Training / People) | `/index.html` |
| Beginner's Playbook (interactive guide) | `/beginners-playbook/` |

## Publishing (GitHub Pages)
1. Create a repo named `km-ultimate`
2. Upload this whole folder's contents (keeping the `beginners-playbook` subfolder) to `main`
3. Settings → Pages → Source: `main` → Save
4. Live at `https://YOUR-USERNAME.github.io/km-ultimate/`

## Adding committee photos
Each person card contains an SVG placeholder avatar. Replace it with:
```html
<img src="photos/name.jpg" alt="Name" style="width:100%;height:100%;object-fit:cover;">
```
inside that card's `.avatar` div.

## Stack
Single-file HTML/CSS/JS pages — no build step, no dependencies.
