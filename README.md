Overview

This project examines short-term spatial and temporal air pollution patterns across the Greater Toronto and Hamilton Area (GTHA) using GIS-based interpolation and mobility data. The study focuses on pollution variation beyond fixed monitoring stations and evaluates how daily human movement influences real-world exposure.

Objective

Fixed air quality monitoring stations do not fully capture pollution variability between stations. This project aims to estimate pollutant levels in unmonitored areas and assess how individual mobility intersects with areas of elevated pollution.

Data

Hourly air quality data (PM₂.₅, NO₂, O₃) from Air Quality Ontario

One-week GPS trajectory data collected by project participants

2021 census spatial boundaries for the GTHA

Methods

Converted GPS trajectories from NMEA to GIS-compatible formats

Cleaned and standardized temporal and spatial datasets

Applied Inverse Distance Weighting (IDW) to interpolate pollutant surfaces

Used Kernel Density Estimation (KDE) to identify mobility concentration areas

Compared interpolated pollution surfaces with trajectory density to assess exposure patterns

Key Findings

PM₂.₅ concentrations were lower in Mississauga compared to Toronto and Hamilton

NO₂ exposure was elevated along major transportation and commuting corridors

O₃ showed widespread regional exposure, particularly during daytime hours

Mobility patterns significantly influenced individual exposure beyond monitoring station locations

Tools

ArcGIS Pro

QGIS

Survey123 / GeoTracker

Spatial interpolation and density analysis tools

Notes

This was a group project completed as part of GGR444, with equal contribution from all team members.
The repository focuses on spatial analysis methods, workflows, and research outputs.
