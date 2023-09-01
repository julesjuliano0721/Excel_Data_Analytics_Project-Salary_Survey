# Excel Data Analytics Project: US Tech Job Salaries 💵 💻

![ustechcareerwallpaper](https://github.com/julesjuliano0721/Excel_Data_Analytics_Project-Salary_Survey/assets/136859698/234f88fb-beb0-47e1-8252-1a65ed69e347)

## Scenario
You are a junior data analyst doing freelance work for AskAManager, an online blog that addresses issues regarding management, interviews, and workplace matters. They ask you to analyze a salary survey response form they released online for people who view their website to fill out. For this specific project, your client wants you to provide key insights within careers in the field of technology in the United States.

Link to Survey Response Form: [how much money do you make?](https://www.askamanager.org/2021/04/how-much-money-do-you-make-4.html)


## Business Tasks

 - Collect subset of data that categorizes as a career in technology in the US.
 - Clean data
 - Analyze factors that affect salary such as:
   
   1. Gender
   2. Type of Tech Job 
   3. Age
   4. Level of Education
   5. Experience in Field of Work
   6. Race/Ethnicity


---


### Collecting and Extracting Data 

 - Used filter tool within COLUMN C (What industry do you work in?) to find “Computing Or Tech” Jobs and searched for key words such as “comp” and “tech” using filter to add any jobs that could be generally categorized within the same column considering the "Other:" checkbox allowed for string data type.
 - Used filter tool within COLUMN K (What country do you work in?) to find jobs within the United States. This column was also free form/string data, so every possibility  (U.S., US, USA, United States, U.S.A., The United States, etc.) had to be manually found and considered.
 - Used filter tool within COLUMN H (Please indicate the currency) to find all "USD" to make sure people who work from another country remotely, yet work for a company in the United States are included.
 - Exported subset of data onto new sheet called "US Tech Jobs Working Sheet"


### Data Cleaning Process

 - Removed duplicates
 - Edited column names to make more readable
 - Job Title (REVISED): Used UPPER function
 - Job Type (ADDED COLUMN):
    - Our client wanted us to find key insights within these specific fields:
  
     1. Software Development:
       * Software Engineer
       * Web Developer
       * Mobile App Developer
       * Front-end Developer
       * Back-end Developer
       * Full-stack Developer
       * Game Developer
       * DevOps Engineer
    2.	Data Science and Analytics:
       * Data Scientist
       * Data Analyst
       * Business Intelligence (BI) Analyst
       * Machine Learning Engineer
       * Data Engineer
       * Database Administrator (DBA)
    3.	Information Technology
       * IT Support Specialist
       * Systems Administrator
       * Network Administrator
       * IT Help Desk Technician
       * Cloud Engineer
       * Information Security Analyst
    4.	Cybersecurity:
       * Cybersecurity Analyst
       * Penetration Tester (Ethical Hacker)
       * Security Operations Center (SOC) Analyst
       * Information Security Manager
    5.	UX/UI Design:
       * UX Designer (User Experience Designer)
       * UI Designer (User Interface Designer)
       * Interaction Designer
       * User Researcher
    6.	Project Management:
       * IT Project Manager
       * Agile Project Manager
       * Scrum Master
	   7.	Quality Assurance and Testing:
       * Quality Assurance (QA) Engineer
       * Software Tester
       * Test Automation Engineer








