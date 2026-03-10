# Revit Point Cloud Scan View Generator 

This Python script automates the creation of individual 3D views for each scanner station (setup) within a Revit point cloud. 

## Project Overview

When dealing with a point cloud that contains multiple scan locations, manual inspection can be difficult. This script generates a dedicated 3D view for every single scan position, centering and cropping a **Section Box** exactly at the origin of each scan to facilitate a clear and localized model inspection.

## Usage

1. Open your Revit model with the linked point cloud.
2. Run the script through Dynamo.
3. Check your **Project Browser**; you will find new 3D views organized and named by their respective scan locations.

