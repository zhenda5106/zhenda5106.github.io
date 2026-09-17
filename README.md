# Ziyang Huang — Academic Portfolio

A static, multi-page academic website built with HTML and CSS for GitHub Pages. No JavaScript, dependencies, or build step is required for the website.

## Pages

- `index.html`: profile image, identity, and introduction.
- `academics.html`: university, faculty, college, program, and current coursework.
- `interests.html`: developing academic and research interests.
- `projects.html`: double-pendulum project, AI-assisted development disclosure, and external GitHub repository link.
- `cv.html`: honest placeholder until a CV PDF is supplied.
- `contact.html`: university email and existing GitHub profile.
- `style.css`: shared layout, typography, navigation, and responsive styles.

Open `index.html` directly in your browser. Internal page and asset links are relative and work locally and on GitHub Pages. Each page contains the same navigation, with `aria-current="page"` indicating the active link. If changing navigation labels or links, update all six pages.

## Assets and updates

The homepage uses the supplied `assets/profile.jpg` at its original aspect ratio. Replace that file to update the avatar. If the dimensions change, update the image width and height attributes in `index.html`.

Add your real CV at `assets/Ziyang_Huang_CV.pdf`. Replace the placeholder section in `cv.html` with the link shown in its HTML comment. Optionally change the CV link in all six navigation bars to point directly to the PDF.

The Contact page uses `ziyang.huang@mail.utoronto.ca` and `https://github.com/zhenda5106`.

The simulation is maintained in the separate [Double Pendulum Numerical Simulation repository](https://github.com/zhenda5106/double-pendulum-simulation). This website only links to that repository and does not require any of its source files, figures, or Python dependencies. The project link opens in a new tab with `rel="noopener noreferrer"`. The project metadata includes “AI-assisted · Vibe-coded” and a concise development note.

## GitHub Pages

Keep the six HTML pages, `style.css`, `.nojekyll`, and assets in the published directory. The `.nojekyll` file tells GitHub Pages to serve files directly instead of transforming them with Jekyll. No simulation project directory or website build workflow is necessary.

All work remains local until you choose to commit and push. Notes are intentionally omitted.
