# ACC102_Track2 Github Data Analysis Project: Milk Tea Brand Store Data Analysis
## Problem 
This project analyses the total number of stores of Chinese milk tea chain brands, city cover, and average price.
## Data
Source: public milk tea industry dataset( https://stores.geohey.com/ranklist )
Access data: 19 April 2026
Key fields: Brand name, total store count, covered city number, average drink price
## Methods
Library Import: Import core Python libraries.
Data Loading: Read and load the raw milk tea dataset in CSV format using pandas function.
Data Cleaning: First, remove rows with missing values to eliminate incomplete data. Second, filter out invalid CHinese-onlynames and mixed Chinese-Eglish names, retain valid English brand names containong spaces.
Data Sorting: Sort the cleaned dataset by "Store_Count" in descending order. 
Data Visualization:First, generate bar charts to observe the relationship between store count and average price.Second, create a scatter plot to analyze the correlation between store count and city coverage. Third, adjusti chart parameters to optimize visual presentation.
## Key Findings
First, MIXUE maitains the lowest average product price among all milk tea brands, yet holds an abusolutely leading position in total store quantity.  
Second, there is a distinct positive correlation between a brand store count and its city coverage scope.
Third, low-priced milk tea brands achieve dramaticaly larger operational store scales compared whith high-priced brands.
## Product link
Github responsitory link: https://github.com/huzhang117/ACC102_Track2-/edit/main/README.md
Video link:https://b23.tv/wGzNfST
## Limitations & next steps
Limitations: The dataset is limitede by incomplete raw data. Excesive invalid or messy data was removed during cleaning, which results small final sample size.Thus, the fundings cannot fully represent the entire milk tea market.
Next steps: Add city level information and store opening time data to make the analysis more comprehensive.
