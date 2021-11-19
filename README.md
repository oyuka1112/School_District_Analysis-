# School District Analysis on Python
## Overview of the school district analysis
The purpose of the School District Analysis project is to get useful information from the given dataset using [python pandas package](https://pandas.pydata.org/docs/getting_started/overview.html) on jupyter notebook. The dataset includes reading and math scores of each students from 15 different high schools (9th to 12th grade). The snapshot of the district metics presented in a table format below. 
![](https://user-images.githubusercontent.com/64121596/142295953-cb4cf7e9-2af6-4018-b083-03bcfcc0d84e.png)


## Results
### The District Summary
The District Summary did not change that much regarding the average math and reading score. But, the passing percentage increased drastically when we exclude the 9th graders scores. That means in 9th graders, a lot of kids are failing (less than 70%). 
 - Including the 9th grade:
  ![](https://user-images.githubusercontent.com/64121596/142376232-334d052b-bf92-4ad8-bef2-85a81ed4a3ae.png)
  
 - Excluding the 9th grade:
  ![](https://user-images.githubusercontent.com/64121596/142376089-4e6a3564-dae5-4d6d-8b5e-3b0ad248fbf5.png)

### The School Summary by given mertrics
1. Top and low performing 5 schools based on overall (both math and reading) passing rate (70% or more). 
  - After changing the 9th graders scores to NaNs, the Thomas High School (with its overall passing rate) jumped to the top 2 school.

3. The average math score received by students in each grade level at each school (top 10)
  ![](https://user-images.githubusercontent.com/64121596/142378092-2c7c0704-cbc5-4209-ba77-74b268015811.png)
4. The average reading score received by students in each grade level at each school (top10)
  ![](https://user-images.githubusercontent.com/64121596/142378218-7b4c112f-7874-441c-a87c-1a8ca34b93e7.png)
5. School performance based on the budget per student
  - The spending and its overall passing rate has negative relationship. The spending per student increases, the overall passing rate decreases. 
  ![](https://user-images.githubusercontent.com/64121596/142378362-e6eeab08-c197-4abe-8eac-e476510e6565.png)
6. School performance based on the school size
  - School sizes as small, medium, and large, the small and medium sized school performed better overall. If the school size is large (2000 to 5000) the scores and passing rates decreased compared to small or medium school sizes.
  ![](https://user-images.githubusercontent.com/64121596/142378474-03b509aa-7fdf-45b8-931a-2a21e7825135.png)
7. School performance based on the school type
  - Charter schools performed better than the district schools.
  ![](https://user-images.githubusercontent.com/64121596/142378565-24383bbc-5b77-4d7f-895d-69034078b9fd.png)


## Summary
I replaced the 9th graders of Thomas High School math and reading score to zero and compared.
- The difference in the overall passing percentage is very high when we exclude the 9th graders scores.
    
