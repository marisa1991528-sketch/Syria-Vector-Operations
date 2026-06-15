# Syria-Vector-Operations

GeoPandas vector analysis workflows for Syria using open-source geospatial datasets.

## Contents

### 11 Vector Buffer

Buffer generation around vector features.

Features:

- Buffer creation
- Distance-based analysis
- Polygon generation
- GeoPandas buffer()

---

### 12 Vector Dissolve

Aggregation of multiple polygons into a single geometry.

Features:

- Polygon merging
- Attribute aggregation
- GeoPandas dissolve()
- Boundary simplification

---

### 13 Vector Spatial Join

Spatial relationship analysis between vector layers.

Features:

- Point-in-polygon analysis
- Spatial Join
- Attribute transfer
- GeoPandas sjoin()

---

### 17 Vector CRS Alignment

Coordinate reference system alignment between vector datasets.

Features:

- CRS inspection
- CRS transformation
- EPSG conversion
- Layer alignment
- GeoPandas to_crs()

---

### 18 Geometry Repair

Detection and repair of invalid geometries.

Features:

- Geometry validation
- Self-intersection detection
- Geometry repair
- Shapely is_valid
- Shapely buffer(0)

---

## Data Sources

### Administrative Boundaries

- HDX OCHA
- Syrian Arab Republic – Subnational Administrative Boundaries

### Hydrology Data

- HDX Humanitarian OpenStreetMap Team
- Syria Waterways

---

## Tools

- Python
- GeoPandas
- Shapely
- Folium

---

## Techniques Demonstrated

- Buffer analysis
- Polygon dissolve
- Spatial Join
- CRS transformation
- CRS alignment
- Geometry validation
- Geometry repair
- Vector processing workflows
