### Becoming a data professional -- Insights from Kaggle 2020 Data science survey

#### Project Background and motivation
There are so many resources on the internet for learning Data science and well as a vast number of machine learning techniques from simple linear regression to advanced deep learning based methods. It may be very confusing for someone trying to break into the field to get a grasp of exactly what to learn. Since I'm trying to break into the field myself, I decided to explore Kaggle's 2020 data science survey. It consists of about 20,000 responses, both from students and professionals about their age, education ,job roles and large variety of other profession related topics.In this analysis, I tried looking at the professionals and data science practices of companies, both large and small and try to find patterns in professionals within a job role and across job roles

#### Questions I explore in this analysis
+ Some general statistics about the survey respondents
+ Salary information 
+ Ages of data professionals
+ Gender distribution
+ Country of residence
+ Educational qualifications 
+ Data professionals accross different sized companies -count,salary
+ ML practices of companies
+ Development Environments - what IDEs are used
+ Most Popular hosted notebooks
+ Coding Experience accross different roles
+ Popular Coding Languages
+ Popular visualization libraries
+ How much ML experience is required
+ Popular machine learning Frameworks
+ Choice of learning platforms

### Section 1: General information about the survey respondents

#### 1.1 Age
Here 69% of the respondents are below 35 years of age and 55% are below 30 years of age. This is inline with the fact that most data professions came into the spotlight very recently  

![](/images/img_1p1.PNG)

#### 1.2 Gender Distribution
Roughly 78% of the respondents were men, 19.4% were women and 1.8% were other genders, This is a trend commonly seen in other technical fields as well 

![](/images/image1p2.PNG)

#### 1.3 Country of Residence
Most of the participants were from India and u.S. followed by Brazil, Japan and U.K.

![](/images/img1p3.PNG)


### Section 2: A closer look at data professionals


#### Criteria for being considered as a data professional

For the purpose of this analysis, I'll consider anyone who has described their work in some form in Q23. There are a few people who seem to be employed, but haven't described their role. So I have omitted these people. The questions under Q23 were as follows

+ Analyze and understand data to influence product or business decisions

+ Build and/or run the data infrastructure that my business uses for storing, analyzing, and
  operationalizing data

+ Build prototypes to explore applying machine learning to new areas

+ Build and/or run a machine learning service that operationally improves my product or
  workflows

+ Experimentation and iteration to improve existing ML models

+ Do research that advances the state of the art of machine learning

+ None of these activities are an important part of my role at work

+ Other

After applying the above criteria, there were roughly 9142 data professionals among 20,000 respondents

#### 2.1 Salary Distribution
For compairing salaries accross different countries, I have converted salaries in usd to purchasing power parity using the BigMac index sine the value of a given amount of money,say $100 varies in different regions across the world. Henceforth, salary will be in number of mac units. Salary distribution for the entire sample is shown below. As expected, it is a right skewed distribution with a long tail. Majority of the people earn less than 50,000 units while there are extremely high earning individuals, earning as high as >300,000 units
![](/images/img_2p1.PNG)

#### 2.2 Age of professionals
Most professionals fall in the 25-29 years age group with 30-34 years and 22-24 years being the next highest groups. Overall more than half of the professionals are aged between 22 and 34 years

![](/images/image_2p2.PNG)

#### 2.3 Gender Distribution of professionals
Similar to the trend observed with the survey respondents, roughly 83% of the professionals are men,16% women and remaining 1% are other genders
![](/images/image_2p3.PNG)

#### 2.4 Pay variation with country
Here I plot the median salaries of each country to find out the where the median salaries for data professionals is the highest. Turns out US, Israel,UAE,Australia and Switzerland are countries with highest median salaries in the world. PPP here is calculated based on the big mac index which is a widely used number for assesing PPP. All aspects of cost of living may not be represented well by the index, but it gives a good rough estimate of the highest paying places in the world
![](/images/median_ppp.PNG)

#### 2.5 Level of formal education
Often newcomers in data related fields wonder how much formal education does one need to break into the field. From the data here, it can be seen that around 46% professionals have master's degrees, 27% having bachelor's degrees and 17% having a doctorate. Thus having higher education certainly seems to have a significant impact on one's career prospects in a data related field
![](/images/image_2p5.PNG)

