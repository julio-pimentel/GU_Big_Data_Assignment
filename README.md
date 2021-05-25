# SEEK Job Market analysis
For the course 7030ICT Introduction to Big Data Analytics at Griffith University, we analysed the SEEK job market dataset. It is an Australian platform where companies can post job announcements and job seekers can apply for a position. We focused on the Information & Communication Technology category. The project is divided into 3 parts. 

## Part 1 - Data Preparation and Pre-processing
The original dataset subject of this analysis is structured with 13 columns and with attributes to identify each posted position appropriately. The most relevant characteristics of the dataset are the title of the position, published date, location, classification and subclassification of the type of job. Classification refers to the sector of work, and subclassification refers to the specific areas within the classification.

The Information and Communication Technology sector, which was chosen for a more in-depth analysis in this report, accommodates 22 subsectors, with Developers/Programmers the highest number of posts (3,069 posts). The maximum salary is $250,000 per annum. The following assumptions are made: It is assumed that some companies opt to not include the salary in their job advertisement, and that is the reason for zero values in the dataset. Additionally, since there is no further specification about this value in the dataset, it is assumed that 250 refers to $250,000, which would be the maximum annual income for some positions.

A horizontal bar chart was chosen to display the presence of null or missing values. The "Area" column contains a significant number of missing values. "Area" is a subcategory of "location" and therefore not an issue within the dataset. "Company" is likely absent due to some companies preferring not to display their company name.

