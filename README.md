# Global_Electricity

## Global Electricity Access

The visualisation follows the theme of Global to Local and attempts to show the disparity in access to electricity around the globe. Following the discourse of Sustainable Development Goal number 7 that encourages clean and sustainable sources of energy for all- the visualisation attempts to bring out the stark disparity in distribution of energy as a resource where a part of the global population is able to access and ergo use too much and another part next to nothing in comparison.

## Datasets:

The datasets were procured from Our World in Data which is a website that collates various data contributions a project of Global Change Data Lab (a non-profit organization). The data here was a contribution from the World Bank who originally acted to assemble the data.
The primary datasets used for this visualisation include world access (and no access) to electricity recorded over the last three decades as well as per capita energy use. Both datasets were available in the dominations of- World, Region and Country, and have been thus used for the visualisation.
Link to datasets: https://sdg-tracker.org/energy

## Visualisation:

The visualisations utilize Mapbox library resources for visualising the data in maps and attempts to experiment with Apache Echarts libraries to visualize the data in charts.

## Design and Technical Approach:

The visualisation uses a top-down approach by demonstrating the comparison on the larger (world) scale and zooming in to region, country and population. Area charts were opted for over line or bar charts to highlight the shaded portions over set periods of time. As a design, this provided greater emphasis to the disparity in the charts (as was the aim of the visualisation)- especially in the comparison of regions.
The swipe comparison container was opted for to show the disparity between the two datasets and the intensity of the same over time. The larger and darker circles indicate and exhaustive number on both sides.
