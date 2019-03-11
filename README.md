# Data_Science_Jobs

### Basic information
A repository containing some research done on the data related job openings in the US. This investigation was done on the Kaggle dataset ["Data Scientist Job Market in the U.S."](https://www.kaggle.com/sl6149/data-scientist-job-market-in-the-us). Here an author collected information about approx. 7000 data scientist jobs posted on [Indeed.com](https://indeed.com/) on August 3rd, 2018.  

### Motivation
This project is a part of Udacity "Data Scientist" Nanodegree. The task is to find an appropriate Dataset and analyze it using the CRISP-DM process.  
Since I am very interested in Data Science and currently learning it I am curious what are the requirements for Data Science Experts in the industry. In order to feed my curiosity I stated following questions and conducted research on them:  
* Which companies offer the most jobs for data scientist and in which U.S cities/states there are more chances to find a data related job?
* What are the expectations on work experience from various companies? 
* Which technical skills (Programming Languages / Tools) are required and how they are ranked? 
* Are there are any interesting wording differences between companies which might give some additional information about a company? 

### Summary
**Demand:** Amazon searches the most data experts. Ball Aerospace, Microsoft and Google are on places 2-4 with approx. 2 times fewer job posts in comparison to Amazon. NYC, Seatle, and Cambridge provide good chances to find a job. If U.S states are investigated, California is a clear leader with approx. 60% more jobs in comparison to 2nd Massachusets.  
**Requirements:** generally companies expect at least 4 years of work experience, however, the companies from pharmaceutic industry expect around 6-7 years of work experience. When technical requirements are investigated, approx. 50% of all ads require Python proficiency. Java is mentioned in 27% of job postings. AWS, SQL, and R with approx. 25%  are on places 3-5.  
Finally the **wording analysis** showed that Amazon and Google focus rather on Machine Learning, Walmart on Big Data. Facebook focuses on research and machine learning and often uses words like "world" and "help people". Microsoft, Broad Institute, McKinsey and Oath Inc. highlight the importance of teamwork.

### Installations:
This project was done in the Anaconda Environment using Jupyter Notebook with python 3.6. To work with this Notebook an install of the package "wordcloud" is required. This can be easily done using *pip install wordcloud* 

### Files:
This project contains a Jupyter Notebook **_2019-03-11 jobs.ipynb_** where all data preprocessing and analysis steps are conducted. The raw data with all job posts is stored in **_alldata.csv_**. For more information about this dataset refer to the [Kaggle page](https://www.kaggle.com/sl6149/data-scientist-job-market-in-the-us) of this dataset.

### Acknowledgments:
The project was conducted by myself.  
The data preprocessing step using regular expressions as well as word cloud implementation was inspired by the amazing [tutorial on NLP](https://www.youtube.com/watch?v=xvqsFTUsOmc) from Alice Zhao ( [GitHub Link](https://github.com/adashofdata/nlp-in-python-tutorial)  )
