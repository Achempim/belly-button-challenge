# belly-button-challenge

Project Overview
This repository contains an interactive dashboard for exploring the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The dashboard allows users to view data related to microbial species present in each sample through a bar chart, bubble chart, and demographic information panel.

Features:
Interactive Dropdown: Select different samples to update the charts and metadata.
Bar Chart: Displays the top 10 OTUs for the selected sample.
Bubble Chart: Visualizes all OTUs for the selected sample.
Demographic Metadata: Displays sample-specific demographic information.
Code Structure
The key scripts for this project are located in the following files:

JavaScript Code: All JavaScript logic for fetching the dataset, building charts, and handling interactions is in the file app.js located in the root directory.

Code Source: The D3.js code in app.js was custom-written to dynamically fetch and visualize the Belly Button Biodiversity dataset as specified in the project requirements.
Location: app.js
HTML and CSS: The HTML structure and basic styling for the dashboard are in index.html and style.css located in the root directory.

Location: index.html | style.css
Dataset
The dataset is fetched dynamically from the following URL: samples.json.

How to Run
Clone the repository to your local machine: git clone using the (url)
Deployment
This project is deployed via GitHub Pages. You can view the live app here.

Notes
The interactive charts and data visualization components are built using the D3.js and Plotly.js libraries.
Source Code for Charts: The code responsible for building the bar chart, bubble chart, and demographic panel can be found in the buildCharts and buildMetadata functions inside the app.js file.
