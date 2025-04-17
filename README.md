# Housing-price-and-Covid_19
Categorizing the missing values in the dataset and aggregating the Covid data by state, age and number 

#Data Science House Price and Summary of the average number of COVID-19 cases by state

# Resources

*Data Source: Altschool

*Jupyter Notebook

*Pandas, Numpy and Matplotlib

# Overview/Introduction

The House_Price dataset contains the following columns with missing values:

location: 1 missing value
size: 16 missing values
society: 5,502 missing values
bath: 73 missing values
balcony: 609 missing values

# Categorization of Missing Values

Missing At Random (MAR):

location: The missing value could be related to other observed variables (e.g., properties without a specified location might be less desirable or in less popular areas).
size: The missing size could be influenced by other factors such as the type of area or society. For example, larger properties might be more likely to have size information available.
bath: The missing values in the number of bathrooms may be related to the type of property or its size. For instance, smaller properties may have fewer bathrooms, leading to missing data.
balcony: The absence of balcony information may correlate with the type of property or its price range. Properties with fewer amenities may have less reported balcony information.

Missing Not At Random (MNAR):

society: The missing values in the society column could be due to properties that are not part of any society or are in less developed areas, which may not be reported. This suggests that the missingness is related to the nature of the properties themselves, making it MNAR.

Missing Completely At Random (MCAR):

In this dataset, there are no clear indicators of missing values that would fall under MCAR, as the missingness appears to be related to other variables.

# Objectives

MAR: location, size, bath, balcony
MNAR: society
MCAR: None identified

# Summary of Average COVID-19 Cases by State

Efficiently summarize the average number of COVID-19 cases by state, I aggregated the data by state and calculated the average number of cases per state. Here are the key findings:

1. California:  
   - Highest average cases due to early outbreaks in counties like Santa Clara, Los Angeles, and San Francisco.  
   - Multiple counties reported cases, indicating widespread transmission.  

2. Washington:  
   - Significant early outbreaks, especially in King and Snohomish counties.  
   - High average cases, with King County being a major hotspot.  

3. New York:  
   - Rapid increase in cases, particularly in New York City and Westchester County.  
   - Emerging as a major hotspot by the end of the dataset.  

4.  Illinois:  
   - Concentrated cases in Cook County (Chicago area).  

5. Florida:  
   - Cases spread across multiple counties, including Broward and Miami-Dade.  

6. Other States:  
   - States like Texas, Massachusetts, and New Jersey also reported notable averages, though lower than the top states.  
   - Many states had sporadic cases, often linked to travel or localized outbreaks.  

# Key Observations:
- Early cases were concentrated in coastal states (California, Washington, New York).  
- The average cases per state varied widely, with some states reporting single-digit averages while others had much higher numbers.  
- The data reflects the initial phase of the pandemic in the U.S., where testing was limited and cases were underreported in many areas.  
# Insight:
This summary highlights the uneven geographic distribution of COVID-19 cases in early 2020. For a more detailed breakdown, focusing on counties within high-impact states would provide additional insights.  

Note: This data contain two dataset(House_Price and Us_Counties_2020_Covid.) The Us counties was not uploaded on the respository because it is bigger than 25MB 

![image](https://github.com/user-attachments/assets/78e98ee3-3417-4afb-9cdf-bfa05c14f5ff)

![image](https://github.com/user-attachments/assets/87d3b059-e293-4fce-a888-b0f27b491759)

![image](https://github.com/user-attachments/assets/aa628299-ed3c-47f8-8436-681419e2100a)


