---
name: intake-form
description: Auto Accident intake form (form.html) — UX, bilingual UI, address/GPS (ArcGIS), PDF, drafts, lead paste, GitHub Pages. Use for any intake-form change in manumasferral-ops/intake-form.
---

# Intake form agent

## Start here

1. Read **`.cursor/INTAKE-IMPROVEMENTS.md`** in this repo.
2. Edit **`form.html`** only unless the user asks otherwise.
3. Match existing patterns: DM Sans, CSS variables, **single-page scroll + collapsible sections + toolbar pills** (not multistep wizard), toasts, floating save bar.

## Drafts — do not delete

- Storage key: **`intake_drafts`** in `localStorage` (per browser + URL).
- **Never** wipe, rename, or overwrite the full draft store during code changes.
- **Merge** on import; migrate on key changes; keep `applyFormData` backward-compatible.
- Only the user deletes a draft (× with confirm). Agents must not remove draft UI or storage logic.

## Address / GPS

- Client `#address`, `#city`, `#state`, `#zip`: **ArcGIS** autocomplete + verify; staff **confirm** before overwrite.
- Do not revert client fields to Nominatim without a deliberate migration plan.
- Keep companion/vehicle location on Nominatim unless scoped to change those too.

## Output

- Bullet summary of what changed and why.
- Note any 21st.dev patterns adapted (links/names only).
- Remind user to `git push origin main` for Pages deploy.
