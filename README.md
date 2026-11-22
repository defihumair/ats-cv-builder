# ATS CV Builder

**Use it now:** https://defihumair.github.io/ats-cv-builder/

A free CV builder that runs entirely in your browser. Edit on the left, watch a live A4 preview on the right, and export a clean, ATS-friendly PDF. No sign-up, no server, no tracking.

## Why it's ATS-friendly

Applicant tracking systems read CVs as plain text. This builder produces the layout they handle best:

- **Single column.** No tables, text boxes or sidebars that scramble the reading order.
- **Standard section names**: Professional summary, Work experience, Skills, Education.
- **Real text in the PDF.** The export uses your browser's Save as PDF, so every word stays selectable and readable, not an image.
- **Clean formatting**: common fonts, simple bullets, dates aligned right.

## Private by design

There is no database. Your CV never leaves your device.

- **Autosave**: every change is saved in your own browser.
- **Backup file**: *Download PDF + data* gives you the PDF plus a small `.json` file with everything you typed.
- **Pick up later**: *Open saved CV (.json)* restores your work on any computer.

Keep the `.json` file with your PDF. Clearing your browser data removes the autosave, but never the file.

## How to use

1. Click **Start blank**, or edit the example CV.
2. Fill in each section. Use **Show** to hide a section and the arrows to reorder sections.
3. Wrap words in `**double stars**` inside a bullet, project or education detail to make them bold.
   - Start a bullet line with `## ` to add a sub-heading under a role (for example, a project name).
   - In a project name, put the tools after ` | ` (for example `Sales model | Power BI, SQL`); the tools appear in normal weight.
   - Tick **New page** on a section to start it on a fresh page.
4. Watch the page indicator. Dashed lines mark where page 2 begins.
5. Click **Download PDF + data**, choose **Save as PDF**, and turn off **Headers and footers**.

## Features

- Live A4 preview with page-break guides
- Sections for summary, experience, skills, education, projects, certifications and languages
- Add, remove and reorder entries and sections
- Sub-headings inside a role, and a **New page** option per section
- Education details on their own line, with bold support (good for coursework)
- Accent colour, text size and font options
- Built-in ATS tips
- Works offline: download `index.html` and open it in Chrome or Edge

## Run it locally

Download `index.html` and double-click it. Nothing to install.

## Tech

One HTML file: vanilla JavaScript and CSS, with no frameworks, no dependencies and no build step.

## Author

Muhammad Humair Qureshi · [LinkedIn](https://www.linkedin.com/in/biwithhumair) · [GitHub](https://github.com/defihumair)

Suggestions and pull requests are welcome.
