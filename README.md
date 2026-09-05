# 🌌 AWDD FontAwesome Widget Pack
A cyber‑minimal, atmospheric UI component pack built using the AWDD palette:

- **#0D1C38** (navy)
- **#2BABD9** (aqua)
- **#6A5976** (violet)
- **#C53A65** (rose)
- **#0B0C1D** (black)
- **#CDA95F** (gold)

This pack includes reusable HTML/CSS widgets designed for dashboards, creative OS systems, worldbuilding tools, and Notion embeds.  
All components use FontAwesome 6 and the Inter typeface.

---

## 📁 Folder Structure

awdd-fa-widget-pack/
│
├── core/
│   ├── base.css
│   ├── colors.css
│   ├── fonts.css
│   └── fa-import.html
│
├── widgets/
│   ├── navigation/
│   ├── icons/
│   ├── headers/
│   ├── sections/
│   └── badges/
│
├── notion-optimized/
│   ├── notion-base.css
│   ├── index.md
│   └── README.md
│
└── icons/
├── character-icons.json
├── lore-icons.json
├── faction-icons.json
├── arc-icons.json
└── trait-icons.json


---

## 🎨 Core Files

### `colors.css`
Defines AWDD palette variables for consistent styling.

### `base.css`
Shared resets, spacing utilities, and layout rules.

### `fonts.css`
Imports Inter and applies global font rules.

### `fa-import.html`
FontAwesome 6 CDN import.

---

## 🧩 Widget Categories

### **Navigation**
- `nav-button.html`
- `nav-button.css`
- Notion version included

### **Icons**
- `icon-button.html`
- `icon-button.css`
- Notion version included

### **Headers**
- `header-bar.html`
- `header-bar.css`
- Notion version included

### **Sections**
- `section-label.html`
- `section-label.css`
- Notion version included

### **Badges**
- `badge-success.html`
- `badge-warning.html`
- `badge-danger.html`
- `badges.css`
- Notion versions included

---

## 🧬 Notion-Optimized Versions

Notion embeds compress padding, restrict width, and clip overflow.  
The `/notion-optimized/` folder contains:

- simplified gradients  
- tighter spacing  
- embed-safe borders  
- reduced radii  
- overflow protection  

Use these versions when embedding widgets into Notion.

---

## 📘 Icon JSON Sets

The `/icons/` folder contains structured JSON lists of recommended FontAwesome icons for:

- Characters  
- Lore  
- Factions  
- Arcs  
- Traits  

Each file includes AWDD palette metadata and icon color assignments.

---

## 🚀 How to Use

### **Local Development**
Open any widget HTML file in your browser.

### **Embedding in Notion**
1. Host this repo on GitHub Pages, Netlify, or Vercel.  
2. Open any `*-notion.html` file.  
3. Copy the public URL.  
4. Paste into Notion → “Create Embed”.

### **Customization**
All widgets use:
- AWDD palette variables  
- Inter font family  
- FontAwesome 6 icons  

You can adjust colors globally via `core/colors.css`.

---

## 🛠️ Requirements

- FontAwesome 6 (CDN included)
- Inter font (Google Fonts)
- Any static hosting provider for Notion embeds

---

## 💛 Credits

Designed for AWDD OS aesthetic system — cyber‑minimal, atmospheric, and beautifully structured.

