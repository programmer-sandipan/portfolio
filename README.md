🎓 Student Portfolio — AI & Python Projects
A single-file, fully responsive personal portfolio website for a B.Sc (Computer Science) student showcasing AI/ML projects, skills, and workshop experience. Built with pure HTML, CSS, and vanilla JavaScript — no frameworks required.

📸 Overview
This portfolio is designed for a 2nd-year student from Haldia Institute of Management who completed an AI/ML workshop and built real-world projects using Python, EDA, and Machine Learning. It includes a dark, glassmorphism-style UI with animated particle effects and smooth scroll interactions.

✨ Features

Animated particle canvas background — floating dots with gradient connector lines
Glassmorphism UI — translucent cards with subtle blur and gradient borders
Typing effect — rotating phrases in the hero section
Scroll-reveal animations — cards and sections fade in on scroll using IntersectionObserver
Scroll progress bar — fixed top bar showing page read progress
Sticky navigation header with backdrop blur
Mobile-responsive drawer menu — hamburger menu for screens under 920px
Smooth anchor scrolling — all internal links scroll smoothly
URL personalization — quickly swap student name and GitHub via query string params (?name=YourName&github=...)
Dynamic footer year — auto-updated via JavaScript


📁 File Structure
index.html          # Single self-contained file (HTML + CSS + JS)
README.md           # This file
All styles are embedded in a <style> block and all scripts in a <script> block — no external files needed beyond CDN assets.

🔗 External Dependencies (CDN)
ResourcePurposeFont Awesome 6.5Icons throughout the UI
No JavaScript frameworks. No build tools. No package manager.

🧩 Page Sections
SectionIDDescriptionHero(top)Name, tagline, typing animation, quick statsAbout#aboutWho I am, what I'm learning, mentorshipSkills#skillsPython, Pandas/EDA, Matplotlib/VisualizationProjects#projectsEDA Dashboard (Titanic) + House Price PredictionWorkshops#workshopArdent AI/ML Workshop, Code_ScholarEUContact#contactEmail, LinkedIn, Instagram, Mentor info

🛠️ Customization
All key links are defined in one central LINKS object at the top of the <script> block. Edit these before deploying:
jsconst LINKS = {
  githubProfile:   "https://github.com/programmer-sandipan",
  linkedin:        "https://linkedin.com/in/sandipan-maity-35447839a",
  project1Repo:    "https://github.com/your-username/project-1",
  project2Repo:    "https://github.com/your-username/project-2",
  project1Notebook:"https://colab.research.google.com/...",
  project2Notebook:"https://colab.research.google.com/...",
  email:           "sandipanmaity102@gmail.com"
};
Also update the following in the HTML:

Student name — replace Student Name in the <h1> tag
Institution details — update the nav brand subtitle (year, semester, college name)
About / Skills / Projects text — edit card paragraphs directly in the HTML


🖥️ Projects Showcased
Project 1 — EDA Dashboard (Titanic Dataset)

Loaded and explored a real dataset with Pandas
Handled missing values using mean/mode imputation
Created survival count, gender-vs-survival, and age distribution charts using Matplotlib
Summarized key insights in a presentation-ready notebook

Project 2 — House Price Prediction

Built a supervised ML model using scikit-learn Linear Regression
Applied train-test split for unbiased evaluation
Measured performance using RMSE and R² score
Visualized actual vs predicted prices and residual errors


🚀 Deployment
Since this is a single HTML file, deployment is trivial:
GitHub Pages:

Push index.html to a GitHub repository
Go to Settings → Pages and set source to the main branch
Your portfolio will be live at https://your-username.github.io/repo-name

Other options: Netlify drag-and-drop, Vercel, or any static file host.

📱 Responsive Breakpoints
BreakpointLayout change> 920pxFull desktop layout: multi-column grids, full nav≤ 920pxSingle-column layout, hamburger drawer menu

🎨 Color Palette
VariableValueUsage--accent#7C4DFFPrimary purple accent--accent2#00E5FFCyan accent / gradient end--good#00E676Success / highlight--bg0#070A12Page background start--txtrgba(255,255,255,.92)Primary text

👤 Author & Mentor

Student: Sandipan Maity — B.Sc (CS), 2nd Year, Haldia Institute of Management
GitHub: programmer-sandipan
LinkedIn: sandipan-maity-35447839a
Mentor: SK Sahil (AI Developer & Tutor) — Code_ScholarEU on Instagram


📄 License
This portfolio template is free to use and modify for personal educational use.
