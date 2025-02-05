# Insights from Failed Orders - Data Analysis Project

# Overview
This project analyzes failed taxi orders from Gett, focusing on identifying key factors contributing to cancellations and optimizing operations. The analysis includes geospatial visualization, time-based trends, and driver availability impact.

# Dataset
The dataset consists of taxi order records, including timestamps, cancellation times, driver assignment status, and geolocation data.

# Key Columns:
request_timestamp: Timestamp of the ride request.
cancellation_time_in_seconds: Time taken before cancellation.
is_driver_assigned_key: Indicates whether a driver was assigned (0: No, 1: Yes).
origin_latitude, origin_longitude: Coordinates of ride requests.

# Key Analyses & Visualizations
Geospatial Analysis
Used H3 Hexagonal Binning to visualize high-failure areas.
Displayed failed order density on an interactive Folium map.
Average Time to Cancellation Analysis
Analyzed how long users waited before canceling.
Plotted hourly trends with Seaborn line plots.
Impact of Driver Availability
Compared cancellation times for requests with and without assigned drivers.
Derived insights on how driver availability affects cancellations.

# Technologies Used
Python (Pandas, NumPy, Seaborn, Matplotlib, Folium, H3-Py)
Jupyter Notebook for analysis
GitHub for version control
How to Run the Project

# Clone the repository:
git clone https://github.com/your-username/failed-orders-analysis.git
cd failed-orders-analysis

# Install dependencies:
pip install pandas numpy seaborn matplotlib folium h3
Run the Jupyter Notebook to explore the insights.

# Results & Insights
Identified high-failure zones, enabling better driver allocation strategies.
Found peak cancellation times and their correlation with driver availability.
Proposed strategies to reduce cancellations, improving service efficiency.

# Future Improvements
Deeper analysis using Machine Learning to predict failed orders.
Integration with external weather and traffic data for better insights.
Deployment of an interactive dashboard (Power BI/Tableau).

# Contributing
Feel free to fork the repository, submit pull requests, or suggest improvements!

# License
This project is licensed under the MIT License.
