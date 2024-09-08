# :zap: Applied Data Science Capstone - IBM

# :clipboard: Project Overview

# :dart: Key Questions needs to be addressed:
1. How do variables such as payload mass, launch site, number of flights, and orbits affect the success of the first stage landing?
2. Does the rate of successful landings increase over the years?
3. What is the best algorithm that can be used for binary classification in this case?

# Approach process
<br/>

## 1. Collecting the Data (API) 
 - We collect SpaceX launch data using the SpaceX REST API, process it into a structured format, and clean the dataset by filtering for Falcon 9 launches and handling missing values. The cleaned data is used to analyze and predict rocket landing attempts.

## 2. Collecting Data with Webscraping
-  Performing web scraping to collect Falcon 9 historical launch records from a Wikipedia page titled `List of Falcon 9 and Falcon Heavy launches`
-  Parsed data will be stored in pandas DataFrame object
  
