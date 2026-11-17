# Website and CV workflow

When Da Fan supplies new professional information, update the latest CV and corresponding website pages in the same task.

- Local website: `Website/`; latest CV: `CV/20261117/` (17 November 2026).
- Public website repository: https://github.com/DaLambDa/DaLambDa.github.io, branch `main`. Local `Website/` maps to its root.
- Private editable CV repository: https://github.com/DaLambDa/academic-cv, branch `main`. Local `CV/` maps to its root; latest source is `20261117/`.
- Keep editable CV source, references, unused drafts, and historical CV snapshots out of the public website repository. Publish only the compiled `cv.pdf` alongside website assets.
- Preserve older local dated CV snapshots. Update `CV/README.md` if the latest dated version changes.
- Use only information supplied or confirmed by Da Fan; preserve his plain academic English and the existing website style.
- Update relevant CV sections and website pages together. Build changed CV source with XeLaTeX twice, inspect the PDF, and copy it to `Website/cv.pdf`; both PDFs must be byte-identical.
- Check website links and factual consistency. Update dates when appropriate.
- When submission is requested, push CV source changes to the private repository and website/PDF changes to the public repository, with related commit messages. Editing alone does not authorize publication.
- Exclude macOS metadata and TeX build byproducts. Preserve Pages, CNAME, domain, and HTTPS settings.
- Fetch current remote branches before pushing; preserve concurrent changes and never force-push without explicit authorization.
- The local `github-upload/` directory is an obsolete staging snapshot. Do not publish it.
