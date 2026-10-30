# 🌾 Sri Lanka Paddy Yield & Climate Dashboard

### Exploring the relationship between paddy productivity, rainfall, and climate variability across Sri Lanka

[![Power
BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Business
Intelligence](https://img.shields.io/badge/Business-Intelligence-2563EB?style=for-the-badge)](#)
[![Sri
Lanka](https://img.shields.io/badge/Location-Sri%20Lanka-8D153A?style=for-the-badge)](#)

**An interactive Business Intelligence project built with Microsoft
Power BI**

------------------------------------------------------------------------
📌 Project Overview
Agriculture plays an important role in Sri Lanka's economy and food
security. Paddy cultivation mainly follows two cultivation seasons:
Maha and Yala. Rainfall variability and large-scale climate
phenomena can influence agricultural conditions and crop productivity.

This project brings together historical paddy yield data, rainfall
measurements, and climate indicators to explore patterns across Sri
Lanka's 25 administrative districts.

The interactive Power BI dashboard helps users investigate
district-level productivity, seasonal differences, rainfall patterns,
and relationships between agricultural output and climate indicators.
🎯 Project Objectives
- Compare paddy yield across Sri Lankan districts.
- Explore differences between the Maha and Yala cultivation seasons.
- Analyze historical rainfall patterns and paddy productivity.
- Examine rainfall-yield relationships.
- Explore climate indicators associated with El Niño, La Niña, and the
  Indian Ocean Dipole.
- Present the analysis through interactive and accessible
  visualizations.
📊 Dashboard Pages
The dashboard is organized into three analytical pages.
1. 🇱🇰 National Performance
A national overview of paddy productivity and district-level
performance.

Key visuals - National average paddy yield KPI. - Mean seasonal
rainfall KPI. - District-level yield comparison. - Long-term national
performance trends. - Maha and Yala seasonal distribution. - Interactive
filters for district, season, and year.

2. 🌧️ Seasonal Trends --- Rainfall vs. Output
Explores how rainfall and paddy production vary across cultivation
seasons and over time.

Key visuals - Historical rainfall and production trends. - Maha and
Yala rainfall distribution. - Seasonal rainfall comparisons. - Rainfall
distribution across historical cultivation cycles.

3. 🌏 Climate Analytics --- Statistical Correlations
Examines the relationship between paddy yield and selected climate
indicators.

Key visuals - Rainfall versus paddy yield scatter plot. - Oceanic
Niño Index (ONI) and average yield trends. - Dipole Mode Index (DMI)
analysis. - District-level comparison of climate conditions and
productivity.

🔍 Key Findings
The following figures summarize the findings reported in the project
analysis.
National and seasonal indicators
  Indicator                        Reported result
  National average paddy yield     3,542 kg/ha
Mean seasonal rainfall             813.76 mm
Maha average rainfall              988.68 mm
Yala average rainfall              638.84 mm
Maha average yield               3,592 kg/ha
Yala average yield               3,489 kg/ha
Rainfall-yield correlation            -0.165
District-level yield comparison
Higher average yields identified

  District         Average yield
  Hambantota         4,719 kg/ha
Polonnaruwa        4,636 kg/ha
Ampara             4,272 kg/ha
Anuradhapura       4,122 kg/ha

Lower average yields identified

  District     Average yield
  Galle          2,750 kg/ha
Kalutara       2,699 kg/ha
Colombo        2,903 kg/ha
💡 Main insights
- Higher rainfall does not necessarily correspond to higher paddy
  yield in the analyzed dataset.
- Maha receives more average seasonal rainfall than Yala.
- Yala's reported average yield remains relatively close to Maha's
  despite lower average rainfall.
- Irrigation and water management are important considerations when
  interpreting paddy productivity.
- ONI and DMI provide additional climate context for examining
  historical agricultural patterns.
Interpretation note: The reported rainfall-yield correlation is
descriptive. Correlation alone does not establish causation, and these
findings should be interpreted within the coverage and limitations of
the underlying datasets.

🗂️ Data Sources
The analysis combines information from the following sources, as
documented in the project report.
  Source                              Data used
  Department of Census and Statistics Historical district-level paddy
(DCS), Sri Lanka                    yield for Maha and Yala

  Department of Meteorology, Sri      Seasonal rainfall measurements
Lanka / CHIRPS                      
NOAA Physical Sciences Laboratory   Oceanic Niño Index (ONI) and Dipole
Mode Index (DMI)
Climate indicators
- ONI --- Oceanic Niño Index: Used to examine El Niño and La Niña
  conditions.
- DMI --- Dipole Mode Index: Used to examine Indian Ocean Dipole
  conditions.
⚙️ Data Preparation
Data preparation and transformation were carried out using Power
Query and Power BI.

The reported workflow included:
1. Preparing the agricultural yield and climate datasets.
2. Aligning monthly climate index information with Maha and Yala
   seasons.
3. Combining datasets using common fields: district, year, and season.
4. Converting district and season into categorical text fields.
5. Preparing year as a categorical field for filtering.
6. Converting yield, rainfall, ONI, and DMI fields into numerical
   types.
7. Using average aggregation for yield and rainfall metrics to support
   comparisons.
The report identifies paddy_climate_master.csv as the consolidated
analysis-ready dataset.
🧰 Tools & Technologies
  Tool / technology                   Use in this project
  Microsoft Power BI              Dashboard development and
interactive analysis

  Power Query                     Data cleaning, transformation, and
preparation

  CSV datasets                    Prepared data storage and
integration

  Data visualization              Exploring trends, comparisons, and
relationships
Business Intelligence           Communicating data-driven insights
🚀 Explore the Dashboard
1. Clone or download this repository.
2. Locate the Power BI .pbix file.
3. Open the file using Power BI Desktop.
4. If Power BI requests a data source, update the path to the dataset
   on your computer.
5. Navigate through the three report pages.
6. Use the district, season, and year filters to explore the data.
Compatibility: Power BI Desktop is primarily available for
Windows. Mac users can explore supported published reports through
Power BI Service, subject to account access, publishing permissions,
and report compatibility.

📁 Suggested Repository Structure
Sri-Lanka-Paddy-Yield-Climate-Dashboard/
│
├── README.md
├── 22cds0402.pbix
│
├── dataset/
│   └── paddy_climate_master.csv
│
├── images/
│   ├── national-performance.png
│   ├── seasonal-trends.png
│   └── climate-analytics.png
│
└── report/
    └── project-report.pdf
This is a suggested structure. Keep only files and folders that are
actually included in your repository, and update filenames where
necessary.
🌱 Recommendations Highlighted by the Analysis
The project report discusses several possible areas for further
attention:
- Strengthening irrigation and water management, particularly during
  the Yala season.
- Considering ONI and DMI information in agricultural planning.
- Improving drainage in areas affected by excessive rainfall.
- Exploring climate-informed agricultural advisory systems.
- Investigating data-driven approaches to crop insurance and
  agricultural risk management.
These are recommendations for consideration; the dashboard does not
evaluate the effectiveness of these interventions.
🔮 Future Improvements
- Include additional climate variables such as temperature, humidity,
  and solar radiation.
- Add more detailed geospatial visualizations.
- Explore predictive models for paddy yield forecasting.
- Integrate regularly updated agricultural and climate datasets.
- Develop an early-warning dashboard for agricultural climate risks.
👨‍💻 Project Information
  Detail              Information
  Project title   Sri Lanka Paddy Yield & Climate Dashboard
Course          Business Intelligence
Course code     DS4108
University      Sabaragamuwa University of Sri Lanka
Faculty         Faculty of Computing
Department      Department of Data Science
Student index   22CDS0402
Project type    Individual academic project
Main tool       Microsoft Power BI
👤 Author
Johen Perera
BSc (Hons) Data Science Undergraduate
Sabaragamuwa University of Sri Lanka
- GitHub: JohenPerera123
- LinkedIn: Johen Perera
📄 License & Data Usage
This repository is intended for academic and professional portfolio
purposes.

Please refer to the original data providers for licensing, attribution,
and redistribution conditions before reusing or sharing the source
datasets. The inclusion of a dataset in this repository should not be
interpreted as a claim of ownership.
### 🌾 Turning agricultural and climate data into meaningful insights

**Thank you for visiting this project!**

If you find this work interesting, feel free to explore the repository
and connect with me.
:::
