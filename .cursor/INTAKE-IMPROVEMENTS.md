# Intake form — engineering hub

Everything for improving this project lives **in this repo**. Open `~/intake-form-work` (or clone `manumasferral-ops/intake-form`) in Cursor.

| Resource | Purpose |
|----------|---------|
| `form.html` | Single-file app (GitHub Pages) |
| `.cursor/agents/intake-form.md` | Agent instructions for intake work |
| `.github/workflows/weekly-intake-review.yml` | Opens a Friday GitHub issue as a reminder |
| Live | https://manumasferral-ops.github.io/intake-form/form.html |

## Engineering rules

- **Vanilla** HTML/CSS/JS only — no React/Next/npm unless explicitly requested.
- **Bilingual** EN/ES on all new UI copy.
- **Preserve IDs:** `#address`, `#city`, `#state`, `#zip`, `#name`, `#tel`, `#dol`, `#source`, etc. (drafts, PDF, lead paste, automation).
- **Static hosting** — free geocoders (ArcGIS, Nominatim for companions/vehicles), no API keys, no backend.
- **UI ideas:** https://21st.dev/community/components — adapt small patterns (buttons, fields, cards, feedback), not full layout rewrites.

## Preferred layout (do not replace)

Staff prefer the **current single-page intake**, not a step wizard:

- Scrollable page with **collapsible sections** (Client, Case, Medical, …)
- **Toolbar:** progress %, **section pills** (jump + expand), dark mode, expand/collapse all, copy/email summary
- **Lead paste** block at top; **floating** save + PDF bar
- **Do not** add 21st “Multistep Form” / wizard-only navigation unless explicitly requested again

## Client address / GPS (implemented)

- **One provider for client:** ArcGIS suggest + verify (search and 📍 Verify use the same geocoder).
- **Confirm before overwrite:** panel shows match(es), score, current vs proposed; **Accept** or **Keep current**.
- **Scores:** ≥75% = verified badge; 60–74% = low (review); &lt;60% = cannot Accept.
- **Stale:** editing fields after verify shows **Edited** until re-verify.
- **Auto:** blur on `#address` when street exists but city/state/ZIP missing → suggest confirm panel.
- **Lead paste:** applies fields, then opens confirm panel (no silent overwrite).
- **All address/location fields** use the same ArcGIS flow: client, each **companion**, each **vehicle car location** (search, 📍 Verify, confirm panel, badges).

## Friday weekly pass — paste into Cursor / Claude Code

```
Weekly engineering pass on manumasferral-ops/intake-form — file form.html only.
Live: https://manumasferral-ops.github.io/intake-form/form.html
Read .cursor/INTAKE-IMPROVEMENTS.md and .cursor/agents/intake-form.md first.
Browse https://21st.dev/community/components for UI ideas; implement in vanilla HTML/CSS/JS.
Small high-impact diff; preserve field ids, drafts, PDF, bilingual EN/ES, ArcGIS client address flow.
Summarize changes + git push steps when done.
```

## Focused task — GPS / address (reference)

```
Improve GPS / address verification in form.html per .cursor/INTAKE-IMPROVEMENTS.md (client ArcGIS, confirm panel, badges, lead paste).
Smoke-test: autocomplete, Verify button, lead paste, drafts, PDF.
```

## Publish

```bash
cd /path/to/intake-form-work
git add form.html .cursor/
git commit -m "Describe your change"
git push origin main
```

Wait for GitHub Pages, then hard-refresh the live URL.
