# Global Map Explorer
npm install && npm run dev

- Map: MapLibre GL JS (OSM streets, Esri satellite, OpenTopoMap terrain)
- Geocoding + boundaries: Nominatim (real OpenStreetMap polygons; points are flagged "approximate")
- Routing: OSRM (driving) and routing.openstreetmap.de (walking/cycling)
- No API keys needed. These public servers are for demos only (about 1 request/second, no heavy use).
  For production, put Geoapify / MapTiler / openrouteservice behind your own small server so keys stay private.
- Keep the attribution shown on the map.
