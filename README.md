# Glassdoor Company Review Analysis with NLP

This project is a Glassdoor employer review analysis on a large company. The goals are to build a workflow for similar Glassdoor company review tasks and help employers gain insights on their employee engagement. Although the data in this project is about one company, the techniques can be applied to any company that has enough Glassdoor reviews. Specifically, we will find answer to these questions: what employees like and dislike about their company? Has the company’s reputation gotten better or worse over the years? What are the keywords that employees say about this company? What can this company do to improve employee engagement?


## Project Overview:
The analysis consists of 3 Jupyter notebooks.
1. Data Cleaning and Exploratory Data Analysis<br>
2. Sentiment Analysis<br>
3. Keywords Extraction and Topic Modeling<br>


## Key Findings:
#### 1. What employees like and dislike about this company?<br>
Employees love the good pay, generous benefits, profit sharing and a good work-life balance. Employees from call centers complain about the low pay, long hours handling phone calls and the management team. Project managers complain about the upper management team. Other anonymous employees which could consist of any job family complain about the aforementioned issues plus red tape of large corporations and constant changes.
#### 2. Has the company’s reputation gotten better or worse in the recent year?<br>
This company did great compared to other companies’ average ratings on Glassdoor. The majority of employees are satisfied with the company. Its rating has been increasing since 2008 with small dips in 2011, 2013 and 2017.
#### 3. Which job families have the highest and lowest satisfaction rates?<br>
Among the most frequent job titles, Financial Representatives have the lowest satisfaction and Software Engineers give the highest ratings. Since we know the negative comments are from call center employees, our best guess is Financial Representatives work in the call center.
![](figures/freq10_job_pol_sub.png)
#### 4. What are the keywords that people say about this company?<br>
The keywords are most clear in the top bi-gram plots. They are: good salary, good benefits, generous profit sharing, big company, work-life balance, upper management, low pay, long hours.
#### 5. What can this company do to improve employee engagement?<br>
This analysis identified the negative comments are mainly from call center employees. We suggest the company look into the salary, working hours and find solutions to address these issues. If call center employee engagement increases, the total employee engagement will increase significantly.
![](figures/top20_bigram_con.png)

## Project Contribution:
This project has created a standard workflow for similar tasks. Given any company’s Glassdoor review data, the same structure and code can be applied with little tweaks, especially the data cleaning code blocks can be used without change since all Glassdoor review data follow the same format.


## Limitations:
#### 1. Limitations: <br>
Since there are 1578 unhappy employees submitted anonymously, we can’t do a more granular analysis on specific job families. It is our assumption that Financial Representatives work in call centers, if this is untrue, we would need to analyze this further.
#### 2. Future Work: <br>
We could do a similar analysis on this company's competitor and see how they compare and what they can learn from each other.

## Acknowledgement:
I would like to extend my appreciation to Glassdoor for allowing me web scraping the data, so I could conduct this analysis. 
