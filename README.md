**Project: Solar Radiation Measurement Data Analysis**

**Overview**

This project analyzes solar radiation measurement data, along with various environmental parameters, to gain insights into solar energy patterns and potential applications. Key areas of focus include:

**Exploratory Data Analysis (EDA):** Understanding data distribution, correlations, and anomalies.
**Statistical Analysis:** Identifying trends, patterns, and significant relationships.
**Visualization:** Creating informative plots and charts to communicate findings.

**Prerequisites**

* **Python 3.x:** Ensure Python is installed on your system.
* **Virtual Environment:** Recommended for managing project dependencies.
* **Required Libraries:**
  * `pandas`: Data manipulation and analysis.
  * `numpy`: Numerical operations.
  * `matplotlib`: Data visualization.
  * `seaborn`: Statistical visualizations.
  * `scikit-learn`: Machine learning algorithms (if applicable).

**Installation**

1. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate  # On Windows
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

**Dataset**

The dataset contains the following key columns:

* **Timestamp:** Date and time of each observation.
* **GHI:** Global Horizontal Irradiance (W/m²).
* **DNI:** Direct Normal Irradiance (W/m²).
* **DHI:** Diffuse Horizontal Irradiance (W/m²).
* **ModA/ModB:** Measurements from modules or sensors.
* **Tamb:** Ambient Temperature (°C).
* **RH:** Relative Humidity (%).
* **WS:** Wind Speed (m/s).
* **WSgust:** Maximum Wind Gust Speed (m/s).
* **WSstdev:** Standard Deviation of Wind Speed.
* **WD:** Wind Direction (°N (to east)).
* **WDstdev:** Standard Deviation of Wind Direction.
* **BP:** Barometric Pressure (hPa).
* **Cleaning:** Indicator for cleaning events.
* **Precipitation:** Precipitation rate (mm/min).
* **TModA/TModB:** Temperature of Modules A/B (°C).
* **Comments:** Additional notes.

**Running the Analysis**

1. **Exploratory Data Analysis (EDA):**
   * Explore data distribution, correlations, and outliers.
   * Identify potential data cleaning or preprocessing steps.
2. **Statistical Analysis:**
   * Calculate summary statistics (mean, median, standard deviation).
   * Conduct hypothesis testing or correlation analysis.
   * Explore seasonal variations or trends.
3. **Visualization:**
   * Create informative plots (e.g., histograms, scatter plots, time series).
   * Visualize relationships between variables.

**Contributing**

Contributions are welcome! 

**License**

This project is licensed under the MIT License. See the LICENSE file for more details.
