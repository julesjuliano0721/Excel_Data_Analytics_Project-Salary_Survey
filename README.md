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

    - Our client wanted us to find key insights within these specific fields and their corresponding job titles:    

___
    
    1. Software Development:
          - Software Engineer
          - Web Developer
          - Mobile App Developer
          - Front-end Developer
          - Back-end Developer
          - Full-stack Developer
          - Game Developer
          - DevOps Engineer
     2. Data Science and Analytics:
          - Data Scientist
          - Data Analyst
          - Business Intelligence (BI) Analyst
          - Machine Learning Engineer
          - Data Engineer
          - Database Administrator (DBA)
     3. Information Technology:
          - IT Support Specialist
          - Systems Administrator
          - Network Administrator
          - IT Help Desk Technician
          - Cloud Engineer
          - Information Security Analyst
     4. Cybersecurity:
          - Cybersecurity Analyst
          - Penetration Tester (Ethical Hacker)
          - Security Operations Center (SOC) Analyst
          - Information Security Manager
     5. UX/UI Design:
          - UX Designer (User Experience Designer)
          - UI Designer (User Interface Designer)
          - Interaction Designer
          - User Researcher
     6. Project Management:
          - IT Project Manager
          - Agile Project Manager
          - Scrum Master
     7. Quality Assurance and Testing:
          - Quality Assurance (QA) Engineer
          - Software Tester
          - Test Automation Engineer



     - Added new column called "Job Title" and used filter tool to manually match each type of tech job to the corresponding field that our client provided for us
     - LIMITATIONS: Job titles and roles in the tech industry can vary from one company to another, and new roles may emerge as technology continues to advance. Keep in mind that these categories may overlap, and there are many sub-specializations within each category. Also, to maintain the integrity and quality of the data, only the sub-specializations specifically provided for us above were used, so this left a lot of jobs uncategorized within the dataset.

 - "Annual Salary" Column
    - Changed format to currency
    - Handling Outliers:
      - **Less than $15k**
         - investigated and deleted rows that contained salaries less than because the annual salary for people living on minimum wage is about $15k    
      - **Between $15-$30k**
         - Factors/issues considered when deleting outliers:
            1. median salary of job
            2. additional external source of income (not full-time work hours inputed as instructed by response form)
            3. human error (forgot to add additional zero to income)
            4. level of job title (trainee, assistant would make more sense for a lower-based income compared to a software developer)

          
 -  "Experience in Field of Work" Column
    - Used "Find and Replace" Tool to clean up structure of each option

 - Cleaning and Analyzing "Race/Ethincity (Choose all that apply:):" Column
    - separated each race into different columns
    - used COUNTIF Function to calculate each instance a race was chosen
    - Calculated the sum and percentage of each race and created a table:
  
      
      <img width="438" alt="RaceEthnicityTable" src="https://github.com/julesjuliano0721/Excel_Data_Analytics_Project-Salary_Survey/assets/136859698/83a8c5fe-d4e3-4509-9c63-b14690c90c57">

   






