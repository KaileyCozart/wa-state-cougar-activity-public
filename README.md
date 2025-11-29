# CougarScope: Using Machine Learning to Explore Cougar Activity in Washington State

## Website

https://kaileycozart.github.io/wa-state-cougar-activity-public/

## Project Overview

Interactions between cougars, humans, and other animals present challenges in regions with high cougar activity. In the proposed study, data from the Washington Department of Fish and Wildlife (WDFW) and the Social Media Cougar Activity (SMCA) Dataset will be used to investigate how clustering algorithms can be used to uncover patterns in cougar behavior and whether classifiers can predict high-impact cougar events. This project aims to enhance existing knowledge of cougar aggression behavior with the possibility of offering new insights, ultimately leading to improved public safety and wildlife conservation efforts.

## User / Website Overview

Figure 1 contains the WDFW confirmed cougar safety counts by county from the years 2016 to 2025, with darker colors indicating more reports. By hovering on or clicking each county, the count will be displayed in the tooltip. 

Figure 2 contains the SMCA datasets's cougar sighting counts divided by GMU, with darker colors indicating more reports. By hovering on or clicking each GMU, the count will be displayed in the tooltip. This data is for the year 2024.

Figure 3 contains a sample of cougar sightings over time, divided by GMU and date, with the size of the circle being determined by the number of cougars in that sighting. By clicking on a particular dot, the date, GMU, and number of cougars are displayed. 

## Developer / Codebase Overview

The docs folder contains the files for the website. The following 3 files are outside resources: 'd3.min.js,' 'plot.min.js,' 'topojson.v2.min.js.' The 'Game_Management_Units_(Polygons)_2025.geojson' contains the polygons for Washington State's GMUs and is downloaded directly from the government website. The '2024_cougar_activity_data_sample_combined.csv' and 'wdfw_2016_to_2025_county_counts.csv' datasets contain the sample data for use in the public website. Styles are contained in 'styles.css' and run instructions are provided alongside the main website code in 'index.html.'
