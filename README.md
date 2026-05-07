# Analysis-of-Fragmented-Care-in-the-Stormont-Vail-Health-System

This repository contains an R Markdown and Jupyter notebook used for the analysis and visualization of fragmented care in the Stormont Vail Health System, along with a presentation summarizing the results.

# Repository Structure

* Exploratory.Rmd - R Markdown featuring the exploratory data analysis behind this project.
* Analysis.ipynb - Jupyter Notebook featuring the in depth analysis and categorization of fragmented care.

# What Exploratory.Rmd Does

* Creates a heatmap for patient distance from nearest SVH hospital.
* Creates a scatter plot that shows the inverse correlation between a patient's distance to the nearest SVH hospital and the number of encounters they have had with SVH.
* Creates a scatter plot that shows the correlation between a patient's income and the number of encounters they have had with SVH.
* Creates a bar chart that visualizes how limited access to reliable transport is correlated with higher numbers of encounters with the SVH system.
* Creates a box and whisker plot that visualizes how limited access to reliable transport is correlated with higher numbers of encounters with unique specialists with the SVH system.

# What Analysis.ipynb Does

* Separates all patients into 4 Normalized Categories of Fragmentation based on number of different types of visits, the number of different types of specialists visited, the number of different departments visited, the number of different healthcare providers visited, and total number of diagnoses given. 
* Creates a radar chart that visualizes the separation between the categories of Low, Medium-Low, Medium-High, and High.
* Utilizes Neo4j Aura API to construct a knowledge graph which demonstrates how the patients in each category tend to get different types of care with different patterns of visitation.
  
