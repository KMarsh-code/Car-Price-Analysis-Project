# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png) 

<p align="center">
  <img src="LB_image.jpg" alt="Project Logo" width="25%">
</p>

# Project Content
* [Readme.md](https://github.com/KMarsh-code/Car-Price-Analysis-Project/blob/3e97e0f315abb778f55a6fbf0548dea0c8fecbe5/README.md)
* [Project Board](https://github.com/KMarsh-code/Car-Price-Analysis-Project/blob/3e97e0f315abb778f55a6fbf0548dea0c8fecbe5/README.md)
* [Datasets](https://github.com/KMarsh-code/Car-Price-Analysis-Project/tree/3e97e0f315abb778f55a6fbf0548dea0c8fecbe5/Data)
* [Project Jupyter Notebook](https://github.com/KMarsh-code/Car-Price-Analysis-Project/blob/3e97e0f315abb778f55a6fbf0548dea0c8fecbe5/jupyter_notebooks/01_car_price_project.ipynb)
* [Visualizations](https://github.com/KMarsh-code/Car-Price-Analysis-Project/tree/3e97e0f315abb778f55a6fbf0548dea0c8fecbe5/Plots)
* [Tableau Dashboard Online](https://public.tableau.com/app/profile/maria.matsella/vizzes)
* [Tableau Dashboard Static Versions](https://github.com/KMarsh-code/Car-Price-Analysis-Project/tree/main/Dashboards)

# Car Price Analysis and Dashboard

This repository contains all of the files and documentation for the Car Price Analysis and Dashboard Hackathon project by **Team Ladybug**. The aims are to provide analyses and visualisations in the form of a data dashboard to be used as a tool in providing stakeholders with key insights linked to their business requirements, as detailed below.

## Dataset Content
This Car Price dataset contains information on the price of 205 cars, along with 24 features such as make/model, fuel type and engine size. Each row contains data on an individual car, and a detailed description of each feature in the dataset can be found in the [Data Dictionary](https://github.com/KMarsh-code/Car-Price-Analysis-Project/blob/3e97e0f315abb778f55a6fbf0548dea0c8fecbe5/Data/car_price_cleaned_data.csv). The dataset is freely available on [Kaggle](https://www.kaggle.com/datasets/imgowthamg/car-price) (date accessed: 06/10/2025).

## Business Requirements
The stakeholders (car company) are interested in understanding what the main factors are that influence the price of a car, to help them adjust their business strategy and maximise sales.

## Hypotheses and Approaches

**H1: Price segmentation through performance indicators**

Car prices follow a structured segmentation driven by engine capacity and performance metrics. Vehicles with larger engines and higher horsepower tend to belong to higher value segments, while smaller engine vehicles form the economy class.

**Visualisations:**
* Correlation Heatmap (EDA): Numeric variable relationships.
* Scatterplot (Tableau Dashboard): Engine size vs price

**H2: Performance, efficiency and value perception**

Higher horsepower leads to higher vehicle prices but lower fuel efficiency. Diesel vehicles maintain better mileage and higher price points compared to gas vehicles at similar performance levels.

**Visualisations:**
* Scatterplots (EDA): Horsepower vs city MPG; horsepower vs. price; engine size vs price; city MPG vs price
* Scatterplots (Tableau Dashboard): Horsepower vs city MPG; horsepower vs price; city MPG vs price (additional advanced visuals). 

**H3: Brand-level pricing and market positioning**

Car brands position themselves across the market spectrum according to perceived quality, design, and prestige. Luxury brands (Jaguar, Porsche, BMW) command higher median prices, while economy brands (Toyota, Nissan, Honda) maintain affordability through price consistency.

**Visualisations:**
* Histogram (EDA): Distribution of car prices with segments
* Barplot (Tableau Dashboard): Average car price per brand, including additional advanced visuals
* Doughnut chart (Tableau Dashboard): Average price by car body type

**H4: Regional distribution and market segmentation**
The global car market exhibits clear regional segmentation. European brands dominate the mid class and luxury tiers, while Asian manufacturers lead in the economy segment.

**Visualisations:**
* Global map (Tableau Dashboard): regional distribution of price segments

## Project Plan

The data was first extracted from Kaggle and then cleaned to improve its quality for further analysis. This cleaned data was uploaded into the [repository](https://github.com/KMarsh-code/Car-Price-Analysis-Project/blob/3e97e0f315abb778f55a6fbf0548dea0c8fecbe5/Data/car_price_cleaned_data.csv) for access by the wider team. Exploratory data analysis (EDA) was conducted to understand the key variables and their distributions, identify outliers, and perform any necessary transformations. These steps were completed in Python to maintain reproducibility, and can be found in the [jupyter_notebooks directory](https://github.com/KMarsh-code/Car-Price-Analysis-Project/blob/3e97e0f315abb778f55a6fbf0548dea0c8fecbe5/jupyter_notebooks/01_car_price_project.ipynb). The cleaned data was used to create interactive visualisations in a Tableau dashboard, which will be used to inform the hypotheses and provide insights to stakeholders for their business requirements. Tableau was chosen as the dashboarding tool as it is widely used in business and provides an intuitive platform for data storytelling. The dashboard associated with this project is publicly available here: [Online Dashboard](https://public.tableau.com/app/profile/maria.matsella/vizzes). Static versions of the dashboard visualisations are stored [here](https://github.com/KMarsh-code/Car-Price-Analysis-Project/tree/main/Dashboards).

## The rationale to map the business requirements to the Data Visualisations

To meet our business goal of understanding the factors that influence car pricing and identify brand positioning, we focused our analysis on features that demonstrate strong statistical relationships with price. This ensures that insights are both data-driven and actionable.

The following visualisations were used to support this analysis:
* Pairplot of key numeric features: Provided a holistic view of variable relationships and helped confirm linear patterns (e.g., between engine size and price).
* Correlation heatmap: Quantified the strength of relationships, helping us identify the most predictive variables for price modeling.
* Regression plots: Showed clear linear trends between price and both horsepower and engine size, confirming these as reliable indicators for premium pricing.
* City MPG vs Horsepower: Illustrated the performance-efficiency trade-off, valuable for market segmentation strategies.
* Price Distribution with Segments: Helped identify pricing clusters for low-, mid-, and high-end vehicles.
* Brand vs Average Price: Revealed brand positioning in terms of pricing, useful for competitor benchmarking and marketing focus.

## Analysis techniques used

* Visual Studio Code
* Python
* Jupyter notebook
* ChatGPT
* GitHub
* Tableau
* PowerPoint

## Summary of Findings

The project presents a connected analysis of vehicle pricing using Python and Tableau. It begins with correlation based segmentation and progresses through performance efficiency relationships, brand perception, and regional dynamics. The findings confirm that performance and engine size drive baseline pricing; fuel efficiency inversely affects perceived value; brand reputation increases price tolerance; and regional origin reinforces market segmentation. This integrated approach combines analytics and business interpretation to offer actionable insights into how the automotive industry positions and prices its products globally.

## Ethical considerations

The dataset is publicly available and contains no private data on individuals.

## Dashboard Design
### 1.	Main Dashboard – “Car Price Analysis”
**Title:** Car Price Analysis: Understanding Global Pricing Patterns, Brand Positioning & Market Segmentation

**Widgets & Visual Blocks:**
- Bar chart: Median Price for Car Brands
- Map: Regional Distribution of Car Market Segments
- Boxplot: Brand-Level Pricing Tiers
- Indicator: Median Price + Luxury Market Share
- Scatter plots with regression lines:
	- Engine Size vs Price
	- Horsepower vs City MPG
	- Horsepower vs Price
	- Highway MPG vs Price
	- Stacked bar chart: Avg. Price by Region Group and Price Segment
	- Filters: Fuel Type, Car Body, Brand

### 2.	Engine Size vs Price
- Focus: Displays the correlation between engine size and car price, differentiated by fuel type (gas/diesel).
- Elements: Scatter plot with regression lines for each fuel type, dot size = horsepower.
### 3.	Horsepower vs Price
- Focus: Examines how horsepower influences price.
- Elements: Colored scatter plot (by fuel type), dot size = price, regression lines for each fuel type.
### 4.	Horsepower vs City MPG
- Focus: Highlights the trade-off between engine performance (horsepower) and fuel efficiency (MPG).
- Elements: Scatter plot with trendlines, bubble size = price, color = fuel type.
### 5.	Highway MPG vs Price
- Focus: Shows how highway fuel efficiency impacts car pricing.
- Elements: Scatter plot with linear trendlines, bubble size = price, fuel type color-coded.
### 6.	Pricing Distribution by Car Segment and Region
- Focus: Illustrates pricing stratification by brand, region, and segment (economy, mid-class, luxury).
- Elements: Bar plots, boxplots, and color legends.

**Communication Strategy: Technical vs Non-Technical Audiences**

To ensure accessibility across audiences, the dashboard was designed with intuitive layouts, consistent color schemes, and clear titles and tooltips. For technical audiences, scatter plots with regression lines, segmentation by fuel type, and axis granularity provide analytical depth. Meanwhile, non-technical stakeholders can easily interpret pricing trends through simplified bar charts, median value indicators, and regional maps. The combination of performance (e.g., horsepower, engine size) and economic indicators (e.g., fuel type, MPG, price) enables both strategic and operational insight sharing.
 

## Development Roadmap

Working on a hackathon project as a small, fully remote team was challenging as it is a very fast-paced situation where communication is vital. We kept up to date with progress by having regular team meetings throughout the day, as well a a dedicated team discord channel where we could post issues or updates at any time. We also maintained a project board where progress could be tracked in real time. Using Tableau for the purposes of this hackathon was a steep learning curve, but provided an excellent opportunity for growth. In the future, we could expand on the skills used in the dashboard tools to include forecasting with temporal data.

## Main Data Analysis Libraries
* Pandas
* Numpy
* Plotly
* Seabon
* Matplotlib
* Tableau

## Credits  

### Contributions:

**Team ladybug**
* Data Architect - Yulia Shutko
* Data Analyst - Maria-Marsella Gounaridou
* Data Analyst - Ifrah Mohamed
* Project Manager - Kirsty Marsh

### Resources:

* [The Code Institute](https://codeinstitute.net/) Learning Management System
* [VS Code](https://code.visualstudio.com/) was used to write the code
* [ChatGPT](https://chatgpt.com/) was used to generate and debug code
* [README](https://github.com/Code-Institute-Solutions/da-README-template) template
* [Kaggle](https://www.kaggle.com/datasets/imgowthamg/car-price) data set was used for this project
* [Logo Image](https://www.vecteezy.com/vector-art/17461005-cute-ladybug-insect-animal-animated-vector-illustration)


