# Project1_GEOG4057
Project: Import and Visualize 2018 New Orleans Land Value Data
Overview
This project provides a Python script to import a JSON file containing 2018 Land Value data for New Orleans into a shapefile and visualize it using ArcGIS Pro. The script handles the conversion of geometries in WKT format and attributes from the JSON file into a feature class.

Script Description
The script, importNoTaxJSON, performs the following tasks:

Reads the JSON file (no_tax.json).
Converts geometries from WKT format.
Creates a feature class with appropriate fields.
Writes data from the JSON file to the feature class.
Provides an ArcGIS Pro interface for file selection and shapefile naming.
How to Use
Ensure you have ArcGIS Pro and arcpy installed.
Place the JSON file (no_tax.json) in your workspace directory.
Run the script with the output shapefile name as an argument.
