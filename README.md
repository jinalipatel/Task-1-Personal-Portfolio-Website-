# Full Stack Web Development - Assignment 1

Assignment 1 for the course **Full Stack Web Development** (Code: 1010043350), School of Technology, Design & Computer Application, College of Technology.

---

## How to Run

### Option 1: Double-click `run.bat`
Opens both pages in your default browser.

### Option 2: Open directly in browser
Double-click `index.html` (Portfolio) or `event\index.html` (Event) in File Explorer.

Requires internet for Tailwind CSS CDN.

---

## Task 1: Personal Portfolio Website

**Tech Stack:** HTML5 + Tailwind CSS

**Location:** `index.html` (root)

**Link (when deployed):** `https://<username>.github.io/<repo-name>/`

### Features
- Responsive navigation with mobile menu
- Hero, About, Skills, Projects, and Contact sections
- Modern design with Tailwind CSS
- Smooth scrolling and gradient accents

---

## Task 2: Event Landing Page

**Tech Stack:** Tailwind CSS (responsive)

**Location:** `event/index.html`

**Link (when deployed):** `https://<username>.github.io/<repo-name>/event/`

### Features
- Responsive event landing page for college tech fest
- Event details, schedule, and highlights
- Hero, About, Schedule, Highlights, and Register sections
- Mobile-friendly layout

---

## Deploying to GitHub Pages

### Option A: One Repository (Both Tasks)

1. **Create a new GitHub repository**
   - Name it something like `fullstack-assignment-1` or `portfolio-event`

2. **Push this project**
   ```bash
   git init
   git add .
   git commit -m "Assignment 1: Portfolio & Event Landing Page"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to repo **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: **main**, folder: **/ (root)**
   - Save

4. **Your links:**
   - **Task 1:** `https://YOUR_USERNAME.github.io/YOUR_REPO/`
   - **Task 2:** `https://YOUR_USERNAME.github.io/YOUR_REPO/event/`

### Option B: Two Separate Repositories

For completely separate links:

**Task 1 Repository:**
- Put only `index.html` (and any shared assets) in the repo root
- Enable GitHub Pages
- Link: `https://YOUR_USERNAME.github.io/portfolio/`

**Task 2 Repository:**
- Put the `event/` folder contents in the repo root (so `index.html` is at root)
- Enable GitHub Pages
- Link: `https://YOUR_USERNAME.github.io/tech-fusion-event/`

---

## Submission

Submit your assignment at: [Google Form Link](https://forms.gle/3PEgu2q1qo1GVi1v8)

- **Task 1 Link:** Your Personal Portfolio GitHub Pages URL
- **Task 2 Link:** Your Event Landing Page GitHub Pages URL
