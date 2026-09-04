## Pull Request: scaffold(frontend): Vite + React TypeScript app with Leaflet map, hotspot list, API client, Dockerfile, and CI

Adds a first-pass frontend scaffold for the Landslide Monitoring project.

This PR includes:
- Vite + React (TypeScript) application
- Leaflet-based map (react-leaflet) with sample hotspots
- Hotspot list and selection UI
- API client that hits GET /api/risks with a local fallback to src/data/sampleRisks.json
- Dockerfile and Nginx config for static serving
- GitHub Actions workflow to build the frontend on push/PR
- README.md and project config (tsconfig, vite.config)

How to run locally:
1. npm install
2. npm run dev

Follow-ups (high priority):
- Integrate /api/risks endpoint
- Add time-series per hotspot and alert UI
- Add tests and linting in CI

