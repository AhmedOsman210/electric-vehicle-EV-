🚗 Electric Vehicle Population Data Analysis

📌 Overview

This project analyzes the Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) registered through the Washington State Department of Licensing (DOL). The dataset includes information about vehicle make, model, registration location, electric range, base MSRP, and more.

📊 Dataset Details

Rows: 223,995

Columns: 17

Missing Values: Yes (handled during preprocessing)

Duplicates: Removed

📁 Column Descriptions:

VIN (1-10): First 10 characters of the Vehicle Identification Number.

County & City: Where the vehicle is registered.

State & Postal Code: Location details.

Model Year: Manufacturing year.

Make & Model: Brand and specific model.

Electric Vehicle Type: Battery Electric or Plug-in Hybrid.

Electric Range: Distance the vehicle can travel on a full charge.

Base MSRP: Manufacturer's Suggested Retail Price.

Legislative District: Registration location.

Electric Utility: Provider for charging stations.

2020 Census Tract: Demographic analysis data.

🛠️ Tech Stack

Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook for EDA & visualization

GitHub for version control

📌 Key Steps in Analysis

✅ Data Cleaning & Preprocessing

Handled missing values

Removed duplicate records

Converted relevant columns to appropriate data types

🔎 Exploratory Data Analysis (EDA)

Summary statistics & distribution plots

Vehicle registration trends by location

Price analysis of EVs

Electric range comparison

Correlation heatmap visualization

📈 Machine Learning (Future Scope)

Predictive modeling for EV adoption trends

Clustering EVs based on range & price

📊 Visualizations



🚀 How to Run the Project

# Clone the repository
git clone https://github.com/yourusername/EV-Data-Analysis.git

# Navigate to the project folder
cd EV-Data-Analysis

# Install required libraries
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook

📌 Future Improvements

Enhance predictive modeling

Integrate real-time EV data sources

Build a dashboard for interactive visualizations

🏆 Acknowledgments

Special thanks to the Washington State Department of Licensing for providing the dataset.
