
# Mortgage Centre Class Action — Static Website (Legal-Heavy)

This repository contains a static, legal-heavy website intended to notify and enroll potential Class Members in the proposed class proceeding against iBrokerPower Inc., Ronald Kam Shing Lee, Ginkgo MIC Mortgage Investment Corporation, Henry Tsi, and The Mortgage Centre Canada Inc.

## Structure
- `index.html` — Landing / summary for potential Class Members.
- `about.html` — Longer, legal-oriented explanation of parties, causes of action, and evidence sources.
- `legal-docs.html` — Index page linking to documents in `/docs`.
- `join.html` — Registration form (posts to Formspree placeholder).
- `contact.html` — Contact and secure submission guidance.
- `styles.css` — Shared minimal styling.
- `docs/` — Contains draft pleadings and an exhibit matrix (generated as HTML files).

## Deployment (local / VS Code)
1. Unzip the archive.
2. Open the folder in VS Code.
3. Serve locally using the VS Code Live Server extension or `npx http-server` or `python -m http.server`.
4. Replace the form `action` attribute in `join.html` with your real form endpoint (Formspree, Formkeep, Netlify Forms, or your server).

## Security notes
- Do not collect or store unredacted personal or sensitive information on public pages.
- Use encrypted uploads or a secure case management system for evidence.
- Consult counsel and IT before collecting client data or third-party lender information.

## Next steps I can help with
- Replace placeholder form endpoint with a working secure form integration.
- Add server-side endpoints (Node/Express) to accept encrypted uploads and store metadata.
- Convert legal documents in `/docs` to downloadable PDFs.
- Improve accessibility and add bilingual (English/French) support.

---
