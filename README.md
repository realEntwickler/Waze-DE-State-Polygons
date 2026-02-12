# Germany Federal States – Polygon Data

This repository provides polygon geometry data of the German federal states for technical and geospatial use.

## Content

- Individual polygon files for each federal state  
- Available formats:
  - WKT (Well-Known Text)

## Technical Specifications

- Coordinate order: **Longitude, Latitude**
- Closed polygon rings
- Valid geometry structure suitable for spatial databases and automated processing

## Intended Use

The data is designed for:

- GIS applications  
- Spatial databases (e.g. PostGIS)  
- Geofencing  
- Coordinate validation  
- Routing and mapping systems  
- Use in scripts and automated workflows  

## Example (WKT)

```sql
POLYGON(
  (
    (6.28057 50.26867, 6.28465 50.27358, ... , 6.28057 50.26867)
  )
)
