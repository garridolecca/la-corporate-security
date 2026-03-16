# LA County Corporate Security Dashboard

Interactive lens-based dashboard visualizing **343,000 security incidents** across
LA County, built with **ArcGIS Maps SDK 5.0** and **Canvas rendering**.

**[View Live Demo](https://garridolecca.github.io/la-corporate-security/)**

## Features

- **343K Real Incidents** from 7 intelligence sources (Samdesk, Dataminr Pulse,
  DataCapable, IRWIN, Geospark, Seerist, Factal), Aug 2023 -- Feb 2025
- **Interactive Lens** -- Move cursor to explore; radial bar chart shows
  category breakdown by data source within the lens area
- **5 Incident Categories** -- Armed Violence, Threats & Terrorism, Fire & Hazmat,
  Infrastructure, Transport & Disruption
- **Source Filtering** -- Toggle individual intelligence sources on/off
- **Category Filtering** -- Isolate specific incident types
- **Adjustable Radius** -- 1, 2, 3, 5, or 10 mile lens radius

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Map | ArcGIS Maps SDK for JavaScript 5.0 |
| Rendering | Canvas 2D with typed arrays (343K points) |
| UI | Custom glassmorphic panels, Calcite dark theme |
| Data | Static JSON pre-extracted from File Geodatabase |

## Getting Started

1. Open `index.html` in a browser or visit the [live demo](https://garridolecca.github.io/la-corporate-security/)
2. Enter an ArcGIS API key when prompted (for the basemap)
3. Move your cursor over the map to explore incidents

## Data

Source data: National incident layer (11.5M records) published as a hosted feature
service on ArcGIS Online, filtered to LA County bounding box.

## License

MIT
