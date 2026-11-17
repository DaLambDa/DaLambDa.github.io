# Website and CV workflow

When Da Fan supplies new professional information, update both the latest CV and the corresponding website pages in the same task.

- Local website: `Website/`; latest CV source: `CV/20261117/` (as of 17 November 2026).
- GitHub repository: https://github.com/DaLambDa/DaLambDa.github.io, branch `main`.
- Website files map to the repository root. Editable CV files map to `CV/20261117/`.
- Preserve earlier local dated CV snapshots. If creating a new dated version, update the latest-version pointer in `CV/README.md`.
- Use only information supplied or confirmed by Da Fan. Preserve his plain academic English and the existing visual style.
- Update the relevant CV sections and website pages (research, talks, teaching, appointments, education, service, contact).
- Rebuild the CV with XeLaTeX twice, inspect the result, and copy the final PDF to `Website/cv.pdf`. The two PDFs must be byte-identical.
- Update the CV date and website download caption when appropriate. Check internal website links and factual consistency.
- Submit related website, PDF, and CV source changes together to GitHub when requested. Do not assume future editing requests authorize publication unless that authorization is explicit in the conversation.
- Exclude obsolete CV snapshots, standalone private documents, macOS metadata, and TeX build byproducts from GitHub.
- Preserve existing Pages and domain settings unless Da Fan requests a change.
