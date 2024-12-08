# 10-Academy-week0 

# **MoonLight Energy Solutions: Solar Investment Analysis**

## **Overview**
MoonLight Energy Solutions aims to develop a strategic approach to enhance operational efficiency and sustainability through targeted solar investments. This project involves analyzing environmental measurement data to identify high-potential regions for solar installation and providing actionable insights aligned with the company's long-term sustainability goals.

## **Objectives**
- Perform exploratory data analysis (EDA) to identify trends and insights from solar radiation and environmental data.
- Assess the impact of environmental factors (e.g., humidity, wind speed) on solar energy potential.
- Provide recommendations for high-potential locations for solar installations.
- Present actionable insights in a well-structured strategy report.

## **Dataset**
The dataset contains aggregated Solar Radiation Measurement Data, including:
- **Timestamp:** Date and time of observation.
- **GHI:** Global Horizontal Irradiance (W/m²).
- **DNI:** Direct Normal Irradiance (W/m²).
- **DHI:** Diffuse Horizontal Irradiance (W/m²).
- **ModA & ModB:** Sensor measurements (similar to irradiance).
- **Tamb:** Ambient temperature (°C).
- **RH:** Relative humidity (%).
- **WS, WSgust, WSstdev:** Wind speed metrics (m/s).
- **WD, WDstdev:** Wind direction metrics (°N).
- **BP:** Barometric pressure (hPa).
- **Cleaning:** Indicator for cleaning events.
- **Precipitation:** Rate of precipitation (mm/min).
- **TModA & TModB:** Module temperatures (°C).

## **Analysis Workflow**
### **Step 1: GitHub Setup**
- Repository Name: `10-Academy-week0`.
- Branch: `task-1` for Day 1 analysis.
- Commit regularly with descriptive messages.

### **Step 2: Exploratory Data Analysis (EDA)**
- **Summary Statistics:** Analyze mean, median, and standard deviation of numeric columns.
- **Data Quality Check:** Identify missing values, outliers, and anomalies.
- **Time Series Analysis:** Observe trends in GHI, DNI, DHI, and Tamb.
- **Impact of Cleaning:** Evaluate cleaning's effect on sensor readings.
- **Correlation Analysis:** Study relationships between solar metrics, temperature, and wind conditions.
- **Wind Analysis:** Visualize wind speed and direction distribution.
- **Temperature Analysis:** Examine relationships between humidity, temperature, and solar metrics.
- **Z-Score Analysis:** Identify data points significantly deviating from the mean.
- **Bubble Charts:** Explore complex relationships between multiple variables.

### **Step 3: Data Cleaning**
- Handle missing values and anomalies.
- Replace invalid or negative values.
- Standardize data for consistency.

### **Step 4: Insights and Recommendations**
- Identify high-potential regions for solar installation.
- Highlight trends in solar radiation and environmental factors.
- Provide actionable insights with visualizations and summaries.

### **Step 5: Report Preparation**
- Summarize key findings.
- Develop visualizations to support recommendations.
- Prepare a structured strategy report.

## **Project Structure**
```
moonlight-energy-solutions-analysis/
│
├── data/
│   └── sierraleone-bumbuna.csv             # Raw datasets
    └── benin-malanville.csv 
│
├── notebooks/
│   └── sierraleone-bumbuna.ipynb                  # Jupyter Notebook for EDA
    └── benin-malanville.ipynb 
│
├── src/
│   ├── data_preprocessing.py      # Script for data cleaning
│   ├── eda_visualizations.py      # Functions for EDA visualizations
│   └── analysis.py                # Core analysis scripts
│
├── results/
│   ├── visualizations/            # Saved plots and figures
│   └── insights_summary.txt       # Summary of insights
│
├── README.md                      # Project documentation
│
└── requirements.txt               # Python dependencies
```

## **Technologies Used**
- **Programming Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy
- **Tools:** Git, Jupyter Notebook

## **Getting Started**
1. Clone the repository:
   ```bash
   git clone https://github.com/asmegithub/10-Academy-week0.git
   cd moonlight-energy-solutions-analysis
   ```
2. Create a virtual environment and install dependencies:
   ```bash
   python3 -m venv env
   source env/bin/activate
   pip install -r requirements.txt
   ```
3. Run the analysis:
   - Open the Jupyter Notebook in the `notebooks/` directory.
   - Use scripts in the `src/` directory for preprocessing and visualization.

## **Key Findings**
- (Add a brief summary of key findings here after the analysis is complete.)

## **Recommendations**
- (Summarize actionable recommendations based on the analysis.)

## **License**
This project is licensed under the MIT License.

## **Contributors**
- **Asmare Zelalem** - Analytics Engineer

Feel free to contribute to this project by submitting pull requests or raising issues.