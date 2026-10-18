# Climate Lens

An interactive world map for exploring recent climate-related disasters, natural hazards, and official alerts.
[Try Climate Lens on GitHub Pages](https://proben0630-creator.github.io/-/%ED%99%98%EA%B2%BD%20%EB%AC%B8%EC%A0%9C%20%EC%96%B4%EC%A9%8C%EA%B5%AC.html)

## What This Project Is

- **For whom:** Students and general users who want to explore recent hazards by country or city.
- **When to use it:** When comparing disasters across regions or checking the official source behind a map event.
- **What it can do:** Search for countries and cities, display alerts and events, show nearby hazards, compare an affected area with a country's land area, and link to official sources.

## How It Works

The page combines GDACS disaster alerts, NASA EONET events, USGS earthquake observations, World Bank country information, and Wikipedia city images. Leaflet draws the map, markers, and hazard areas. The interface clearly separates earthquake observations from climate-related indicators.

Core flow: **official open data → normalized events and locations → map layers → country, city, and event details**.

## Screens

Two useful screenshots would be:

1. **Global overview:** Show the world map, legend, several event markers, and the balanced event list.
2. **Selected location:** Search for a city or select a country so its image, alerts, statistics, nearby events, and source link are visible.

## Conclusion

Climate Lens brings several official datasets into one visual interface. It helps users move from a global pattern to a specific place while keeping the original data source available for verification.

## Build Process

The finished page connects multiple public APIs with different data formats. Its code converts them into a common event structure, calculates distances and polygon areas, and updates the map and detail panel from the same selected item.

## Next Steps

- Add clearer loading and fallback messages for every external data source.
- Expand regional official-data connections.
- Add the two recommended screenshots to this README.
