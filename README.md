# Seek Job Market analysis
For the course 7030ICT Introduction to Big Data Analytics at Griffith University, we analysed a dataset of the SEEK job market. It is an Australian platform where companies can post job announcements and job seekers can apply for a position. We focused on the Information & Communication Technology category. The project is divided in 3 parts. 

## Part 1 - Data Preparation and Pre-processing
The original dataset subject of this analysis is structured with 13 columns and with attributes to identify each posted position appropriately. Some of these attributes are the title of the position, the name of the company that opened the position, the date when the ad was published, the employment location, the classification and subclassification of the type of job, among others. Classification refers to the sector of work and the subclassification refers to the specific areas within the classification.

The sector of Information and Communication Technology, which was chosen for a more indepth analysis in this report, accommodates 22 subsectors, with Developers/Programmers the one with the highest number of posts (3,069 posts). The maximum salary is $250,000 per annum. The following assumptions are made: It is assumed that some companies opt to not include the salary in their job advertisement and that is the reason for zero values in the dataset. Additionally, since there is no further specification about this value in the dataset, it is assumed that 250 refers to $250,000, which would be the maximum annual income for some positions.

A horizontal bar chart was chosen to display the presence of null or missing values. The “Area” column contains a significant number of missing values. “Area” is a subcategory of “location” and therefore not an issue within the dataset. “Company” is likely absent due to some companies preferring not to display their company name.

## Part 2 - Data Analysis and Interpretation

The average salary with more job postings is $15,000, and the average salary with fewer job postings is $225,000. Another insight from this graph is that the average salary from $35,000 to $175,000 has similar job postings, except for the average salary of $45,000.


The “Full Time” category has more job postings, and the “Part-Time” category has fewer job postings in this dataset. 


The top five sectors in this dataset are "Information & Communication Technology", "Trades & Services", "Healthcare & Medical", "Hospitality & Tourism", and "Manufacturing, Transport & Logistics". The bottom five sectors in this dataset are "Self-Employment", "CEO & General Management", "Advertisement, Arts & Media", "Farming, Animals & Conservation", and "Science & Technology". Job postings of “CEO & General Management” seem to have a relationship between the frequency of job postings with an average salary of $225,000.


Melbourne was the location selected to visualise the market share in a pie chart. The top five sectors in Melbourne are "Information, Communication & Technology", "Hospitality &
Tourism", "Trade & Services", "Manufacturing, Transport & Logistics", and "Healthcare & Medical". The top five sectors in Melbourne are consistent with the top five sectors in Australia, with minor differences in the order of the ranking. Sectors with little significance in the dataset are grouped as “Other”. 


The locations “Port Headland, Karratha & Pilbara”, “Kalgoorlie, Goldfields & Esperance” and “ACT” have the most significant disparity between the highest salaries. The first two locations are likely due to mining-related jobs, whereas the last location offers Federal Government employment. On the other hand “Sunshine Coast”, “Gold Coast”, and “Mornington Peninsula & Bass Coast” have a lower disparity with the average salary, in part related to a larger tourism sector and a lack of white collar industry.


Acknowledgements: <br>
Gabriela Monteiro<br>
Julio Pimentel<br>
Daniel Spindler<br>
Henry Nguyen, Griffith University
