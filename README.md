# orchard-precision-farming
Geospatial analysis and digital twin prototype for precision farming in orchards.

## Project overview

This project demonstrates a geospatial workflow for precision farming in orchards. It represents the field boundary, tree rows, individual trees, and agricultural machinery GPS observations.

## Main workflow

- Create field, row, and tree geometries using GeoPandas and Shapely.
- Simulate machinery GPS and application-rate data.
- Match GPS observations to the nearest orchard row and tree.
- Compare actual and required application rates.
- Identify potential under-application and over-application.
- Simulate and compare machinery routes using operational KPIs.

## Technologies

- Python
- Pandas and GeoPandas
- Shapely
- Matplotlib
- Git and GitHub