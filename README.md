# Data-Visualization
📊 Traffic Accidents Visualization Project
✅ Project Overview

This project explores traffic accident data through various visualizations. The dataset is split across multiple CSV files, and each visualization is implemented as a separate Jupyter Notebook (.ipynb). Screenshots of the results are provided for reference.

The goal is to analyze accident patterns and contributing factors such as time of day, weather, lighting conditions, road surface, and injury severity.

✅ Directory Structure
Traffic_Accidents_Project/
├── Accidents_by_hour/
│   ├── notebook.ipynb
│   └── screenshot.png
├── Accidents_by_lighting/
│   ├── notebook.ipynb
│   └── screenshot.png
├── Accidents_by_month/
├── Accidents_by_weather/
├── Injuries_Severity/
├── Roadcondition_vs_injuryseverity/
├── crashtype_by_car_allignment/
├── heatmap/
├── Data_filtering_and_sorting.ipynb


Each folder corresponds to a specific visualization with the code and results.

✅ Dataset

The dataset files are combined from multiple parts and processed using the Data_filtering_and_sorting.ipynb.

The main dataset includes:

Date, Time

Traffic control device, Weather, Lighting

Crash type, Road condition

Injuries reported

Time-related fields (month, day, hour)

Geographic coordinates (optional for mapping)

✅ Visualizations Included

Accidents by Month – Bar chart showing monthly accident trends.

Accidents by Hour – Bar chart showing hourly accident distribution.

Accidents by Weather Condition – Count of accidents under different weather scenarios.

Accidents by Lighting Condition – Impact of lighting on accidents.

Injury Severity Distribution – Number of injuries by severity.

Road Condition vs Injury Severity – How road surface correlates with injuries.

Crash Type by Car Alignment – Relationship between crash types and road alignment.

Heatmap of Accidents by Month and Day of Week – Visual time trends.

Additional filtering and sorting operations used for preparing the dataset.

✅ Technologies Used

Python 3

Libraries:

pandas – Data manipulation

matplotlib, seaborn – Visualization

plotly – Interactive maps

glob – File handling

Jupyter Notebook environment for code and outputs.

✅ How to Run the Project

Clone or download this repository.

Install the required Python libraries:

pip install pandas matplotlib seaborn plotly


Open the Jupyter Notebooks in each folder to view the code and results.

Run the Data_filtering_and_sorting.ipynb first to clean and merge the dataset.

Explore each visualization notebook to understand different aspects of the accident data.

✅ Future Enhancements

Add predictive analytics for accident hotspots.

Incorporate interactive dashboards using Streamlit or Dash.

Expand the dataset with traffic volume or geographic information.
