# Earthquake Data Analysis (2010-2025)

### Overview
This project provides a detailed analysis of global seismic activity from 2010 to 2025. It aims to identify trends, patterns, and insights related to earthquake occurrences, magnitudes, impacts, and geographical distribution. The analysis supports disaster preparedness, risk assessment, and scientific research.

---

### Table of Contents
- [Introduction & Goals](#introduction--goals)
- [Data Sources](#data-sources)
- [Analysis Process](#analysis-process)
- [Tools Used](#tools-used)
- [Dataset Files](#dataset-files)
- [Key Findings](#key-findings)
- [Dashboard & Visualization](#dashboard--visualization)
- [Contributing](#contributing)
- [License](#license)

---

### Introduction & Goals
This analysis covers seismic activity over the last 15 years using data from USGS and NOAA. The main objectives are:
- To analyze earthquake frequency, magnitude, and impacts worldwide.
- To visualize seismic hotspots and temporal trends.
- To assess the human and structural impacts of significant earthquakes.
- To provide insightful visual dashboards for decision-makers.

---

### Data Sources
- **USGS Earthquake Hazards Program**: Provides real-time and historical earthquake data, including location, magnitude, depth, and time.
- **NOAA National Centers for Environmental Information (NCEI)**: Supplements with impact details such as casualties, injuries, and economic damages.

---

### Analysis Process
1. **Data Acquisition**: API scraping from USGS and NOAA downloads.
2. **Data Cleaning & Preprocessing**: Data type conversions, geospatial enrichment, handling missing values, and standardizing country names.
3. **Data Merging**: Combining seismic data with impact data using geographic and temporal keys.
4. **Exploratory Data Analysis (EDA)**: Investigating distribution, trends, and patterns:
   - Earthquake density and hotspots.
   - Country-wise earthquake frequency.
   - Magnitude distributions.
   - Impact assessments (deaths, injuries, damages).
5. **Visualization & Dashboard**: Creating interactive dashboards in Power BI for an overview of key insights.

---

### Tools Used
- **Python**: Data scraping, cleaning, and analysis.
- **Power BI**: Interactive dashboards and visualizations.
- **Microsoft PowerPoint**: Presentation of findings.

---

### Dataset Files
- `earthquake_data.csv`: Merged and cleaned earthquake data.
- Additional data files include APIs and supplementary impact datasets.

---

### Key Findings
- Earthquakes predominantly occur along tectonic plate boundaries like the Pacific Ring of Fire.
- Seismic activity has peaked notably in 2018.
- Higher magnitude earthquakes (above 8.0) tend to cause extensive damage and casualties.
- Japan experiences the highest physical and economic impacts.
- The overall damage from earthquakes (2010-2025) surpasses $260 billion, with Japan bearing most of the economic toll.
- Earthquake frequency and intensity fluctuate over years, highlighting the importance of preparedness in high-risk zones.

---

### Dashboard & Visualization
The project features a comprehensive Power BI dashboard that visualizes:
- Yearly earthquake counts and magnitudes.
- Geographical distribution and density.
- Impacts in terms of casualties and damages.
- Country-specific earthquake data.
- Correlation between magnitude and impact.

---

### Contributing
Contributions are welcome! Please fork the repository, create a pull request, or open an issue to suggest improvements.

---

### License
This project is licensed under the MIT License. See the LICENSE file for details.
