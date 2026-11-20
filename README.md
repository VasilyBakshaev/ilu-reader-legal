# Ilu Reader — static site

- `index.html` — Ilu Reader landing page.
- `privacy-policy.html`, `terms.html` — English legal documents, matching the
  Markdown source in `docs/`.
- `licenses.html` — third-party notices for the typefaces.
- `styles.css` — cool paper-and-graphite theme from the app. Prose and headings
  are set in Literata (serif), the interface — navigation, labels, tables and
  buttons — in Manrope; both are SIL OFL 1.1 and self-hosted in `fonts/`
  together with their license texts.
- `fonts/` — `Literata-*.woff2`, `Manrope-*.woff2`, `Literata-OFL.txt`,
  `Manrope-OFL.txt`.
- `THIRD_PARTY_NOTICES.md` — font attribution; both typefaces are SIL OFL 1.1,
  full license texts are in `fonts/`.
- `icon.png` — app icon.

When a document in `docs/` changes, mirror it in the matching HTML page: the
header fields (`Operator`, `Contact`, `Publication`, `Effective date`) form one
`.meta` paragraph separated by `<br>`, e-mail addresses become `mailto:` links,
links to the sibling document point to `*.html`, and the `<h1>` keeps the short
document name shown in the site header (`Privacy Policy`, `Terms of Use`).
