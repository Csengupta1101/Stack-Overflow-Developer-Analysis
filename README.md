# The Stack Overflow Data Set Analysis –

## Dataset Overview –

The dataset comprises of people and their background applying for a job at  Stack overflow. Their entire educational  and professional background with personal details are shared to evaluate how fit they will be in the organization.

### Problem Statement – 

We need to perform detailed analysis of the data points shared with us. Which aspect is impacting which ones to determine one’s credibility or the ability to secure a job in the organization needs to be scrutinized. 

### Technical Expertise -

1. 	Determining that what share of applicants posses a hobby of coding. 
2. 	As obviously people having coding as a hobby is more likely to be passionate about it and should turn out as an excellent asset for the organization however not everyone takes their hobbies seriously.
3. Checking if the people code as a hobby if also contribute to the open source project. This showcases their thoughts towards the tech community.	
4. The number boot camps/Hackathons did the applicant appeared in to showcase the eagerness of the applicant in a career on tech industry.
5. Language , Frame work , Dev Platforms , Operating systems  used till date.
6. Professional and overall coding experience.
7. If the applicant is self paced and doesn’t always require to be pushed.

### Ethics –

1. Ethical practice followed by the applicants.
2. Agreement/disagreement of the applicant with the laid down ethics policy of the organization applying for.

### Personal Dossier – 

1. To evaluate that from which background most applicants are from.
2. Their educational backgrounds and determining the trend of which educational background people are applying in Stackoverflow.
3. US military background , if applicable.
4. Gender , sexual preference , Medical status etc of the applicant.

### Expectation – 

1. Remuneration expectation of the applicants and if they are in sync with organization’s interest.
2. The salary type expected (Monthly /weekly) etc
3. Track record of previous organizations and if the expectations are in sync with that.

### Inputs Shared –

A brief detailing of the kind of input shared here in dataset for the evaluation. This inputs are primarily the expectation of the applicants based on which they’ll make a career choice with Stack Overflow

### Job Assessment Based On -  

1. Financial performance/Funding status of the company.
2. The specific department applied on.
3. The tech stack to be working with.
4. Diversity , perks and benefits , Organizational work environment.
5. Self growth scopes/opportunities.

### Other preferences – 

1. How should the employer contact the employee.(methods of communication delivered).
2. Involvement in stack overflow competitions .

### Workflow – 

The flow in which execution of the project will proceed will be described here – 

####	Exploring the Dataset – Reading the dataset on a given variable. Checking it’s rows and columns. The value counts of each.  In our given dataset there are 129 columns and 98855 rows with details.

####	Missing Values – Not all columns and rows will have inputs in them. Finding out these missing values are very important in order to analyze the data properly. The below columns are having the maximum share of missing values. These columns where majority of the values are missing , will not play any significant role in analyzing the dataset , hence they will be removed from the dataset.


1. Time After Bootcamp – 93.27% values are missing.
2. Hackathon Reasons  - 74% Values are missing.
3. Ergonomic Devices – 66% Values are missing.
4. Stack Over Flow Jobs Recommended – 61% Values are missing.
5. AD Blocker Reasons – 65% Values are missing.
6. MilitaryUS – 84% Values are missing.

####	Other Missing Values – Apart from the above stated columns there are other columns as well with missing values but the share of missing values in them are less than the standard benchmark.

####	Handling Missing Values -  There are several methods using which one can handle the missing values present in a dataset. By analyzing the data it’s evident that the ideal approach for this dataset will be the mode method , where the missing values gets replaced with the most frequent occurred value in that particular column.

####	Research Method –
* Finding values counts of all major aspects.
* Finding which feature is impacting other ones.
* Evaluation of Co relations.
* Visualization with necessary libraries for better understanding.
* Use describe method to find the mean value of assessment of individual priorities. 

####	The Findings -  The findings of the research work done extensively done on the dataset reflects the result as below –

* The majority of applications processed through USA (20721) & India( 13721)
* Although Linux being the ideal companion for a developer , The ratio of OS using is much higher with windows(60698) . Apple(MacOs-20325) and Linux(17684) stands far behind.
* Visual Studio remains as the best choice for the applicants worldwide.
* Python as Language , MYSQL for database management remains the number 1 choice for the applicants.
* The working applicants generally is associated with mid sized firms (20-100 employees)
* The majority of the people in the dataset are working full time.
* On average most of the applicants are back end and full stack developers having , 3-8 years of experience.
* The majority of workforce in the tech world comprises the age group of 25-34 or at least our data tells us so.
* Just like the real world , male white supremacy reflects on our dataset as well ,out of 98000 odd applicants , 78000 are white male.
* Just like the ideal scenario , majority of the applicants are from computer science background(nearly 71,000)
* Only handful of applicants(14000 only) are contributing on stack overflow by participating.
* The majority of the ongoing  generation is ready accept the challenges and new horizons which AI is expanding into.
* The traditional study pattern is changing rapidly , while the previous generation was more into studies of normal graduation , this generation is way more focused on technology and computers while choosing their subjects.


#### The Preference Of Applicants while selecting an organization to work for are as given below and is derived from the dataset -

1. The Industry	
2. Technologies Used	
3. Opportunity of growth
4. Funding Status of the company	
5. Compensation and Benefits	
6. Organizational Diversity
7. The Working Department	
8. Work Culture	
9. Product
10. WFH Options	
11. Salary & Benefits
12. Stock Options




















