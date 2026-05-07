# Mechanical Engineer Portfolio Website

This repository contains a clean, single-page portfolio template tailored for a **mechanical engineer**.

## 1) Recommended Website Structure

Use this section order (already mapped in `index.html`) so recruiters can quickly evaluate your profile:

1. **Hero** (`#hero`)  
   Name, role, one-line value proposition, CTA button.
2. **About** (`#about`)  
   Short bio + engineering focus + tools.
3. **Technical Skills** (`#skills`)  
   Group by CAD, Analysis, Manufacturing, and Other.
4. **Projects** (`#projects`)  
   4–6 project cards with image, your role, tools, and measurable impact.
5. **Experience & Education** (`#experience`)  
   Timeline format for work history and degree.
6. **Contact** (`#contact`)  
   Email, LinkedIn, optional GitHub/Behance/GrabCAD.

---

## 2) How to Customize This Template

### Step A — Basic Identity
Edit `index.html`:
- Replace `YourName` in the logo and hero section.
- Replace `Mechanical Design Engineer` with your exact title (example: `Mechanical Engineer | Product Development`).
- Update the short hero statement.

### Step B — About + Tools
In the About section:
- Replace placeholder bio with 4–6 lines focused on:
  - industries (automotive, HVAC, aerospace, etc.)
  - strengths (DFM, FEA, tolerance stack-up, prototyping)
  - outcomes (cost, weight, reliability improvements)
- Update tools list to your real stack.

### Step C — Skills
In the Skills section:
- Keep categories but replace list items with your strongest, job-relevant skills.
- Prioritize skills that appear in target job descriptions.

### Step D — Projects (Most Important)
For each project card in `#projects`, include:
- **Project title**
- **Problem** (1 sentence)
- **Your role**
- **Tools used**
- **Result with numbers** (example: “Reduced weight by 18%”)

Add real images:
- Replace `placeholder1.jpg`, `placeholder2.jpg`, etc. with files in repo root or `assets/` folder.
- Keep image names simple (e.g., `pump-housing-redesign.jpg`).

### Step E — Experience & Education
Use concise bullet-style statements of impact:
- "Designed X assemblies used in Y product line"
- "Cut prototype iteration cycle from A weeks to B weeks"

### Step F — Contact Links
Update the Contact section:
- Correct email
- Real LinkedIn URL
- Optional GitHub/portfolio links

---

## 3) Styling / Theme Customization

Edit `styles.css`:
- **Primary color:** search `#1f78d1`
- **Hero background:** search `#0b3954`
- **Font:** update Google Font in `index.html` and `font-family` in CSS
- **Layout spacing:** modify `section { padding: ... }`

Suggested professional palette:
- Navy: `#0B1F3A`
- Steel blue: `#1F4E79`
- Accent cyan: `#2CA6A4`
- Light gray background: `#F5F7FA`

---

## 4) Publish on GitHub Pages

Because this repository is named `<username>.github.io`, it is a **User Site** and deploys from the default branch root.

### One-time setup
1. Push this repo to GitHub under your account.
2. In GitHub: **Settings → Pages**.
3. Under **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main` (or your default branch), folder `/ (root)`
4. Save.

### Deploy updates
After each edit:
```bash
git add .
git commit -m "Update portfolio content"
git push
```
GitHub Pages will auto-publish in ~1–3 minutes.

Your live URL will be:
`https://<your-github-username>.github.io/`

---

## 5) Recommended Content Checklist

Before sharing your website, verify:
- [ ] Real name and role shown at top
- [ ] At least 3 strong projects with measurable outcomes
- [ ] Contact links work
- [ ] Mobile menu works
- [ ] No placeholder text remains
- [ ] Spelling and grammar checked

---

## 6) Optional Next Improvements

- Add a downloadable resume button in Hero.
- Add project detail pages (`project-1.html`, etc.)
- Add favicon and SEO tags (`meta description`, Open Graph tags).
- Add a small "Process" section (concept → CAD → simulation → prototype → validation).
