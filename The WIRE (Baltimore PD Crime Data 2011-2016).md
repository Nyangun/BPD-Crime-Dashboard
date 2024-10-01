The WIRE (Baltimore PD Crime Data 2011-2016) Dashboard

Project Overview
This project analyzes and visualizes crime data from Baltimore, focusing on data collected by the Baltimore Police Department between 2011 and 2016. Inspired by the TV series The Wire, this dashboard aims to provide insights into crime trends, hotspots, and patterns across different neighborhoods and districts in the city. The data consists of 286,000 rows and 12 columns, capturing details such as the type of crime, location (coordinates and neighborhoods), time, and whether the incident took place indoors or outdoors.

The dataset was obtained from the City of Baltimore Open Data platform and is updated monthly.

Key Features of the Dashboard
            Calendar Visualization with Total Incidents per Day:

            This visual represents a day-by-day breakdown of crime incidents over the years.
            The calendar provides a quick overview of high-crime days, with colors representing the volume of incidents per day.
            Hovering over a particular day shows the exact count of crime occurrences for that date.
            Top 10 Worst Neighborhoods (Sidebar Graph):

            A side bar graph shows the ten neighborhoods with the highest number of reported crimes.
            The neighborhoods are ranked from worst to least based on total crime incidents, making it easy to identify crime hotspots.
            Crime Category Heat Map (By District):

            This heat map categorizes different types of crimes (e.g., assault, burglary, robbery) by district.
            It shows which districts face the highest crime rates for particular categories, helping to visualize the severity and distribution of crimes across Baltimore.
            Crime Incidents by Time of Day (Area Chart):

            An area chart that visualizes crime occurrences over different times of the day, segmented into "Day" and "Night".
            This chart helps identify crime patterns, highlighting peak crime times and how incidents fluctuate over a 24-hour period.
            Weapons Used (Pie Chart):

            A pie chart that categorizes crimes based on the type of weapon used (e.g., firearms, knives, no weapon).
            This breakdown provides insights into the nature of violence associated with different crimes.
            Crime Incidents by Day of the Month (Line Chart):

            A line chart visualizing the total number of incidents on each day of the month over the six-year period.
            This chart helps determine if certain days of the month see more crime, such as the beginning or end of the month.
            Inside vs. Outside Incidents (Tree Map):

            A tree map displaying the percentage breakdown of incidents that occurred inside vs. outside.
            This visual gives a quick, proportional view of where most crimes take place, whether indoors or outdoors.

New Fields/Variables Created
During the analysis and visualization process, new fields were derived to enhance data interpretation:

Crime Category Section:

            A custom field was created by categorizing the detailed crime descriptions into broader crime categories (e.g., violent crimes, property crimes, narcotics-related crimes, etc.).
            This helps in grouping similar types of crimes and analyzing trends more effectively.
            Time of Day Classification:

            Based on the time data (CrimeTime), a new field was created to classify incidents as either "Day" (7:00 AM to 6:00 PM) or "Night" (6:00 PM to 7:00 AM).
            This allowed for the analysis of crime patterns over different parts of the day, providing insights into how crime varies between daylight and nighttime.
            How to Use the Dashboard
            Navigation: The dashboard is interactive and user-friendly, allowing viewers to explore various crime trends. Users can hover over the visuals for more details, click on segments to filter data, and analyze specific trends of interest.
            Filters: The dashboard includes filters for district, neighborhood, crime category, and time of day, enabling detailed, customizable insights into the crime data.
            Comparison: Users can compare different districts, neighborhoods, and crime categories to draw meaningful conclusions about where and when crime occurs the most.
            Insights
            The calendar visualization highlights specific days of the year when crime rates peaked.
            The worst neighborhoods chart shows a clear concentration of crime in a few key areas, helping to identify neighborhoods most in need of intervention.
            The heat map by district offers a focused view on the types of crimes prevalent in each district.
            The area chart on time of day shows crime spikes during particular hours, possibly aiding police in resource allocation and patrol planning.
            The tree map breaks down inside vs. outside crime locations, revealing whether certain crimes tend to occur in indoor or outdoor settings.

Conclusion

This dashboard provides a comprehensive overview of crime data in Baltimore from 2011 to 2016. It highlights key crime patterns, categories, and geographical trends, making it a useful tool for law enforcement, policymakers, and researchers interested in understanding crime dynamics in Baltimore.