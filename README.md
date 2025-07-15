# Riyadh-POI-Exploritory-Data-Analysis
This repository presents the Exploratory Data Analysis (EDA) phase of a larger AI project titled:
"Personalized Points of Interest (POI) Recommendation System for Tourism in the Capital City of Saudi Arabia – Riyadh."
The project leverages historical check-in data to recommend personalized next locations to users using advanced AI techniques, aligning with Saudi Arabia’s Vision 2030 to enhance digital tourism and smart city infrastructure.

---

## 📄 Project Overview
The goal of the full project is to predict the next most likely Point of Interest (POI) a user might visit based on their location history, behaviors, and the structure of urban POIs in Riyadh. It combines:

- Graph-based models (Directed Acyclic Graphs, Personalized PageRank, Node2Vec)

- Sequence modeling (LSTM)

- Hybrid AI approaches (e.g., Node2Vec + LSTM)

The best performing model was Node2Vec + LSTM, achieving a MAE of 0.0852.

---

## 🗃️ Dataset Description

Real-world check-in data collected from the Swarm app on Foursquare, filtered for Riyadh, Saudi Arabia.

**Features include:**

- user_id: Unique identifier for each user

- poi_id: Identifier for each Point of Interest

- latitude, longitude: Coordinates of the POI

- timestamp: Time of visit

- category: Type of POI (e.g., Restaurant, Park, Mall)

- region: Geographical zone within Riyadh

---

## 📊 Exploratory Data Analysis (EDA)

As part of the team, my dedicated responsibility was conducting the full Exploratory Data Analysis (EDA).
The goal of this EDA was to explore the structure, distribution, and hidden patterns in the cleaned POI dataset. This phase was essential in shaping the feature engineering and model selection strategies.

**EDA Objectives:**
- Uncover patterns in user mobility and POI engagement

- Visualize category distributions and regional clustering

- Analyze temporal behaviors in tourism activity

- Generate insights that support predictive modeling

## 🔍 Analysis Highlights:
1. Descriptive Overview

- Examined dataset size, feature types, and user/POI count distributions

2. Category Analysis

- Identified most and least visited POI types

- Visualized category frequency with bar charts and pie charts

3. User Behavior Exploration

- Counted check-ins per user to reveal engagement patterns

- Detected outliers and frequent visitors

4. Temporal Patterns

- Analyzed check-ins by hour, weekday, and month

- Highlighted peak tourism periods in Riyadh

5. Geospatial Visualization

- Mapped POIs using plotly and folium

- Created density heatmaps to show POI clusters and hotspots

  ---

  

  
