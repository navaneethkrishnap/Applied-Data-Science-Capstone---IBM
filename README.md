# :zap: Applied Data Science Capstone - IBM

# :clipboard: Project Overview
 We will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

# :dart: Key Questions needs to be addressed:
- How do variables such as payload mass, launch site, number of flights, and orbits affect the success of the first stage landing?
- What is the best fit predictive algorithm for this project?

# :arrow_down_small: Methodology

## 1. Collecting the Data (API) 
 - We collect SpaceX launch data using the SpaceX REST API, process it into a structured format, and clean the dataset by filtering for Falcon 9 launches and handling missing values. The cleaned data is used to analyze and predict rocket landing attempts.

## 2. Collecting Data with Webscraping
-  Performing web scraping to collect Falcon 9 historical launch records from a Wikipedia page titled `List of Falcon 9 and Falcon Heavy launches`
-  Parsed data will be stored in pandas DataFrame object


## 3. Data Wrangling 
 - We handle missing values and clean the data for further analysis.
 - Selecting a label for predictive supervised classification model.
## 4. EDA with SQL 
 - We Query the data and extract information about various variables at play using SQL
## 5. EDA with Visualisation
 - We Visualise the data using libraries here and observe what variables depicts.

## 6. Interactive Visual analytics and Plotly Dash
 - Building interactive visual maps, marking using folium and displaying interactive graphs such as pie charts or scatter plot using dash 
## 7. Predictive Analysis (Classification) 
 - Splitting dataset and selecting best hyperparameters and model score and accuracy are evaluated.

## By Navaneeth Krishna P 
### Thank You :blue_heart:
