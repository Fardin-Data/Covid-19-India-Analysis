## Introduction
The COVID-19 pandemic has profoundly impacted public health. This project aims to provide valuable insights into the pandemic's progression in India, helping with decision-making and resource allocation.

## Problem Statement
- Extract COVID-19 data for India using Python and the `requests` module.
- Parse and clean the data, ensuring consistency and handling missing values.
- Perform SQL aggregations to create an Excel dashboard with the following insights:
    - Weekly evolution of confirmed cases, recoveries, deaths, and tests.
    - Categorize districts based on testing ratios and analyze deaths across categories.
    - Compare delta7 confirmed cases with vaccination data.
    - Create KPIs to assess case severity in different states.
    - Categorize total confirmed cases by month to identify the worst month for India.

## Dashboard
![Screenshot 2023-09-09 155926](https://github.com/Fardin-Data/Covid-19-India-Analysis/assets/137788371/ce369b1c-d56b-40db-b96a-05e72c140200)

![Screenshot 2023-09-09 183418](https://github.com/Fardin-Data/Covid-19-India-Analysis/assets/137788371/5bf87ed5-aa93-42f9-9ea8-690a88dd5c5b)


- The dashboard offers two views (state and district), allowing users to switch between them using bookmarks. 
- It includes various filters for exploring different scenarios.

## Files Information
- **Project Presentation**: Link to Project Presentation
- **Dashboard**: Excel file with sheets for state data, district data, pivot tables, and the dashboard.
- **TimeSeries_Data**: Cleaned time series data exported from the web server after EDA.
- **District_Data**: Cleaned district data exported from the web server after EDA.

## Tech Stack
- Python: Data extraction and EDA
- SQL: Aggregation for table creation
- Excel: Dashboard creation and data presentation
- Power Query: Minor data adjustments

## Data Sources
- [District Data](https://data.covid19india.org/v4/min/data.min.json)
- [Time Series Data](https://data.covid19india.org/v4/min/timeseries.min.json)

## Data Info
- [District Data Documentation](https://data.covid19india.org/documentation/v4_data.html)
- [Time Series Data Documentation](https://data.covid19india.org/documentation/timeseries.min.html)

## License
This project is licensed under the MIT License, allowing you to use, modify, and distribute the code and visuals while maintaining the original license terms.

## Team Members
- [Fardin khan](https://github.com/Fardin-Data)
- [Sachin Yadav](https://github.com/sachinyadav22)
- [Vanshpal Singh](https://github.com/vanshpalsingh?tab=following)
- [Vishwanath J](https://github.com/Vishwanath-J-25?tab=repositories)

For questions or feedback, please contact: [fardinkhan.data@gmail.com]

Enjoy exploring the project!
