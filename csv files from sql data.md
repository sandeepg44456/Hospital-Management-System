# Hospital Management Analysis

### ✤ Project Description:

- The primary objective of hospital management analysis is to optimize the efficiency and effectiveness of healthcare delivery within a hospital or healthcare system.

- This involves assessing various aspects such as resource allocation, patient flow, quality of care, and financial performance to enhance patient outcomes while managing costs and resources effectively.


### ✤ Tool Used:

- MySQL
- Python

### ✤ Tables Used:
- patients
- doctors
- admissions
- province_names

### ✤ Task:
- I extracted data and structured it into four separate tables within MySQL.
- I exported each table into individual Excel files.
- By using pandas library in Python, I combined these Excel files into a consolidated dataset stored in a single Excel file.
- To ensure data integrity, I performed comprehensive data cleaning operations, focusing on consistency and accuracy.
- This project provided valuable experience in Python programming, SQL database management, and advanced data manipulation and cleaning techniques.
  
### ✤ Quetions of the Project:

Q1: Show first name, last name, and gender of patients whose gender is 'M'.

Q2: Show first name and last name of patients that weight within the range of 100 to 120 (inclusive).

Q3:Show first name of patients that start with the letter 'C'. 

Q4: Show first name and last name concatinated into one column to show their full name.

Q5: Show first name, last name, and the full province name of each patient. (Example: 'Ontario' instead of 'ON')

Q6: Show how many patients have a birth_date with 2010 as the birth year.

Q7: Show the first_name, last_name, and height of the patient with the greatest height.

Q8: Show all columns for patients who have one of the following patient_ids: 1,45,534,879,1000.

Q9: Show the total number of admissions.

Q10: Show all the columns from admissions where the patient was admitted and discharged on the same day.

Q11: Show the patient id and the total number of admissions for patient_id 579.

Q12: Based on the cities that our patients live in, show unique cities that are in province_id 'NS'?

Q13: Write a query to find the first_name, last name and birth date of patients who has height greater than 160 and weight greater than 70.

Q14: Write a query to find list of patients first_name, last_name, and allergies where allergies are not null and are from the city of 'Hamilton'.
