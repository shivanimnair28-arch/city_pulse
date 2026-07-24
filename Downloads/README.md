# CityPulse Prototype

A static HTML dashboard prototype for a smart city operations view. The dashboard simulates live and interactive city data with client-side JavaScript.

## Files

- `citypulse-prototype.html` — main interactive dashboard prototype
- `README.md` — project overview and usage instructions

## Features

- Live dynamic data simulation for traffic, AQI, crowd density, temperature, and infrastructure metrics
- Auto-refresh every 10 seconds with manual `Refresh` control
- Interactive navigation across modules:
  - City Overview
  - Mobility Intelligence
  - Environmental Intelligence
  - Infrastructure Health
  - Human Activity
  - What-If Simulator
  - Analytics
  - Reports
  - Settings
- Live pulse strip and clock updates
- Simulator for scenario impact modeling
- Data-driven tables and charts generated in JavaScript

## How to use

1. Open `citypulse-prototype.html` in a browser.
2. Use the sidebar to switch between dashboard sections.
3. Click `Refresh` to manually update all simulated data.
4. In the `What-If Simulator`, choose a scenario and zone to see projected impacts.

## Notes

- The dashboard is a front-end prototype only. There is no backend or real sensor integration.
- Data is generated and updated with JavaScript to look like live telemetry.
- For a production implementation, connect the UI to real APIs or streaming data sources.

## Suggested improvements

- Add real API data sources for traffic, air quality, and infrastructure monitoring
- Persist user settings and scenario histories
- Add chart libraries for richer visualization
- Add a mobile-responsive layout and keyboard navigation
