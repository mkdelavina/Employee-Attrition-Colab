# Employee Attrition Analysis

Uncovering the factors that lead to employee attrition. <br>
Data source: https://www.kaggle.com/datasets/whenamancodes/hr-employee-attrition

## Hypothesis 1: Overtime Work
**Hypothesis:** Employees who work overtime have higher possibility of attrition<br>
**Conlusion:**
*   Hypothesis is true. For the whole company, the attrition rate of those who did overtime is 30.5% while for those who did not do overtime, it is only 10.4%.
*   This pattern is more evident among the following groups of people (with overtime vs no overtime):
 *   Job Level: Employees with job level 1 at 52.6% vs 15.8%
 *   Gender: Employees who are single at 49.6% vs 16.2%
 *   Job Role: <br>
      *   Laboratory Technitian at 50% vs 15.7% <br>
      *   Sales Representatives at 67% vs 28.8%
  
![image](https://github.com/user-attachments/assets/ef41a0ba-97dc-445d-b070-ae3520e115c7) ![image](https://github.com/user-attachments/assets/cf704293-0aed-4345-bbdb-dd8391dd1b2c) <br> 
![image](https://github.com/user-attachments/assets/34817a9c-a543-448c-abb2-7209eb548fd3)


## Hypothesis 2: Number of Companies Worked
**Hypothesis 2:** Employees with higher number of previous companies have higher attrition rate compared to those who worked for fewer companies. <br>
**Conclusion:** For the whole company, employees with 5-9 previous companies have higher attrition rate at 21.75% while those with 0-4 previous companies have an attrition rate of 14.63%. <br>
*   This is more evident the in following groups of people:<br>
 *   Job role:
     *   Sales Executive  with 16.3% difference in attrition rates.<br>
     *   Research Scientist with 13.23% difference in attrition rates.

![image](https://github.com/user-attachments/assets/da4c1c6a-503b-4a54-9b94-455058700877) ![image](https://github.com/user-attachments/assets/2a44349d-38f2-473e-a069-45c16aafccb2)

 
## Hypothesis 3: DistanceFromHome
**Hypothesis 3:** Employees who live farther have higher attrition rate<br>
**Conclusion:** For the whole company, they hypothesis holds true. It is also generally true when only comparing those who live less than 10km vs those who live more than 10km. But comparing between those who live 11-20km away and those who live 21-30km away, the pattern is inconsistent. The distance is not directly proportional to the attrition rate, but I think there is a certain threshold, maybe 10k, which employees find acceptable.
*   The group of employees that show this more evidently are:
  *   Department: Human Resources
  *   Job Role: Human Resources
  *   Job Level: 3

![image](https://github.com/user-attachments/assets/faade2ed-d183-4ba3-ad51-e9e5a1436aed) ![image](https://github.com/user-attachments/assets/0c9612ee-fa5d-47c1-a88a-d0b3882a9761) <br>
![image](https://github.com/user-attachments/assets/105466d3-a077-4b38-a9cb-48fefbeba174) ![image](https://github.com/user-attachments/assets/b3541c28-96fc-4f9b-b405-96116a39d9c5)


## Hypothesis 4: Monthly Rate
**Hypothesis** Low Monthly Rate increases attrition
Hypothesis <br>
**Conclusion** Though it might be intuitive to assume that low monthly rates would make employees leave and high monthly rates will make employees stay, this is not what the data shows. For the whole company, the highest attrition is among those with monthly rates between 25k to 30k at 20.8% followed by those with 10k-15k at 18.5%. <br>Those with rates between 5k-10k have lower attrition rate than those earning 15k-25k.

![image](https://github.com/user-attachments/assets/fc359701-d775-4d34-9536-88d8115c8cc5)




  
