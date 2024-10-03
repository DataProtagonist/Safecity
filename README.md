# Safecity

# Crime Data Analysis in Worcester 🔍

This repository contains an in-depth analysis of crime data in the city of Worcester, Massachusetts, using Tableau for visualization and pattern identification. The project explores the spatial and temporal distribution of crimes, offering insights that can help enhance public safety measures and guide law enforcement strategies.

## 📂 Project Overview

The primary goal of this project is to identify crime patterns and trends through the analysis of police incident data in Worcester. Using Tableau's data visualization capabilities, we examine crime trends over time, analyze geographical crime hotspots, and break down incidents by time of day and type of crime.

This project was conducted in collaboration with:
- **Pranay Datta Kavukuntla**
- **Lokesh Vangula**

## 🚀 Project Goals

- **Identify crime trends**: Analyze how crime incidents vary by time of day, week, and year.
- **Geographical mapping**: Visualize crime hotspots across Worcester's neighborhoods.
- **Aid law enforcement**: Provide actionable insights to help allocate resources and develop proactive safety measures.
- **Community awareness**: Inform the public of crime patterns and encourage community-based safety efforts.

## ⚙️ Technologies & Tools

- **Data Visualization**: Tableau for creating dashboards and visual representations of crime trends.
- **Data Handling**: Excel for managing and cleaning the dataset.
- **Reporting & Presentation**: PowerPoint for the project presentation, and PDF for the final report.
- **Dataset**: The dataset contains 398,373 records of crime incidents in Worcester, including details such as time of day, type of crime, location (ZIP code), and police department involvement.

## 📊 Dataset

The dataset used for this analysis includes the following key features:
- **INCIDENT_NUMBER**: Unique identifier for each incident.
- **DATE_LOGGED**: Date the incident was logged.
- **TIME_LOGGED**: Time the incident was logged.
- **YEAR**: Year the incident occurred.
- **INCIDENT_TYPE**: Type of crime committed.
- **LOCATION**: Physical location where the incident occurred.
- **ZIPCODE**: Postal code for the incident location.
- **DEPARTMENT**: The police department handling the case.

## 🔍 Key Findings

1. **Temporal Analysis**:
   - Certain types of crime (e.g., burglaries) are more frequent during late evenings, while others (e.g., traffic violations) occur more often in the afternoon.
   - The inclusion of a **Time Range** column has allowed for more granular analysis, identifying crime spikes in specific hourly windows.

2. **Geographical Crime Hotspots**:
   - Using **ZIPCODE** and **LOCATION**, we identified high-crime areas within the city, providing critical information for targeted police patrols and community safety initiatives.

3. **Crime Type Distribution**:
   - The data shows notable variations in the types of crimes based on the time of day and day of the week. For example, violent crimes are more common in the late hours, while property crimes peak during the afternoon.

## 📈 Visualizations and Dashboards

- **Tableau Dashboards**: Explore interactive visualizations that provide insights into crime patterns by time and location. These dashboards are available in the `Crime data Analysis.twb` file and feature:
  - Time range analysis.
  - Geographical heatmaps to display crime hotspots.
  - Crime type distributions throughout the day.

## 📄 Reports and Presentation

- **Final Report**: The detailed analysis is documented in the `Final Project Phase 4.pdf` file.
- **Presentation**: The PowerPoint presentation (`Police data analysis in Worcester.pptx`) provides a summary of the project's key insights, audience benefits, and future scope for analysis.

## 📅 Future Scope

In future work, we aim to:
- Integrate **socioeconomic and demographic data** to explore deeper correlations between crime rates, income levels, and educational attainment.
- Use **predictive analytics and machine learning** to forecast potential crime trends and help city officials proactively address crime hotspots.
- Collaborate with Worcester's community groups and city officials to develop data-driven public safety programs.

## 📂 Directory Structure

crime-data-analysis-worcester/ │ ├── data/ # Folder for datasets and processed data ├── dashboards/ # Tableau dashboards ├── reports/ # Reports and presentations └── README.md # Documentation of the project


## 💻 Usage Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/DataProtagonist/crime-data-analysis-worcester.git
   ```
2. Open the Tableau Workbook: Use Tableau Desktop to open Crime data Analysis.twb and explore the interactive dashboards.

3. Review the Report and Presentation: Open Final Project Phase 4.pdf for the detailed written analysis and Police data analysis in Worcester.pptx for the project summary.


### Additional Steps:

1. **Upload Files**: 
   - Place the `Police_Incident_Data_Combined.xlsx`, `Crime data Analysis.twb`, and other files into the appropriate directories (`data/`, `dashboards/`, etc.).

2. **Push to GitHub**: 
   - Once the files are structured, you can push the repository to GitHub.

3. **Set up CI/CD** (Optional): 
   - If you’d like to automate testing, code reviews, or deployment, you can set up a CI/CD pipeline as we did for the previous project.

---

Let me know if you need help with any additional setup or adjustments!
