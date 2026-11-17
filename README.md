# stay-cool-socal-landing

Meta ads landing page for **Stay Cool SoCal** — HVAC service in Los Angeles.

Single self-contained `index.html`: lead-qualifying flow, no build step, no dependencies beyond the Archivo web font.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Notes

- `<meta name="robots" content="noindex">` is set — remove it before using this as an indexed public page.
- Styles and scripts are inlined; edit `index.html` directly.
