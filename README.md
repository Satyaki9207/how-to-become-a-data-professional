### How to become a data professional -- Insights from Kaggle 2020 Data science survey

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