![](https://github.com/julio-pimentel/SEEK_Job_Market_analysis/blob/main/Plots/missing%20data%20in%20dataset.png)

## Part 2 - Data Analysis and Interpretation

The average salary with more job postings is $15,000, and the average salary with fewer job postings is $225,000. Another insight from this graph is that the average salary from $35,000 to $175,000 has similar job postings, except for the average salary of $45,000.

![](https://github.com/julio-pimentel/SEEK_Job_Market_analysis/blob/main/Plots/number%20job%20postings%20avg%20salary.png)

The "Full Time" category has more job postings, and the "Part-Time" type has fewer job postings in this dataset. 

![](https://github.com/julio-pimentel/SEEK_Job_Market_analysis/blob/main/Plots/job%20posts%20salary%20range.png)

The top five sectors in this dataset are "Information & Communication Technology", "Trades & Services", "Healthcare & Medical", "Hospitality & Tourism", and "Manufacturing, Transport & Logistics". The bottom five sectors in this dataset are "Self-Employment", "CEO & General Management", "Advertisement, Arts & Media", "Farming, Animals & Conservation", and "Science & Technology". Job postings of "CEO & General Management" seem to have a relationship between the frequency of job postings with an average salary of $225,000.

![](https://github.com/julio-pimentel/SEEK_Job_Market_analysis/blob/main/Plots/job%20posts%20by%20sector.png)

Melbourne was the location selected to visualise the market share in a pie chart. The top five sectors in Melbourne are "Information, Communication & Technology", "Hospitality & Tourism", "Trade & Services", "Manufacturing, Transport & Logistics", and "Healthcare & Medical". The top five sectors in Melbourne are consistent with the top five sectors in Australia, with minor differences in the ranking order. Sectors with little significance in the dataset are grouped as "Other". 

![](https://github.com/julio-pimentel/SEEK_Job_Market_analysis/blob/main/Plots/melbourne%20jobs%20classification.png)

The locations "Port Headland, Karratha & Pilbara", "Kalgoorlie, Goldfields & Esperance" and "ACT" have the most significant disparity between the highest salaries. The first two locations are likely due to mining-related jobs, whereas the last location offers Federal Government employment. On the other hand, "Sunshine Coast", "Gold Coast", and "Mornington Peninsula & Bass Coast" have a lower disparity with the average salary, in part related to a more critical tourism sector and a lack of white-collar industry.

![](https://github.com/julio-pimentel/SEEK_Job_Market_analysis/blob/main/Plots/locations%20avg%20highest%20salary.png)

## Part 3. Data Analysis and Interpretation 

We compared Adelaide and Gold Coast cities in terms of the number of job posts for four different job types. Overall, Adelaide has more job posts, and the ranking
of job types is the same in both cities. To begin, Adelaide is the city with the highest number of job posts, having 4,873 open positions. In contrast, the Gold Coast shows a total of 2,695 posts. The ranking of jobs in both cities follows the same pattern: full-time jobs occupy the first place in several job posts; followed by casual/vacation in the second place; contract/temp in the third place; and part-time in the last position. 

![](https://github.com/julio-pimentel/SEEK_Job_Market_analysis/blob/main/Plots/number%20posts%20per%20city%20by%20job%20type.png)

It is possible to see that the top five sectors are very similar in both cities, with some slight variations. It is evident that "Trades & Services" and "Healthcare & Medical" are equally important in both locations, representing a good number of job posts. 

![](https://github.com/julio-pimentel/SEEK_Job_Market_analysis/blob/main/Plots/number%20job%20posts%20Adelaide.png)
![](https://github.com/julio-pimentel/SEEK_Job_Market_analysis/blob/main/Plots/number%20job%20posts%20GC.png)

Although most of the job offers are for positions with low average salaries in both locations, it is evident that better salary options are available in Adelaide. As seen from the box plot, the median of the average salaries is higher in Adelaide, and the maximum salary is also higher. Therefore, it is possible to conclude that Adelaide is more well-paid than Gold Coast.

![](https://github.com/julio-pimentel/SEEK_Job_Market_analysis/blob/main/Plots/job%20salary%20range%20per%20city.png)

When analysing which city is better for employees, it is considered the probability of getting a job in each city. Therefore, the analysis observes the total number of job posts disregarding whether the job is white or blue-collar. In general, because the city of Adelaide is bigger than Gold Coast, it is expected to have more job opportunities available and, also, more options for higher salaries. Therefore, if someone is looking for a place with more chances to get a job and be well remunerated, Adelaide is a better option than Gold Coast. However, it is relevant to highlight that, when it comes to employability in the "Hospitality & Tourism" sector, Gold Coast can be a better choice than Adelaide due to the higher number of job posts for this sector. On the other hand, Adelaide offers far more opportunities for those pursuing a career in the industries of "Trades & Services", "Healthcare & Medical", "Manufacturing, Transport & Logistics", and "Information & Communication Technology".

The data covers six weeks and one day, with data for the entire month of October but only slightly less than half of November. With this in mind, a decision was made to average the job posts to a daily figure to compare across months, days of the week and day of the month to ensure meaningful insight. The average daily job post count was significantly higher in October than in November. Most jobs are posted on a weekday, with Wednesday, on average, the most popular day to post a job, with the weekend showing very few job posts. Averaging the daily job posts by day of the month shows a significant spike in the middle of the month, with a reasonably quiet period from the 20th to the 28th with very few job posts. The top 5 cities follow the same trends regarding the posting of jobs over time. However, there is a noticeable difference in the number of posts per city. Trend analysis further illustrates the low number of job posts, in the top 5 cities, in the latter part of October. In conclusion, the most defining feature of job posts over time is the harmonious trend of all top 5 cities over the period and Wednesday being the most popular day of the week a job was posted.

![](https://github.com/julio-pimentel/SEEK_Job_Market_analysis/blob/main/Plots/average%20job%20post%20per%20day.png)
![](https://github.com/julio-pimentel/SEEK_Job_Market_analysis/blob/main/Plots/job%20posts%20by%20dayweek.png)
![](https://github.com/julio-pimentel/SEEK_Job_Market_analysis/blob/main/Plots/trend%20job%20posts%20big%20cities.png)


Our group selected the variable "Information & Communication Technology" in the "Classification" column to make the TF/IDF analysis and extract relevant keywords on the
"Title" column. A word cloud chart was created with the 40 most relevant words obtained from the "Title" column. Words such as "developer", "analyst", "senior", "manager", and "engineer" were the most relevant. 

![](https://github.com/julio-pimentel/SEEK_Job_Market_analysis/blob/main/Plots/word%20cloud.png)

<br>Acknowledgements:</br>
<br>Gabriela Monteiro</br>
<br>Julio Pimentel</br>
<br>Daniel Spindler</br>
<br>Henry Nguyen, Griffith University</br>
