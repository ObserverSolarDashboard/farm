# 🌿 Off-Grid Homestead Blueprint — Multi-Region Planning System

A comprehensive, interactive dashboard for planning a 1-acre off-grid homestead optimized for three western US locations: **Boise, Idaho**, **Prescott, Arizona**, and **Reno, Nevada**.

## 🔗 Live Demo

Visit: `https://YOUR-USERNAME.github.io/offgrid-farm-blueprint/`

*(Replace YOUR-USERNAME with your GitHub username after setup)*

## Features

- **🏔️ Multi-Location Support** — Toggle between Boise, Prescott, and Reno. All content dynamically adjusts: planting dates, frost schedules, soil amendments, water strategies, risk assessments, and location-specific tips.
- **🌙/☀️ Dark & Light Mode** — Full theme toggle with persistent preference storage.
- **🔤 Font Size Controls** — Four size settings (A−, A, A+, A++) for accessibility.
- **📱 Mobile Responsive** — Works on phones, tablets, and desktops.
- **🌱 Expandable Instructions** — Click any section for detailed step-by-step how-to guides covering every topic from coop construction to cheese making.

## Dashboard Tabs

| Tab | Contents |
|-----|----------|
| 🏡 Overview | Permaculture zone layout, priority order, detailed build instructions for all four zones |
| 🌱 Seed Vault | Heaven's Harvest heirloom vault + supplemental seeds with planting dates, harvest windows, and growing tips |
| 📅 Calendar | Month-by-month task list, filterable by month, with season extension build guides |
| 🐔 Livestock | Chickens, rabbits, Nigerian Dwarf goats — breeds, housing, feed, breeding, processing, health management |
| ⚡ Off-Grid | Water systems, food preservation (root cellar, canning, fermentation, dehydration), minimal solar, manual tools |
| 🛡️ Resilience | Location risk assessment, Davidson/ECDO framework positioning, skill timeline, Year 1 budget |

## Seed Sources

- **Heaven's Harvest** — Foundation vault (non-GMO, heirloom, open-pollinated)
- **Baker Creek Heirloom Seeds** — Specialty varieties, heritage corn, medicinals
- **Seed Savers Exchange** — Garlic, sunchokes, rare heirlooms
- **Territorial Seed Company** — Pacific Northwest adapted varieties

## How to Host on GitHub Pages (Free)

### Step 1: Create a GitHub Account
If you don't have one, go to [github.com](https://github.com) and sign up (free).

### Step 2: Create a New Repository
1. Click the **+** button in the top-right corner → **New repository**
2. Name it: `offgrid-farm-blueprint` (or whatever you prefer)
3. Set it to **Public**
4. Check **"Add a README file"** (optional — we'll replace it)
5. Click **Create repository**

### Step 3: Upload Files
1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop these two files:
   - `index.html` (the dashboard)
   - `README.md` (this file)
3. Click **"Commit changes"**

### Step 4: Enable GitHub Pages
1. Go to your repository **Settings** (gear icon)
2. In the left sidebar, click **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, select **main** and **/ (root)**
5. Click **Save**
6. Wait 1-2 minutes for deployment

### Step 5: Access Your Site
Your dashboard is now live at:
```
https://YOUR-USERNAME.github.io/offgrid-farm-blueprint/
```

## File Structure

```
offgrid-farm-blueprint/
├── index.html    ← The complete dashboard (single file, self-contained)
└── README.md     ← This documentation file
```

The entire dashboard is a **single HTML file** with all CSS and JavaScript inline. No build tools, no npm, no frameworks, no external dependencies beyond Google Fonts. It works offline once loaded (fonts degrade gracefully to system fonts).

## Frameworks & Preparedness

This dashboard integrates:
- **Ben Davidson's Solar Micronova / Disaster Cycle** research for geomagnetic resilience planning
- **The Ethical Skeptic's ECDO** (Exothermic Core-Mantle Decoupling) theory for geographic positioning
- **MECMUS-2026** (Munch & Grayver) magnetotelluric conductivity data for bedrock assessment
- Conventional agricultural best practices for each hardiness zone

## Tech Stack

- Pure HTML5, CSS3, JavaScript (ES6+)
- IBM Plex Sans & IBM Plex Mono typography
- CSS custom properties for theming
- Zero external dependencies (besides Google Fonts)
- No build step required

## License

Personal use. Not financial, agricultural, or investment advice. Verify all planting dates, regulations, and water rights with local authorities before implementation.

---

*Built March 2026 · Data from USDA, University Extension offices, state water resource agencies, and peer-reviewed geological research.*