#### 2.6 Distribution of job roles
Data scientists make up the largest propotion of professionals who work with data, followed by data analysts and software engineers. 
![](/images/image_2p6.PNG)

#### 2.7 Age and pay
Here I have plotted the median salaries of different age groups. In general it seems that pay increases with age and experience
![](/images/image_2p7.PNG)

#### 2.8 Responsibilities by job title

+ Here I try to explore what professionals do on a day to day basis. Analysing data for business decisions seems to be the most common responsibility accross majority of the job roles.This is not surprising since most time in the data science process is spent in understanding the data and deriving insights from it  

+ Data Analyst and Business Analyst roles seem very similar in terms of responsibilities  

+ Data enigineers and database engineers have the responsibility of building and maintaing data infrastructure which is less common in other roles  

+ Data Scientists and Machine learning engineers seem to have the widest variety of responsibilities

![](/images/image_2p8.PNG)

#### 2.9 Job title and education
Here I take a look at education of people across different job titles. Masters degree holders form the largest propotion of people across all job titles except for reseach scientists where majority of the people hold Phds
![](/images/image_2p9.PNG)

#### 2.10 Count of professionals across companies of different sizes
Here I take a look at the headcount of different job roles across companies of different sizes. It seems like large number of data scientists work in startups and big coorporations.Also data scientists form the major propotion of data professionals followed by Data Analysts and software engineers
![](/images/image_2p10.PNG)

#### 2.11 Pay variation accross companies of different sizes
Here I compare median salaries of professionals across organizations of different sizes. In general bigger companies tend to pay more than smaller ones.Also product/project managers seem to be the highest paid positions accross organizations of different sizes
![](/images/image_2p11.PNG)

#### 2.12 machine learning practices of companies of different sizes
The extent of machine learning usage is compared across companies of different sizes.It can be seen that big coorporations are the ones with well established ML procedures while smaller companies are still at an exploratory stages
![](/images/image_2p12.PNG)

#### 2.13 Preferred development environments
Jupyter notebook/ juputer lab is by far the most preferred tool for building data science workflows followed by vscode and pycharm
![](/images/image_2p13.PNG)

#### 2.14 Popular hosted notebooks
Colab and Kaggle notebooks seem to be the most popular hosted notebooks. It's surprising that almost 19% people dont use any of the hosted notebook services given the amount of compute power available for free
![](/images/image_2p14.PNG)

#### 2.15 Coding experience needed for different professions
It's an interesting question to ask how much coding experience is required to get into these fields.It can be seen that around 30% of pofessionals accross different job titles have less than 2 years of coding experience.
![](/images/image_2p15.PNG)

#### 2.16 Programming Languages to learn
Python is by far the most used language in data related jobs while SQL comes in at second. This is not surprising since SQL plays a mojor role in accessing data from large data warehouses. Thus knowing SQL goes a long way in boosting career prospects of data professionals
![](/images/image_2p16.PNG)

#### 2.17 Popular Visualization libraries
Matplotlib and Seaborn are the most used data visualization libraries since most people start out with these. Plotly produces interactve plots, but requires knowledge of data preprocessing to get certain types of visualizations. ggplot is a visualization library for R
![](/images/image_2p17.PNG)

#### 2.18 Years of Machine Learning experience across different professions
About 40% of the people in all professions have machine learning experience of less than 2 years.Professionals like data and business analysts mostly do not have machine learning experience. Also 2 years of coding experience is subjective and can mean different things for different individuals depending on where they studied and number of hours they put in. But 2 years of ML experience is a reasonable goal for people trying to get into the field to strive towards
![](/images/image_2p18.PNG)

#### 2.19 Usage of ML Frameworks
Scikit learn, Tensorflow and keras are the most popular ML Frameworks which is mostly what people learn while trying to get into this domain
![](/images/image_2p19.PNG)

#### 2.20 Preffered learning Platforms
Coursera seems to be the top platform for learning data science followed by Udemy and Kaggle.
![](/images/image_2p20.PNG)

#### 2.21
Despite the large number of sophistiacted ML algorithms, linear/logistic regression and tree based methods remain the top algorithms used for business purposes.This is because the results of these algorithms can be easily explained while more sophisticated deep learning methods may not be interpreted so readily.This also shows the importance of model interpretability for use in business cases
![](/images/image_2p21.PNG)
