---
layout: project
type: project
published: true
image: images/land_sage.png
title: LandSAGE
permalink: projects/land_sage
# All dates must be YYYY-MM-DD format!
date: 2019-01-08
labels:
  - Geospatial Data Visualization
  - Decision Support Tools
  - Natural Disasters
  - Southeast Asia
summary: As a research assistant at the Laboratory for Advanced Visualization and Applications, I was lead developer of LandSAGE.
---

LandSAGE is a decision support tool for monitoring and mitigation of natural disasters (landslides, mudflows, and floods) in Southeastern Asia using Cyber-enabled Collaboration, Analysis, Navigation and Observation Environments (CyberCANOEs).
<img class="ui large right floated rounded image" src="../images/land_sage.png">

I worked as lead developer of the LandSAGE application for my first year as a research assistant at LAVA. During this time, I integrated real-time and historic hydrological and meteorological data pertaining to landslides and floods in Southeastern Asia into a geospatial visualization application developed for SAGE2.
The sources of data leveraged in this application came from the following sources.
<ul>
  <li>The Cambodia Department of Meteorology <a href="http://www.cambodiameteo.com/map?menu=3&lang=en">website</a> providing live weather data from 35 sensors across Cambodia.</li>
  <li>The Thai Meteorological Department <a href="https://www.tmd.go.th/en/">website</a> providing live weather data and monthly cumulative rainfall data at 120 sensor sites across Thailand</li>
  <li>The Mekong River Commission <a href="http://www.mrcmekong.org/">website</a> providing data from 60 river height and rainfall sensors distributed throughout the Mekong river basin in SEA.</li>
</ul>

The sensor data is displayed on an interactive basemap that can be clicked to view in-depth information about locations covered by the respective sensor networks.
This application is developed as a native SAGE2 application, making use of HTML/CSS/Javascript and the Leaflet.js plotting library.

Source: <a href="https://github.com/btwooton/LandSAGE"><i class="large github icon"></i>LandSAGE</a>


