# Bhavith Reddy — Cricket Profile

## WHERE TO UPDATE STATS

Open `index.html` in Notepad or any text editor.

All stats are written directly in the HTML — no JavaScript tricks.
Search for the value you want to change using Ctrl+F.

### Common updates:

| What to change | Search for this in the file |
|---|---|
| Highest Score | `78*` |
| Half Centuries | `<div class="sval">6</div>` under Half Centuries |
| Man of Match count | `<div class="sval g">7</div>` under Man of Match |
| Add a new match to Recent Form | Copy one `<tr>...</tr>` block inside `<tbody>` |
| Add a new tournament | Copy the `<div class="tblock">` section |
| Contact email/phone | Near the bottom, find `your.email@gmail.com` |
| Last updated date | Find `Last updated: June 2025` |

---

## HOW TO DEPLOY FREE FOREVER (GitHub Pages)

1. Create a free account at https://github.com
2. Click "New repository" → name it `bhavith-cricket` → set to Public → Create
3. Click "Add file" → "Upload files" → drag `index.html` → Commit
4. Go to Settings → Pages → Source: Deploy from branch → Branch: main → Save
5. Your link will be: `https://YOUR-USERNAME.github.io/bhavith-cricket`

**This link works forever for free.**

## HOW TO UPDATE STATS LATER

1. Edit `index.html` on your computer
2. Go to your GitHub repo
3. Click on `index.html` → click the pencil (edit) icon → paste your new code → Commit
   OR: drag and drop the new file to replace it
4. The same link automatically shows the new stats within 1-2 minutes.
