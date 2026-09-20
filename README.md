# Ziyang Huang — Academic Portfolio

A static, multi-page academic website built with HTML and CSS for GitHub Pages. No JavaScript, dependencies, or build step is required for the website.

## Pages

- `index.html`: profile image, identity, and introduction.
- `academics.html`: university, faculty, college, intended programs, current coursework, and explicitly planned Winter 2027 courses.
- `interests.html`: three levels of developing interests and long-term learning goals, rather than established research specialties.
- `projects.html`: double-pendulum project, AI-assisted development disclosure, and external GitHub repository link.
- `cv.html`: Academic CV introduction and a PDF download link that opens in a new tab.
- `contact.html`: university email and existing GitHub profile.
- `style.css`: shared layout, typography, navigation, and responsive styles.

Open `index.html` directly in your browser. Internal page and asset links are relative and work locally and on GitHub Pages. Each page contains the same navigation, with `aria-current="page"` indicating the active link. If changing navigation labels or links, update all six pages.

## Assets and updates

The homepage uses the supplied `assets/profile.jpg` at its original aspect ratio. Replace that file to update the avatar. If the dimensions change, update the image width and height attributes in `index.html`.

The supplied one-page Academic CV is at `assets/Ziyang_Huang_Academic_CV.pdf`. The download link in `cv.html` opens the PDF in a new tab with `target="_blank"` and `rel="noopener noreferrer"`. Replace that file when updating the CV.

Current coursework has been corrected from the previously incorrect calculus entry to MAT148H1 — Algebraic Structures and Number Theory, alongside MAT223H1, PHY151H1, and CSC108H1. MAT149H1, MAT224H1, and PHY152H1 are listed only as planned Winter 2027 coursework. Physics Specialist and Mathematics Major are intended programs.

The Contact page uses `ziyang.huang@mail.utoronto.ca` and `https://github.com/zhenda5106`.

The simulation is maintained in the separate [Double Pendulum Numerical Simulation repository](https://github.com/zhenda5106/double-pendulum-simulation). This website only links to that repository and does not require any of its source files, figures, or Python dependencies. The project link opens in a new tab with `rel="noopener noreferrer"`. The Development Note explicitly discloses substantial AI-assisted coding using Codex, describes the project as a structured learning activity, and explains the ongoing goal of understanding and extending the derivation and implementation independently. A limitation clarifies that nearby trajectory divergence alone does not formally measure chaos or a Lyapunov exponent.

## GitHub Pages

Keep the six HTML pages, `style.css`, `.nojekyll`, and assets in the published directory. The `.nojekyll` file tells GitHub Pages to serve files directly instead of transforming them with Jekyll. No simulation project directory or website build workflow is necessary.

All work remains local until you choose to commit and push. Notes are intentionally omitted.
