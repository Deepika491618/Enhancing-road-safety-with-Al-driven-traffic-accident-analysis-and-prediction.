# Enhancing Road Safety with AI-driven Traffic Accident Analysis and Prediction

## Overview

This project aims to leverage Artificial Intelligence and data analytics to enhance road safety by analyzing traffic accident data and predicting high-risk situations. The solution includes machine learning models that classify accident severity and map accident hotspots, enabling authorities and citizens to take proactive measures.

## Objectives

- Analyze historical traffic accident data
- Predict accident severity based on input features like time, weather, and location
- Visualize accident hotspots using geolocation data
- Assist in road safety planning and policy-making

## Features

- Data preprocessing and feature engineering for traffic datasets
- Accident severity prediction using machine learning models (Random Forest)
- Interactive map visualizing accident hotspots (via Folium)
- (Optional) Web app built with Streamlit for real-time predictions

## Dataset

The dataset includes fields such as:
- Date and Time
- Weather Conditions
- Road Type
- Location (Latitude, Longitude)
- Accident Severity

**Note**: Replace `accident_data.csv` with your actual dataset.

## Tech Stack

- **Python**  
- **Pandas**, **NumPy** – Data processing  
- **Scikit-learn** – Machine learning  
- **Matplotlib**, **Seaborn** – Data visualization  
- **Folium** – Geo-spatial mapping  
- **Streamlit** – Web app interface (optional)

##Project structure 
├── accident_data.csv
├── model_train.py
├── streamlit_app.py
├── visualization_map.py
├── requirements.txt
└── README.md
