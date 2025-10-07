# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Project Content
* [Readme.md](https://github.com/KMarsh-code/Car-Price-Analysis-Project/blob/3e97e0f315abb778f55a6fbf0548dea0c8fecbe5/README.md)
* [Project Board](https://github.com/KMarsh-code/Car-Price-Analysis-Project/blob/3e97e0f315abb778f55a6fbf0548dea0c8fecbe5/README.md)
* [Datasets](https://github.com/KMarsh-code/Car-Price-Analysis-Project/tree/3e97e0f315abb778f55a6fbf0548dea0c8fecbe5/Data)
* [Project Jupyter Notebook](https://github.com/KMarsh-code/Car-Price-Analysis-Project/blob/3e97e0f315abb778f55a6fbf0548dea0c8fecbe5/jupyter_notebooks/01_car_price_project.ipynb)
* [Visualizations](https://github.com/KMarsh-code/Car-Price-Analysis-Project/tree/3e97e0f315abb778f55a6fbf0548dea0c8fecbe5/Plots)
* [Tableau Dashboards]()

# Car Price Analysis and Dashboard

This repository contains all of the files and documentation for the Car Price Analysis and Dashboard Hackathon project. The aims are to provide analyses and visualisations in the form of a data dashboard to be used as a tool in providing stakeholders with key insights linked to their business requirements, as detailed below.

## Dataset Content
This Car Price dataset contains information on the price of 205 cars, along with 24 features such as make/model, fuel type and engine size. Each row contains data on an individual car, and a detailed description of each feature in the dataset can be found in the Data directory [Data Dictionary](https://github.com/KMarsh-code/Car-Price-Analysis-Project/blob/3e97e0f315abb778f55a6fbf0548dea0c8fecbe5/Data/car_price_cleaned_data.csv). The dataset is freely available on [Kaggle](https://www.kaggle.com/datasets/imgowthamg/car-price) (date accessed: 06/10/2025).


## Business Requirements
The stakeholders (car company) are interested in understanding what the main factors are that influence the price of a car, to help them adjust their business strategy and maximise sales.


## Hypothesis and Approaches
**to be added**

## Project Plan

The data was first extracted from Kaggle and then cleaned to improve its quality for further analysis. This cleaned data was uploaded into the [repository](https://github.com/KMarsh-code/Car-Price-Analysis-Project/blob/3e97e0f315abb778f55a6fbf0548dea0c8fecbe5/Data/car_price_cleaned_data.csv) for access by the wider team. Exploratory data analysis (EDA) was conducted to understand the key variables and their distributions, identify outliers, and perform any necessary transformations. These steps were completed in Python to maintain reproducibility, and can be found in the [jupyter_notebooks directory](https://github.com/KMarsh-code/Car-Price-Analysis-Project/blob/3e97e0f315abb778f55a6fbf0548dea0c8fecbe5/jupyter_notebooks/01_car_price_project.ipynb). The cleaned data was used to create interactive visualisations in a Tableau dashboard, which will be used to inform the hypotheses and provide insights to stakeholders for their business requirements. Tableau was chosen as the dashboarding tool as it is widely used in business and provides an intuitive platform for data storytelling. The dashboard associated with this project is publicly available here: **XXX**

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
**to be added**

## Ethical considerations

The dataset is publicly available and contains no private data on individuals.

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap

* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Main Data Analysis Libraries
* Pandas
* Numpy
* Plotly
* Seabon
* Matplotlib
* Tableau

## Credits  

### Contributions:

* Data Architect - Yulia Shutko
* Data Analyst - Maria-Marsella Gounaridou
* Data Analyst - Ifrah Mohamed
* Project Manager - Kirsty Marsh

### Resources:

* [The Code Institute](https://codeinstitute.net/) Learning Management System
* [VS Code](https://code.visualstudio.com/) was used to wite the code
* [ChatGPT](https://chatgpt.com/) was used to generate and debug code
* [README](https://github.com/Code-Institute-Solutions/da-README-template) template
* [Kaggle](https://www.kaggle.com/datasets/imgowthamg/car-price) data set was used for this project

## Acknowledgements (optional)
* Thank the people who provided support through this project.
