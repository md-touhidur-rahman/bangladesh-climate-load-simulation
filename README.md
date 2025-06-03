Bangladesh Climate-Load Simulation

####### Overview  #######

This project simulates the coincidence of extreme ambient temperatures and high electrical load in Bangladesh to support energy infrastructure planning. Using historical weather data and synthetic load modeling, the analysis helps identify periods of stress for grid cooling systems — a critical concern as climate extremes increase.

### Use Case

Applicable in scenarios such as:

Grid cooling system sizing

STATCOM or HVAC stress tolerance design

Operational planning under climate volatility

Academic and industrial research in energy systems

### Dataset

Name: BD_weather.csv

Source: Mendeley Data (Bangladesh Meteorological Department)

Fields: Date, Temperature, Humidity, Rainfall, Station

Cities Used: Dhaka (main focus), optionally Rajshahi, Chittagong

###  Methodology

Simulate load patterns with seasonal variation

Define "extreme event" when:

Temperature > 85th percentile

Load > 90th percentile

Analyze and visualize occurrences

Group and interpret by month/season/year


###  Visualizations


Bar Chart  - Extreme events by month

Grouped Bars  - Binned events by 2-month range (e.g. Apr–May)

Heatmap  - Year vs Month matrix of extreme event frequency

Scatter Plot  - Temp vs Load with extreme events highlighted

## Plots are located in the /figures directory.


#### Folder Structure

bangladesh-climate-load-simulation/
├── data/
│   └── BD_weather.csv
├── notebooks/
│   └── climate_simulation.ipynb
├── figures/
│   ├── figure_1.png
│   ├── figure_2.png
│   ├── figure_3.png
│   └── figure_4.png
└── README.md

### Tech Stack

Python (Pandas, NumPy, Matplotlib, Seaborn)

Google Colab / Jupyter

GitHub for versioning

### Author

Md. Touhidur RahmanGitHub ProfileLinkedIn

### Status

Project complete and publicly available. Open for academic use and extension. Contributions welcome.
