# Ziji Sheng · Academic Website

Live website: https://sziji.github.io/

Bilingual academic website adapted from al-folio. English: `index.html`; Chinese: `zh.html`.
Includes selected publications, ongoing research, education, projects, industry experience, honors, and patents. No transcripts are published. NeurIPS BibTeX is intentionally omitted until final metadata are ready.

## Maintenance

The public site consists of the HTML, CSS, JavaScript, portrait, and two CV PDF files in this repository. Source and the optional al-folio/Jekyll version are in `website-source.zip`. The source uses an `assets/` directory; this deployment flattens those asset paths for upload.

When rebuilding the source, replace `assets/img/`, `assets/pdf/`, and `assets/` with empty strings in the generated HTML before replacing the public root files.

English CV uses the latest confirmed GPA; Chinese CV is the original user-supplied document.

MIT License. Template: https://github.com/alshedivat/al-folio
