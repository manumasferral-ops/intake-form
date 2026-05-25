# intake-form

Static **Auto Accident Intake** (`form.html`) for GitHub Pages.

- **Live:** https://manumasferral-ops.github.io/intake-form/form.html  
- **Local:** clone this repo (e.g. `~/intake-form-work`)

## Agent & improvement docs (all in-repo)

| File | Use |
|------|-----|
| [`.cursor/INTAKE-IMPROVEMENTS.md`](.cursor/INTAKE-IMPROVEMENTS.md) | Rules, Friday prompt, GPS/address notes |
| [`.cursor/agents/intake-form.md`](.cursor/agents/intake-form.md) | Cursor agent definition for this project |
| [`.github/workflows/weekly-intake-review.yml`](.github/workflows/weekly-intake-review.yml) | Friday GitHub issue reminder (enable Actions on `main`) |

Paste the **Friday prompt** from `INTAKE-IMPROVEMENTS.md` into Cursor or Claude Code when improving the form.

## Publish changes

```bash
git add form.html .cursor/
git commit -m "Your message"
git push origin main
```

Then hard-refresh the live URL after Pages deploys.
