🚀 Project Title: SpaceX Falcon 9 Launch Success Prediction
📌 Objective:
    Predict the success of Falcon 9 launches based on historical data.
    
    Use data science techniques including data wrangling, visualization, SQL, geospatial mapping, and machine learning.

📁 Project Structure:
    01_data_collection.ipynb: Web scraping launch data from Wikipedia.
    
    02_data_wrangling.ipynb: Cleaning and formatting data.
    
    03_eda_visuals.ipynb: Visual exploratory data analysis using seaborn and matplotlib.
    
    04_eda_sql.ipynb: SQL analysis using pandasql.
    
    05_folium_maps.ipynb: Mapping launch sites with Folium.
    
    06_dash_dashboard.py: Interactive dashboard using Plotly Dash.
    
    07_prediction_model.ipynb: Model building with logistic regression.
    
    08_model_evaluation.ipynb: Performance evaluation of the model.
    
    falcon9_cleaned.csv: Final cleaned dataset.
    
    presentation.pdf: Final PDF presentation for submission.
    
    requirements.txt: Required Python libraries.
    
    README.md: Project overview and instructions.

🧪 Tools & Technologies:
    Languages: Python
    
    Libraries: pandas, numpy, matplotlib, seaborn, sklearn, folium, plotly, dash, pandasql
    
    Others: Jupyter Notebook, GitHub, VS Code

🧼 Data Preprocessing:
    Removed null and irrelevant columns.
    
    Standardized column names.
    
    Converted mission outcomes into binary labels:
    
    1 = Success
    
    0 = Failure

📊 EDA Insights:
    Explored launch success by:
    
    Launch site
    
    Booster version
    
    Orbit type
    
    Payload mass
    
    Created bar charts, count plots, and heatmaps.

🧾 SQL-Based Analysis:
    Used pandasql for SQL queries like:
    
    Which launch site had the highest success rate?
    
    Orbit type and success relation.
    
    Average payload by orbit.

🗺 Geospatial Mapping:
    Created interactive maps using Folium.
    
    Marked launch sites:
    
    Green = Success
    
    Red = Failure

🤖 Predictive Modeling:
    Model: Logistic Regression
    
    Features: Payload, Orbit, Booster Version, Launch Site
    
    Target: Launch success (Class)
    
    Addressed class imbalance issues.
    
    Scaled features before training.

📈 Results:
    Visualized classification report and confusion matrix.
    
    Found Launch Site and Payload to be the most influential factors.
    
    Model performed well on test data.

📦 Deliverables:
    Python notebooks and cleaned dataset
    
    Interactive dashboard and folium map
    
    Final PDF presentation


