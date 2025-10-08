# IBM Data Science Capstone Project  
## Predicting Falcon 9 First Stage Landings

### Project Summary

This capstone project addresses a real-world challenge in the commercial space industry: predicting whether the first stage of SpaceX’s Falcon 9 rocket will land successfully. The outcome of this prediction directly impacts launch cost estimation and competitive bidding strategies.

SpaceX offers orbital launches at approximately **$62 million** per mission, significantly undercutting traditional providers whose costs often exceed **$165 million**. This cost advantage is largely due to SpaceX’s ability to **reuse the rocket’s first stage**, contingent on a successful landing. Therefore, accurately forecasting landing outcomes is critical for any competitor seeking to challenge SpaceX’s pricing model.

In this project, I assume the role of a Data Scientist working for a startup aiming to enter the orbital launch market. My task is to build a predictive model that estimates the likelihood of a successful first-stage landing, using historical launch data and machine learning techniques. The insights generated will help the startup make informed decisions when bidding against SpaceX for launch contracts.

---

### Objective

To apply the full data science workflow to a real-world aerospace dataset in order to:

- Predict the likelihood of Falcon 9 first-stage landings  
- Estimate launch costs based on landing outcomes  
- Support strategic decision-making for a SpaceX competitor  

---

### Business Context

SpaceX’s reusability model is a game-changer. If the first stage lands, the cost of future launches drops dramatically. By predicting landing success, a rival company can simulate cost scenarios, assess risk, and optimize its bid strategy. This project demonstrates how data science can be leveraged for competitive advantage in a high-tech, high-cost industry.

---

### Methodology

This project follows the end-to-end data science lifecycle, including:

- **Data Collection**: Aggregating launch records, payload details, booster configurations, and landing outcomes  
- **Data Wrangling**: Cleaning and transforming raw data into structured formats  
- **Exploratory Data Analysis (EDA)**: Identifying trends, correlations, and anomalies  
- **Data Visualization**: Communicating insights through charts, maps, and dashboards  
- **Model Development**: Training classification models to predict binary outcomes (landed vs. did not land)  
- **Model Evaluation**: Assessing performance using accuracy, precision, recall, and confusion matrices  
- **Stakeholder Reporting**: Presenting results in a format suitable for executive decision-making  

---

### Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
- SQL for data querying  
- Folium for geospatial visualization  
- Jupyter Notebook for analysis and documentation  

---

### Key Deliverables

- Cleaned and structured SpaceX launch dataset  
- SQL queries for payload and launch site analysis  
- Folium maps showing launch site distribution  
- Visualizations comparing payload mass and landing outcomes  
- Classification models with performance metrics  
- Confusion matrix and accuracy evaluation  
- Final presentation summarizing insights and business implications  

---

### Strategic Impact

This project goes beyond technical modeling—it demonstrates how machine learning can inform real-world business strategy. By quantifying the likelihood of successful landings, we can simulate launch costs, benchmark against competitors, and support data-driven decisions in a rapidly evolving industry.
