# United States Military Budget Forecast

![Alt text](https://static.wikia.nocookie.net/marvelcinematicuniverse/images/3/3f/Armed_Forces.png/revision/latest/scale-to-width-down/1000?cb=20230705194704)

## Introduction

Welcome to the United States Military Budget Forecast project repository! In this project, we delve into the historical trends of the United States military budget and utilize advanced machine learning techniques to forecast its trajectory for the next decade.
## Background

The United States military budget is a critical aspect of national security and geopolitical strategy. Understanding its historical trends and projecting future expenditures is essential for policy-making, resource allocation, and strategic planning.
## Objective

The primary objective of this project is to provide a comprehensive forecast of the United States military budget for the next 10 years. By leveraging historical data and employing machine learning models, specifically the FBProphet forecasting tool, we aim to offer valuable insights into the potential trajectory of military spending.
## Methodology

We begin by collecting and analyzing historical data on the United States total GDP. Following this, we employ FBProphet, a robust forecasting tool developed by Facebook, to model and predict future GDP trends. FBProphet is well-suited for time series data and offers powerful capabilities for trend analysis and forecasting. Now using linear regression we forecast the percent of GDP allotted for the next 10 years and then using those values we forecast the US Military Budget. 
## Repository Structure

This repository contains the following components:

- Data Analysis: Jupyter notebooks detailing the exploratory data analysis and preprocessing steps.
- Modeling: Python scripts or notebooks showcasing the implementation of the FBProphet model for budget forecasting.
- Results: Visualizations and summaries of the forecasted military budget for the next decade.
- Documentation: Additional documentation on data sources, methodology, and model evaluation.