# Patan-Road-Classification
A GIS project focused on assessing the quality of OpenStreetMap (OSM) road data in Patan, Lalitpur.

Objective
To extract road network data, evaluate its completeness and classification, calculate road lengths, and produce a thematic map.

Tools Used
  QGIS (Data extraction, processing, and cartography)
  QuickOSM Plugin (OSM data download)

Key Findings
  Total Segments: 1,305
  Missing Names: 892 segments (~68% of roads lack a name tag). 
  Total Network Length: ~181.3 km

Project Workflow
  Extracted OSM highway data for the Patan area using Canvas Extent.
  Inspected attributes and calculated missing/empty name fields.
  Simplified 16 raw OSM highway tags into 5 practical classes: Arterial, Collector, Local, Service, and Non-motorized.
  Generated a summary table of road lengths by category.
  Designed a thematic map using QGIS Print Layout.
