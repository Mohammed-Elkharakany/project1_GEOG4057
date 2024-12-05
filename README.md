# Project1_GEOG4057
Project: Import and Visualize 2018 New Orleans Land Value Data
Overview
This project provides a Python script to import a JSON file containing 2018 Land Value data for New Orleans into a shapefile and visualize it using ArcGIS Pro. The script handles the conversion of geometries in WKT format and attributes from the JSON file into a feature class.

Script Description
The script, importNoTaxJSON, performs the following tasks:
1-Reads the JSON file (no_tax.json).
2-Converts geometries from WKT format.
3-Creates a feature class with appropriate fields.
4-Writes data from the JSON file to the feature class.
5-Provides an ArcGIS Pro interface for file selection and shapefile naming.

How to Use
1-Ensure you have ArcGIS Pro and arcpy installed.
2-Place the JSON file (no_tax.json) in your workspace directory.
3-Run the script with the output shapefile name as an argument.
