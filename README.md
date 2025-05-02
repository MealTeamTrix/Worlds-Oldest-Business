🏢 Oldest Businesses Analysis

This Jupyter Notebook performs a data-driven exploration of some of the oldest existing businesses around the world, analyzing their distribution across continents and industries. The notebook uses Python (pandas) to read and analyze multiple CSV datasets and uncover patterns about historical business longevity.

📁 Dataset Overview

The notebook uses four main CSV files located in the data/ directory:

File	Description
businesses.csv	Contains information about long-established businesses including their name, founding year, category code, and country code.
new_businesses.csv	Supplementary dataset with additional older businesses to enrich analysis.
countries.csv	Maps country codes to full country names and continents.
categories.csv	Maps business category codes to descriptive names.

🔍 Key Questions Answered

What are the oldest businesses on each continent?
Which countries are missing historical business data?
Which industries have historically lasted the longest on each continent?

📊 Analysis Workflow

The notebook walks through the following major steps:

Load and inspect data using pandas.
Merge datasets to enrich business data with geographical and category information.
Group and aggregate data to identify:
The oldest businesses by continent
Countries missing business history records
Longevity by business category across continents


