# Open Text Compliance — Admin Configuration Prototype

High-fidelity HTML click-through of the LSC Open Text Compliance admin experience.

**Entry point:** [`admin-console.html`](admin-console.html) (root `/` redirects here).

## Screens
- **Admin Console** — Configuration tile grid with the new *Open Text Compliance* tile.
- **Compliance Settings** — Org Default / Profile / User scoping; detection, jurisdiction, default severity outcomes.
- **Policies** — Author/edit policies: grounding doc, keywords/phrases (LLM + offline), country/language, prompt template, audience.
- **Monitored Fields** — Map open-text fields across entities; apply policies; per-field severity → outcome.
- **Violation Log** — Review detections with the reviewer disposition workflow (Confirm / False Positive).

Static vanilla HTML/CSS/JS. No build step.
