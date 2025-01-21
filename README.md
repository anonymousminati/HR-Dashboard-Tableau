
# HR Tableau Project Dashboard
A brief description of what this project does and who it's for


## Data and Material used

#### Project Data
  The data used in this HR Dashboard project is generated using a combination of ChatGPT prompts and the Python Faker library. This dataset simulates a set of employee information typically found in HR systems, including demographics, job details, salary, performance evaluations, and attrition data. The generated data is designed to mimic real-world HR data, providing a rich dataset for analysis and visualization in Tableau.
#### Icons & Images 
  The icons used in the HR Dashboard are sourced from Flaticon and customized using Photopea to match the dashboard’s color scheme. The PDS (Photopea files) can be found in the icon folder of the zip file for further editing if needed.
#### Mockups 
  The initial dashboard mockup was created using the Procreate app on a tablet. Additionally, the dashboard container mockups were created using draw.io.
#### Tableau Project File 
  The project file created during the course can be found in Zip file. You can also directly download the Tableau file from my Tableau Public Profile.
## Summary View
  The summary view should be divided into three main sections: Overview, Demographics, and Income Analysis

- ### Overview
    - Display the total number of hired employees, active employees, and terminated employees.
    - Visualize the total number of hired and terminated employees over the years.
    - Present a breakdown of total employees by department and job titles.
    - Compare total employees between headquarters (HQ) and branches (New York is the HQ)
    - Show the distribution of employees by city and state.
- ### Demographic
    The Demographics section should offer insights into the composition of the workforce, including:

    - Present the gender ratio in the company.
    - Visualize the distribution of employees across age groups and education levels.
    - Show the total number of employees within each age group.
    - Show the total number of employees within each education level.
    - Present the correlation between employees’s educational backgrounds and their performance ratings.


- ### Income
    The income analysis section should focus on salary-related metrics, including:

    - Compare salaries across different education levels for both genders to identify any discrepancies or patterns.
    - Present how the age correlate with the salary for employees in each department.
   
## Data Generation

- ### Chat-GPT Prompts

    Generate python script to generate a realistic dataset of 8950 records for human resources. The dataset should include the following attributes:
    
        1. **Employee ID**: A unique identifier.
        2. **First Name**: Randomly generated.
        3. **Last Name**: Randomly generated.
        4. **Gender**: Randomly chosen with:
            - 46% probability for ‘Female’
            - 54% probability for ‘Male’
        5. **State and City**: Randomly assigned from a predefined list of states and their cities.
        6. **Hire Date**: Randomly generated with custom probabilities for each year from 2015 to 2024.
        7. **Department**: Randomly chosen from a list of departments with specified probabilities.
        8. **Job Title**: Randomly selected based on the department, with specific probabilities for each job title within the department.
        9. **Education Level**: Determined based on the job title, chosen from a predefined mapping of job titles to education levels.
        10. **Performance Rating**: Randomly selected from:
            - ‘Excellent’
            - ‘Good’
            - ‘Satisfactory’
            - ‘Needs Improvement’
        with specified probabilities.
        11. **Overtime**: Randomly chosen with:
            - 30% probability for ‘Yes’
            - 70% probability for ‘No’
        12. **Salary**: Generated based on the department and job title, within specific ranges.
        13. **Birth Date**: Generated based on age group distribution and job title requirements, ensuring consistency with the hire date.
        14. **Termination Date**: Assigned to a subset of employees (11.2% of the total) with specific probabilities for each year from 2015 to 2024, ensuring the termination date is at least 6 months after the hire date.
        15. **Adjusted Salary**: Calculated based on gender, education level, and age, applying specific multipliers and increments.

## Demo

[Demo](https://public.tableau.com/app/profile/prathamesh.malode/viz/HRDashboardnew_17373910247240/HRSummary?publish=yes)

![image](https://github.com/user-attachments/assets/26c7951b-6c4f-4a58-8c2f-f9b0726bc534)


## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prathameshmalode/)


