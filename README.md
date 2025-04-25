### Healthcare Analytics Dashboard
-This project involves analyzing a dataset of 55,500 unique patient records from 10 major U.S. hospitals, covering hospital admissions, medical conditions, medications, insurance providers, and treatment costs. As a data analyst for a national healthcare oversight organization, the objective is to derive actionable insights to enhance healthcare decision-making, optimize costs, and improve patient outcomes. A Power BI dashboard was developed to visualize trends, highlight key metrics, and support data-driven decisions for stakeholders. Here's the link to the dashboard [Link](https://app.powerbi.com/view?r=eyJrIjoiYjJhNmZkZDQtNTU4Zi00MDQ4LTgwOTgtMzNkMTVlMzllNWIwIiwidCI6IjAzNWEyYzY4LTc2YjQtNGViYS1hMTVhLWNiYmNhOTY4NjhjZCJ9)

### Dataset Overview
-The dataset includes: hospital, admission/discharge dates, gender, age, medical condition, medication, hospital coordinates, doctor, patient ID, blood type, insurance provider, billing amount, and room number.

### Data Preprocessing & Analysis
-Data was cleaned and standardized using Power Query. DAX was leveraged to create advanced measures and calculated columns, enabling robust analytical capabilities.

### Key Business Questions  
-What are the prevalent age groups, genders, and blood types among patients, and are certain demographics admitted more frequently?  
-Which medical conditions are most common, and do they disproportionately affect specific groups?  
-What is the typical hospital stay duration for various conditions, and does it vary by hospital or admission type (emergency, urgent, planned)?  
-What are the average treatment costs per condition, and how do costs differ across hospitals or insurance providers?  
-Which hospitals handle the highest patient volumes, and how do they compare in patient outcomes (e.g., test results)?  
-What are the most prescribed medications per condition, and is their use consistent across hospitals?  
-How do admission types (emergency, urgent, planned) correlate with length of stay and treatment costs?

### Key Insights  
-Demographics: Over 6 years (2019–2024), 56,000 patients were admitted (50% female, 40% male, 10% non-binary). Elderly patients (61–89) had the highest admission rates, particularly females. A+ was the most common blood type (19,000 patients), while B+ was the least (3,000).  
-Medical Conditions: Hypertension and diabetes were the most prevalent (13,800 patients), with asthma being the least common (4,000). Specific blood types showed vulnerabilities (e.g., A+ highly prone to hypertension).  
-Insurance & Costs: Medicare insured 28,000 patients, followed by UnitedHealthcare (17,000). Total billing reached $1.4 billion, with an average hospital stay of 15.5 days. Asthma treatments had the highest average cost ($25,600).  
-Admission Trends: Emergency, urgent, and elective admissions each accounted for ~33% of cases, with emergency admissions linked to longer stays.  
-Hospital Performance: Houston Methodist Hospital led with 20,000 admissions and a strong doctor-patient ratio (0.87), while New York Presbyterian had the lowest volume (2,300) and potential understaffing (ratio: 0.98).  
-Outcomes & Medications: 55% of test results were abnormal, often tied to hypertension. Lipitor was the most prescribed medication (11,140 patients). Patient volumes peaked in 2020 but dropped 30% by 2024.

### Conclusion
-This Power BI dashboard provides a comprehensive view of patient care trends, enabling stakeholders to identify opportunities for operational improvements and enhanced patient outcomes.
