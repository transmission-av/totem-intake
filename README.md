# Transmission AV — totem content intake

Public, static, no backend. Two pages for clients sending digital-totem content:

- **`index.html`** — drop files on it before sending; checks names, sizes, coverage. Nothing uploads.
- **`guide.html`** — the Totem Content Guide (naming pattern, specs, checklist).

Pre-configure the checker for a show with a hash link, e.g.
`https://transmission-av.github.io/totem-intake/#show=NTST&positions=8&days=Sat,Sun,Mon,Tue,Wed&w=320&h=1080`

Source of truth lives in the private `architecture` repo (`docs/totem-intake/`); re-copy after edits.
© 2026 Transmission AV
