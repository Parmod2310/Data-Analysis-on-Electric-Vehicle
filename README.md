# Electric Vehicle Data Analysis 🚗🔋

## Internship Work at Innomatics Research Labs

###  📋 Table of Contents
- [Project Overview](@project-overview)
- [Project Motivation](@project-motivation)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
  
## 📌 Project Overview
This project involves a comprehensive exploratory data analysis (EDA) of Electric Vehicle (EV) data from 1997 to 2011. The analysis examines the growth and distribution of EVs over the years and across different locations, using various visualizations, including a Choropleth Map and an animated Racing Bar Plot.

## 💡 Project Motivation
With the increasing global adoption of electric vehicles, analyzing historical data is essential for understanding trends, preferences, and growth patterns in the EV market. This analysis provides insights into the development of the EV industry and its geographical spread, helping inform further research and business decisions.

## ✨ Features
1. Exploratory Data Analysis (EDA): Univariate and Bivariate analysis to understand distributions and relationships within the data.
2. Choropleth Map: Visualizes the geographical distribution of EVs.
3. Racing Bar Plot Animation: Depicts the evolution of EV makes over time.
4. Interactive Visualizations: Utilizes Plotly for enhanced interactivity in maps and animations.
5. Clean Code and Modular Structure: Well-organized code with detailed comments and a modular structure for easy navigation.
   
## 📊 Dataset
#### The dataset contains information about Electric Vehicles from 1997 to 2023. Key columns include:

- **Location**: Geographical area where the EV is located.
- **Model Year**: The year the EV data was recorded.
- **Make**: The make or brand of the EV.
- **Other Features**: Additional relevant features aiding in analysis (e.g., vehicle type, model).
 
## ⚙️ Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Required Python libraries: pandas, seaborn, matplotlib, plotly
### Clone the Repository
```bash
git clone https://github.com/your-username/electric-vehicle-data-analysis.git
cd electric-vehicle-data-analysis
```
### Install Dependencies
Install the necessary Python libraries:
```bash
pip install -r requirements.txt
```
## 🚀 Usage
1. **Data Analysis**
- Run the EDA notebook to perform univariate and bivariate analysis.
- Use histograms, count plots, scatter plots, and heatmaps to explore the data distribution and relationships.
2. **Visualizations**
- Use choropleth_map.py to generate an interactive Choropleth Map displaying EV counts by location.
- Run racing_bar_plot.py to visualize the animated Racing Bar Plot, highlighting the evolution of EV makes over the years.
3. **View the Results**
- The visualizations are interactive, allowing you to explore trends by hovering over elements for more details.
- The Racing Bar Plot can be saved as a video or animated GIF for presentation purposes.
## 📈 Results
### Key Findings
- The EV distribution varies significantly by location, with certain regions showing higher adoption.
Over time, the diversity in EV makes has increased, reflecting the industry's growth and the entry of new manufacturers.
Visualizations
- Choropleth Map: Shows the geographical spread of EVs, revealing adoption hotspots.
Racing Bar Plot: Animates the evolution of EV manufacturers, illustrating the rise and fall of brands over time.
## 🤝 Contributing
We welcome contributions to improve this project! If you have any suggestions or would like to collaborate, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or improvement:
```bash
git checkout -b feature-name
```
3. Commit your changes:
``` bash
git commit -am 'Add new feature'
```
4. Push to the branch:
```bash
git push origin feature-name
```
5. Submit a pull request.

## 📜 License
This project is licensed under the MIT License. See the **LICENSE** file for details.

##### You’re now ready to start analyzing Electric Vehicle data! If you have any questions, feel free to reach out or open an issue. 🚗🔋📊
