# Vattenstånd — Swedish Coast Sea Level

A self-contained static web page showing observed sea levels along the Swedish
coast, using SMHI's free open data API. No backend, no API key, no build step.

## Files

```
index.html     — the page, open directly via a local web server or GitHub Pages
```

## Usage

**Local:**
```bash
python3 -m http.server 8000
# open http://localhost:8000
```

**GitHub Pages:** push the repo, enable Pages under Settings → Pages → main branch / root.

## Data source

| Data | Source | Licence |
|---|---|---|
| Sea level observations (parameter 13: Havsvattenstånd, cm, RH2000) | SMHI Open Data | CC BY 4.0 SE |

Stations are fetched live from the SMHI API. Select the one nearest your location.
