
# Employment-Based Immigrant Visa


## Certified or Denied?

A permanent labor certification issued by the Department of Labor (DOL) allows an employer to hire a foreign worker to work permanently in the United States. In this study we will explore how likely USCIS will approve or deny visa application. This is a visa decision prediction based on employee's job history, education, job title, employer, class of admission and many other factors. 
A permanent labor certification issued by the Department of Labor (DOL) allows an employer to hire a foreign worker to work permanently in the United States. In this study we will explore how likely Department of Labor will certify or deny visa application. This is a visa decision prediction based on employee's job history, education, job title, employer, class of admission and employers and job backgrounds.

The dataset to be use in this study is us_perm_visas.csv from [Kaggle](https://www.kaggle.com/jboysen/us-perm-visas). This data was collected and distributed by the [US Department of Labor](https://www.dol.gov/agencies/eta/foreign-labor/programs/permanent). 


## Questions this project aims to answer:

1. What percentage of employment-based immigrant visa application were certified or denied by the Department of Labor?
2. What are the type of visa admission most foreign workers applied?
3. From which country most of the foreign worker came from?
4. Which of the employer, job, and foreign worker informations correlate with the USCIS decision to Certify or Deny an application?
5. Is it possible to predict Department of Labor decission on visa application process? 
6. Which Machine Learning achieved the highest Accuracy.


## Results:

### Case Status:

Certified:    330519

Denied:        25649

Year 2014 has the most number of visa application approved.

![case_status](https://user-images.githubusercontent.com/71112826/111577310-41345380-876f-11eb-983b-21ec4cc93e80.png)

![case_year](https://user-images.githubusercontent.com/71112826/111576777-5eb4ed80-876e-11eb-9a43-9cfb6e9b6c56.png)

### Class of Admission:

H-1B Visas - Specialty Occupations, DOD Cooperative Research and Development Project Workers, and Fashion Models has the highest number of application, followed by L1 Visas - for temporary intracompany transferees who work in managerial positions or have specialized knowledge and F1 Visas - students and employment.

![class](https://user-images.githubusercontent.com/71112826/111576778-5f4d8400-876e-11eb-8d8e-461864047ae3.png)

### Foreign Worker Citizenship:

Five countries with the most foreign workers who applied for employment based immigrant visa are:

1. India, 206049

2. China, 26418

3. South Korea, 21218

4. Canada, 13129

5. Mexico, 7917

![fw_citizenship](https://user-images.githubusercontent.com/71112826/111576782-5fe61a80-876e-11eb-94ee-7edcf57b88f4.png)

### Education:

226779 of foreign worker who applied for visa has master's degree.

![education](https://user-images.githubusercontent.com/71112826/111576779-5f4d8400-876e-11eb-90b1-c13140866146.png)

### Job Title

Top Five job title:

Software Engineer, 14372

Computer Systems Analyst - V, 4747

Senior Software Engineer, 3801

Computer Systems Analyst - II, 3416

Software Developer, 2880

![job_title](https://user-images.githubusercontent.com/71112826/111580583-003f3d80-8775-11eb-9c70-3b2d01185965.png)



### Other Features:

![heatmap](https://user-images.githubusercontent.com/71112826/111576784-5fe61a80-876e-11eb-91c2-dabd9d66254d.png)

### Machine Learning: 

Using Random Forrest Classifier model

<img width="710" alt="RFC" src="https://user-images.githubusercontent.com/71112826/111576786-607eb100-876e-11eb-861c-af3796e35392.png">




Google Slide Link:

[Second Segment](https://docs.google.com/presentation/d/1Z1C_EhpD8gS8iwni5HqNlYQYjw_V2ndjph1U1KrMhdA/edit?usp=sharing)

[Third Segment](https://docs.google.com/presentation/d/1U-wAsYPrnfzQV3xdSnGeBvhxa9SUavEQ4HA1Ft3FI-0/edit?usp=sharing)
