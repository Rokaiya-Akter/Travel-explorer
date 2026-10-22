# Voya — Travel & Places Explorer

An editorial-style travel intelligence app. Search any country or city and get rich travel data — all powered by free, open APIs with **no API keys required**.

## 🌐 External APIs Used

| API | Purpose | Cost |
|-----|---------|------|
| [RestCountries](https://restcountries.com) | Country facts, flags, currencies, languages | Free, no key |
| [OpenStreetMap Nominatim](https://nominatim.openstreetmap.org) | Place search & geocoding | Free, no key |
| [Overpass API (OSM)](https://overpass-api.de) | Nearby attractions & points of interest | Free, no key |
| [Wikimedia / Wikipedia](https://en.wikipedia.org/w/api.php) | Destination photography | Free, no key |
| [OpenStreetMap Embed](https://www.openstreetmap.org) | Interactive map | Free, no key |

## ✨ Features

- **Overview tab** — Country hero card with flag, capital, population, area, languages, currencies
- **Photos tab** — Real Wikimedia photos of the destination
- **Nearby tab** — Points of interest (museums, monuments, viewpoints) sorted by distance
- **Map tab** — Embedded interactive OSM map centered on the location
- **Autocomplete search** — Live suggestions as you type

## 🚀 How to Run

Just open `index.html` in any modern browser — no setup needed:

```
double-click index.html
```

Or serve locally:
```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`
