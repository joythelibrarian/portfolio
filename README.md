# Joy Kim — Portfolio Site (v2)

Updated portfolio for the City College of San Francisco Tenure-Track Librarian interview.

## 📁 What's in this folder

```
portfolio/
├── index.html              ← the entire site (all styles embedded)
├── assets/
│   ├── pdfs/               ← 14 instructional slide deck PDFs
│   ├── images/             ← 2 RPG workshop screenshots
│   └── docs/               ← 1 misc document (CORE Assist Forum)
└── README.md               ← this file
```

Everything else (PSU videos, PCC ESOL Google Slides, iSpring course, SCU, CSU East Bay, Gentrification Unit, Media Literacy Workshop, SJSU e-portfolio, Milpitas, Las Lomas) is linked directly to Google Drive, YouTube, and other sources.

## 🔁 What changed from v1

- **Tabs consistency** — "Berkeley CC" matches "Portland CC"
- **BCC section:** added Role-Playing Game Workshop (with 2 photos + APA citation), updated file names
- **PQA Workshop** moved from BCC → Misc. Teaching (labeled "College Track")
- **PSU section:** added McNair Scholars slide deck, ANTH 412/512 research guide citation, LibGuides Peer Review citation
- **PCC section:** added ESR 171 teaching demo, ESOL 30: Analyzing a Graph
- **Misc. Teaching:** added Gentrification Unit (Google doc), CORE Assist Forum PDF
- **Other Work:** working links now in for Milpitas High (`mhslibrary.musd.org/home`) and Las Lomas (`auhsd.libguides.com/LLHS_Library/literacy`); added Media Literacy Workshop link under Las Lomas
- **Footer:** simplified to "Portfolio · 2026"

## 🚀 Replacing the old files on GitHub

If your repo already has old files from v1, the cleanest approach:

### Option A — Delete old repo, start fresh (recommended)
1. On GitHub, go to your repo → **Settings** → scroll to the bottom → **Delete this repository**
2. Create a new repo with the same name (`portfolio`)
3. Upload the contents of this v2 folder (see steps below)
4. Turn on Pages again (Settings → Pages → main branch → Save)
5. Your URL stays the same: `https://YOUR-USERNAME.github.io/portfolio/`

### Option B — Replace files in the existing repo
1. Delete old files: navigate to each old file/folder in GitHub, click the trash icon, commit
2. Upload the new files the same way you did before

## 📤 Upload steps (for a fresh repo)

1. **Upload batch 1** — the HTML + README:
   - At repo root, click **Add file** → **Upload files**
   - Drag `index.html` and `README.md`
   - Commit

2. **Upload batch 2** — the PDFs (in 3 smaller groups of ~5 to avoid upload errors):
   - Click **Add file** → **Upload files**
   - In the path text box at top, type `assets/pdfs/` (or navigate into the folder first)
   - Drag ~5 PDFs at a time, commit each batch

3. **Upload batch 3** — the images:
   - Navigate to (or type path) `assets/images/`
   - Drag both `rpg-1.jpg` and `rpg-2.jpg`, commit

4. **Upload batch 4** — the misc docs:
   - Navigate to (or type path) `assets/docs/`
   - Drag `CORE-Assist-Forum.pdf`, commit

5. **Turn on Pages:** Settings → Pages → Source: Deploy from a branch → main → / (root) → Save

6. Wait ~2 minutes, then visit `https://YOUR-USERNAME.github.io/portfolio/`

## ✏️ Editing later

Edit `index.html` directly on GitHub: click the file → pencil icon → edit → Commit changes. Site updates in ~1 minute.

### Adding new entries
1. Find the section in `index.html` (e.g., `<!-- BERKELEY CITY COLLEGE -->`).
2. Copy an existing `<article class="card">…</article>` block.
3. Paste it inside the same `<div class="card-grid">` and edit the tag, title, description, and link.

### Adding a photo to the hero section
1. Put your photo in `assets/images/` (e.g., `joy.jpg`)
2. In `index.html`, find `<div class="hero-eyebrow">PORTFOLIO · 2026</div>`
3. Just above it add:
   ```html
   <img src="assets/images/joy.jpg" alt="Joy Kim"
        style="width:120px;height:120px;border-radius:50%;object-fit:cover;margin-bottom:24px;border:4px solid var(--cream);box-shadow:var(--shadow-md);">
   ```

Good luck with the interview!
