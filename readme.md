
# Hurricane Helene Rainfall in Western North Carolina

## Purpose

This interactive map explores rainfall totals recorded during
Hurricane Helene and the preceding rain event in western
North Carolina from September 25th-27th, 2024.

The goal is to show how rainfall varied across selected
mountain communities during this historic weather event.

## Data

Rainfall data was obtained from the North Carolina State
Climate Office's report, "Rapid Reaction: Historic Flooding
Follows Helene in Western NC."

The dataset contains selected weather station rainfall
totals measured in inches over a three-day period.

The data was manually organized into GeoJSON point features.
Coordinates are approximate locations of the named areas.

Source:
https://climate.ncsu.edu/blog/2024/09/rapid-reaction-historic-flooding-follows-helene-in-western-nc/

## Symbolization

This map uses proportional circle symbols. Larger circles
represent greater rainfall totals. Circle area is
proportional to the rainfall measurement.

Clicking a circle displays the location, county, and
rainfall total.

## Design

The map was created with Leaflet and OpenStreetMap basemap from the Leaflet Providers Demo.

Blue circles represent rainfall observations, with
orange highlighting when the user hovers over a location.

The map includes a title, description, legend, scale bar,
attribution, and interactive popups.

## Author

Victoria Burleson
Appalachian State University
October 2026
