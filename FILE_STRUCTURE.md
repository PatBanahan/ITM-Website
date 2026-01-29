# ITM Website - File Organization Guide

## Folder Structure

```
ITM_Website/
│
├── index.html                 (landing page - rename itm_landing_page.html to this)
├── ITM_Logo_3D.glb           (3D logo file)
│
├── assets/
│   ├── videos/               (background video montage when you make it)
│   ├── fonts/                (custom "In The Moment" font)
│   └── images/               (any other images)
│
├── pages/
│   ├── music.html            (music page with streaming links)
│   ├── videos.html           (video grid/carousel)
│   ├── merch.html            (merch showcase)
│   ├── contact.html          (contact form/email)
│   └── about.html            (ITM bio/mission)
│
└── css/
    └── styles.css            (if we separate CSS later)
```

## Setup Instructions

1. **Create main folder:**
   - Make a folder on your desktop called `ITM_Website`

2. **Download these files to ITM_Website:**
   - itm_landing_page.html → RENAME to `index.html`
   - ITM_Logo_3D.glb → keep same name

3. **Create subfolders:**
   - Inside ITM_Website, create folders: `assets`, `pages`, `css`
   - Inside assets, create: `videos`, `fonts`, `images`

4. **Test it:**
   - Open `index.html` in your browser
   - Logo should spin!

## File Naming Rules

✅ GOOD:
- `index.html` (standard landing page name)
- `ITM_Logo_3D.glb`
- `music.html`
- `background_video.mp4`

❌ BAD:
- `itm landing page final FINAL v3.html` (spaces, redundant)
- `t ITM_Logo_3D.glb` (leading space)
- `music page.html` (space in filename)

**Rules:**
- No spaces (use underscores _ or hyphens -)
- All lowercase for web files
- Descriptive but concise
- No special characters

## Why This Matters

When you upload to a real web host later:
- `index.html` automatically loads as homepage
- Relative paths (`./ITM_Logo_3D.glb`) work everywhere
- Organized folders = easier to update/maintain
- Clean names = no broken links

## Next Steps (After Landing Page Works)

1. Build out pages folder (music, videos, merch, contact, about)
2. Add background video to assets/videos
3. Add custom font to assets/fonts
4. Link everything together

Keep it simple, keep it organized. Future you will thank present you!
