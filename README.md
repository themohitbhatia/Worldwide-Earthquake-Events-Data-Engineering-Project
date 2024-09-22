# 🌍 Worldwide Earthquake Events - Data Engineering Project

![Worldwide Earthquake Events Workflow](Worldwide%20Earthquake%20Events%20Work%20Flow.png)

## Project Overview

This project analyzes **global earthquake events** using cloud technologies and data engineering tools. It showcases how to fetch, process, and visualize large datasets related to earthquake occurrences across the globe.

## Tools & Technologies Used

- **Microsoft Fabric**:
  - **Notebook** for data preprocessing and exploration.
  - **Data Factory Pipeline** for automating data fetching and cleaning.
- **PySpark**: For efficient large-scale data processing.
- **Power BI**: For data visualization and reporting.

## Data Source

The earthquake data is fetched from the **USGS Earthquake Catalog**. You can view the raw data source at:  
[https://earthquake.usgs.gov](https://earthquake.usgs.gov)

## Project Workflow

The workflow follows these steps:
1. **Data Ingestion**: Automated using **Data Factory Pipeline**, fetching earthquake data from the USGS catalog.
2. **Data Cleaning**: Performed within the pipeline to ensure the data is ready for analysis.
3. **Data Processing**: Using **PySpark**, the large dataset is processed efficiently for meaningful insights.
4. **Visualization & Reporting**: Earthquake patterns, magnitudes, and geographical distributions are visualized using **Power BI**.

## Key Insights

- Visualized **earthquake magnitude** and **frequency** across different regions.
- Analyzed geographical patterns of earthquake occurrences over time.

## Explore

- [View the Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiMGI4NjQ1ZWEtNmZkNS00ZGUyLTk1OWItOTk3ZmM3YTEyZmE2IiwidCI6Ijc1NjMwNDliLTJmMWQtNDJlNC04MTY5LTA5NWFiNzM0Y2YwYyJ9)  


---

### How to Run the Project

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/worldwide-earthquake-events.git
