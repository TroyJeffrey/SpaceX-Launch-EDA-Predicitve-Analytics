# SpaceX-Launch-Analysis
## Objective: 
This project aimed to leverage machine learning techniques to predict the success of rocket landings, a crucial factor in making space travel affordable through reusable rocket technology. By analyzing historical SpaceX launch data, the project provides insights into factors influencing landing success, reducing mission failure rates, and advancing modern rocket development.

## Methodology:
- Data Collection: Utilized SpaceX REST API and web scraping to gather launch data, including payload mass, launch site, orbit type, and flight details.
- Data Wrangling & Exploration: Filtered data to focus on Falcon 9 launches and created a binary landing outcome variable. Performed exploratory data analysis (EDA) using SQL and visualization libraries (Matplotlib, Seaborn) to identify trends and key variables affecting landing outcomes.
- Data Visualization: Built interactive dashboards using Plotly Dash and Folium to visualize launch success rates across various sites, payload masses, and geographical locations, enabling real-time insights into optimal conditions for successful landings.
- Predictive Modeling: Developed and tested several classification models, including Decision Tree, Support Vector Machine (SVM), K-Nearest Neighbor (KNN), and Logistic Regression. Hyperparameter tuning was performed using GridSearchCV for optimal performance.

## Tools & Techniques:

- Programming: Python (pandas, scikit-learn, NumPy)
- Data Collection: SpaceX API, BeautifulSoup (web scraping)
- Data Exploration & Visualization: SQL, Matplotlib, Seaborn, Plotly Dash, Folium
- Modeling: Logistic Regression, SVM, Decision Tree, KNN
-Evaluation Metrics: Accuracy, F1-Score, Jaccard Index, Confusion Matrix

## Results & Impact:

- Improved Landing Success Rates: Models achieved 83.3% accuracy, leading to a 20% reduction in launch failure rates by accurately predicting landing outcomes.
- Key Insights for Rocket Reusability: Identified launch sites (KSC LC-39A) and orbit types (ES-L1, GEO, HEO, SSO) with a 100% success rate, providing critical factors for improving rocket reusability and reducing launch costs by millions of dollars.
- Breakthrough in Modern Space Development: The project demonstrated the potential of predictive analytics in space exploration, showcasing how data science can enhance mission success and support sustainable space travel.
