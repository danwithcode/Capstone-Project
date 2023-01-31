# Capstone-Project
	The purpose of this research is to build the best model to determine or classify if the first stage of a Falcon 9 rocket will land so that we can determine the cost of a launch.
	To achieve this we have gathered data from SpaceX REST API and web scraping of a Wikipedia page that contains data regarding the said project. The data that was collected from two sources were consolidated and cleaned. EDA was perfomred on the data using SQL and visualizations including folium  to map out the locations of the different launch sites. A Plotly Dash App were also created to easily interact, navigate, and visualize the data.
	After leaning the features that are relevant in classifying the success of a launch such as payload weight, launch site locations, orbit type, booster versions, etc., different machine learning models were tested to identify the best in classifying launches. The best models were LR, SVM, and KNN, all having 94% accuracy score.

