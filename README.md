<img width="1122" height="800" alt="Resident Evil Analytics Dashboard" src="https://github.com/user-attachments/assets/cee752f8-3877-4a13-89bb-799bfac9059b" />


🎮 Resident Evil Data Analytics Dashboard
📌 Overview
This project demonstrates an end-to-end data analytics workflow, transforming raw data into meaningful insights and an interactive dashboard.
Using a dataset based on the Resident Evil game series (sourced from Kaggle), the project focuses on analyzing character activity, game engagement, and scene-level interactions.
________________________________________
🎯 Objective
To showcase practical skills in:
•	Data cleaning and transformation
•	Data modeling and merging
•	Exploratory data analysis
•	Dashboard development and storytelling
________________________________________
🛠️ Tech Stack
•	Python (Pandas, Matplotlib)
•	Jupyter Notebook
•	Microsoft Power BI
________________________________________
📂 Dataset
•	Source: Kaggle
•	Contains multiple related tables:
o	Games
o	Characters
o	Scenes
o	Interactions (linking characters, scenes, and games)
________________________________________
🔄 Workflow
1. Data Preparation (Python)
•	Loaded datasets using Pandas
•	Explored structure using .head() and .columns
•	Cleaned and standardized data
•	Merged multiple tables into a unified dataset
2. Exploratory Analysis
•	Identified top characters by appearances
•	Analyzed game-wise and scene-wise activity
•	Evaluated role distribution (Hero / Villain / Support)
•	Measured unique character presence per game
•	Performed time-based analysis using release years
3. Data Export
•	Generated a final cleaned dataset:
resident_evil_cleaned.csv
4. Dashboard Development (Power BI)
•	Built an interactive dashboard featuring:
o	KPI Cards (Total Activity, Characters, Game Releases)
o	Bar Charts (Character, Game, Scene analysis)
o	Pie Chart (Role distribution)
o	Slicers (Game, Role, Year filters)
•	Applied a custom dark-themed UI inspired by Resident Evil
________________________________________
📊 Key Insights
•	Certain characters dominate overall activity, indicating central roles in the storyline
•	A small number of game releases contribute disproportionately to total interactions
•	Hero roles significantly outnumber villains and support characters
•	Scene-level analysis highlights key narrative moments
•	Later releases show increased activity, suggesting richer content
________________________________________
📁 Project Structure
Resident-Evil-Project/
│
├── Resident_Evil_Project.ipynb
├── resident_evil_cleaned.csv
├── Resident_Evil_Dashboard.pbix
├── dashboard.png
└── README.md
________________________________________
📸 Dashboard Preview
(Insert dashboard screenshot here)
________________________________________
💡 Highlights
•	Demonstrates data integration across multiple tables
•	Combines Python analysis with Power BI visualization
•	Focuses on clear storytelling through data
•	Includes custom UI/UX design for dashboard presentation
________________________________________
🚀 Conclusion
This project highlights the ability to move from raw data to actionable insights while presenting results through an intuitive and visually engaging dashboard.
________________________________________
📌 Note
This project was developed as a self-initiated learning exercise, combining data analytics with a personal interest in gaming.
________________________________________

