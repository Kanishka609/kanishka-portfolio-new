
# Kanishka Raswal — CV / Portfolio Website

Live site: https://Kanishka609.github.io/kanishka-portfolio-new/  
Repository: https://github.com/Kanishka609/kanishka-portfolio-new

A modern, responsive, dark-purple CV website built with HTML + CSS.  
Designed to be clean, accessible, and easy to maintain. Content maps directly to my CV.

✨ Features
- Polished, professional design (Space Grotesk headings, Inter body)
- Responsive layout (desktop → mobile)
- Accessible structure (semantic sections, good contrast)
- Zero build tools — just static files (fast to host on GitHub Pages)
- CV PDF included and linked from the header & contact section

🗂 Project Structure
kanishka-portfolio-new/
├─ index.html # Single-page site
└─ assets/
├─ css/
│ └─ style.css # Theme, layout, components
├─ img/
│ └─ hero_graphic.png # Hero graphic (replace with your own if desired)
└─ cv/
└─ Kanishka_Raswal_CV.pdf

Sections in `index.html`:
- Hero (headline, key skills chips, CTA)
- Quick Facts strip (education, languages, certificates, status)
- Experience
- Education
- Skills
- Certificates
- Languages
- Interests
- Contact + Download CV

🛠Edit Content (quick guide)
#1) Hero headline
In `index.html`, find:
```html
<h1><span class="muted">Hardworking</span> Problem Solver</h1>
Change the text as needed (keep the <span class="muted">…</span> to preserve the pink accent).
2) Email & CV
•	Update email links in Hero and Contact sections:
mailto:raswalkanishka@gmail.com
•	Replace your PDF at assets/cv/Kanishka_Raswal_CV.pdf (keep the same filename or update the link in HTML).
3) Experience / Education / Skills
•	Edit list items and dates directly in their sections.
•	Add or remove chips by duplicating/removing:
<span class="chip">Teamwork</span>
4) Hero graphic or photo
•	Replace assets/img/hero_graphic.png with your own image (900×1100 recommended).
•	Alt text example:
<img src="assets/img/hero_graphic.png" alt="Monogram emblem for Kanishka Raswal" />
🎨 Styling & Theme (tokens you can tweak)
In assets/css/style.css, top variables control the theme:
:root{
  --primary:#8B5CF6;     /* violet */
  --primary-2:#F472B6;   /* pink accent */
  --text:#F8FAFC;        /* text color on dark */
  --muted:#CBD5E1;       /* secondary text */
  --border:#2B2247;      /* subtle borders */
  --maxw:1150px;         /* page width */
  --radius:18px;         /* card rounding */
  --space-...            /* 8px spacing scale */
}
Change these to adjust colors, spacing, and radii globally.
▶ Preview Locally
No build step required:
•	Double-click index.html, or
•	Use a simple static server, e.g. VS Code’s “Live Server” extension.
🚀 Deploy (GitHub Pages)
1.	Push to this repo (branch: master or main).
2.	Repo Settings → Pages
Source: Deploy from a branch
Branch: master (or main) — Folder: /(root) → Save
3.	Site URL: https://Kanishka609.github.io/kanishka-portfolio-new/
Changes go live automatically after each push.
✅ Quality Checklist (useful for the report)
•	Alignment & spacing: content aligns to the same left guide; 8-px spacing scale used consistently.
•	Typography: headings (Space Grotesk) + body (Inter); readable line length.
•	Contrast & accessibility: sufficient color contrast; semantic headings; alt text on images; nav has clear labels.
•	Performance: images optimized (≤150 KB where possible); fonts loaded with display=swap.
•	Links: section anchors work; Download CV opens the PDF.
Micro-evidence to capture (for justification)
•	Image compression before/after (file sizes).
•	Quick contrast/accessibility check notes.
•	1-person usability check (“Could they find Certificates on mobile?”).

