# School_District_Analysis

## Overview of Analysis

The purpose of this analysis is to compare test results from several different high schools within one school district to look for evidence of academic dishonesty. Specifically, we'll be examining how the math, reading, and overall test results for students at Thomas High School differ from similar schools and whether or not there is evidence of academic dishonesty. 


## Results

### District Summary
#### Before Replacing with NaNs

<img width="1025" alt="Screen Shot 2022-07-16 at 1 33 26 AM" src="https://user-images.githubusercontent.com/99847786/179341350-fc1dc9b5-b064-4754-ac7f-cd055b8e0ef9.png">


#### After Replacing with NaNs

<img width="936" alt="Screen Shot 2022-07-10 at 1 35 13 AM" src="https://user-images.githubusercontent.com/99847786/179341360-82833d2d-56d6-4673-b2dc-bbb17795fafe.png">

After replacing the math and reading scores for Thomas High School with NaNs, there was no noticeable change for the average math and reading scores, however, there were some slight differences in the remaining columns. The percentage of students passing math fell from 74.9% to 74.8%, the percentage of students passing reading fell from 85.8% to 85.7%, and the percentage of students passing overall fell from 65.2% to 64.9%.

### School Summary
#### Before Replacing with NaNs

##### Top Five Schools

<img width="1142" alt="Screen Shot 2022-07-16 at 1 12 40 AM" src="https://user-images.githubusercontent.com/99847786/179340396-93dd3d30-4dc4-4af6-9e8f-aae0b7d971a3.png">


##### Bottom Five Schools

<img width="1142" alt="Screen Shot 2022-07-16 at 1 10 56 AM" src="https://user-images.githubusercontent.com/99847786/179340364-9f29bf62-9a4b-4f6f-9cea-c98dc8978719.png">

#### After Replacing with NaNs

##### Top Five Schools


<img width="1007" alt="Screen Shot 2022-07-10 at 2 55 57 AM" src="https://user-images.githubusercontent.com/99847786/178134619-127013bc-9c70-46d4-b5fe-6dbb3865acf9.png">

##### Bottom Five Schools

<img width="1007" alt="Screen Shot 2022-07-10 at 2 56 11 AM" src="https://user-images.githubusercontent.com/99847786/178134621-2222af76-f3e3-4612-b23a-8bfa622b3818.png">

After changing the scores for Thomas High School, a few things stand out. The average math and reading scores fall from 83.42 and 83.85 to 83.35 and 83.90 respectively. The percentage passing math and reading also decrease, from 93.27 and 97.31 to 93.19 and 97.02 % respectively.  Finally the overall percentage of students passing falls from 90.95% to 90.63%


### Thomas High School Vs Other Schools

As seen in the tables above, Thomas High School continues to hold the second highest rank in the school district despite several of the grades being changed to NaNs. 

### Math and Reading Scores by Grade

#### Before

##### Math

<img width="422" alt="Screen Shot 2022-07-16 at 2 31 49 AM" src="https://user-images.githubusercontent.com/99847786/179343503-92986b25-7844-4b08-a160-37e0f1570b7e.png">


##### Reading

<img width="481" alt="Screen Shot 2022-07-16 at 2 31 19 AM" src="https://user-images.githubusercontent.com/99847786/179343506-c89699b3-a423-4135-967e-06a629b7d656.png">


#### After
##### Math

<img width="347" alt="Screen Shot 2022-07-16 at 1 43 38 AM" src="https://user-images.githubusercontent.com/99847786/179341888-7fc5e1cf-bbb5-4e2b-a37d-8aca3d7657ca.png">

##### Reading

<img width="347" alt="Screen Shot 2022-07-16 at 1 43 44 AM" src="https://user-images.githubusercontent.com/99847786/179341891-61ed54f2-0c58-4d85-b6f5-6096355e511a.png">

Here we see that there is no significant difference in math and reading scores by grade. 

### Schools by Spending

#### Before

<img width="1025" alt="Screen Shot 2022-07-16 at 1 15 48 AM" src="https://user-images.githubusercontent.com/99847786/179340961-df4b471e-0681-46ac-907f-8124cd54549c.png">

#### After

<img width="758" alt="Screen Shot 2022-07-10 at 2 34 36 AM" src="https://user-images.githubusercontent.com/99847786/178134111-ae651c70-b15e-430b-ad62-fb2d9defa75b.png">

Although Thomas High School would fall into the  630-644 bin, there is no significant difference in all categories by spending ranges before and after the math and reading scores have been updated. 


### Schools by Size

#### Before

<img width="1025" alt="Screen Shot 2022-07-16 at 1 16 28 AM" src="https://user-images.githubusercontent.com/99847786/179340969-9f302089-512b-451b-a4f9-3b7912aba50c.png">

#### After

<img width="772" alt="Screen Shot 2022-07-10 at 2 34 46 AM" src="https://user-images.githubusercontent.com/99847786/178134113-56a9c29c-87d8-420a-8d30-70599324a75a.png">

No noticeable differences here either. Here, Thomas High School falls into the 'Medium' size school category, the highest performing on average. 

### Schools by Type

#### Before

<img width="1025" alt="Screen Shot 2022-07-16 at 1 16 49 AM" src="https://user-images.githubusercontent.com/99847786/179340974-1bc81d72-a606-40ac-99ad-aacef611ce53.png">


#### After

<img width="772" alt="Screen Shot 2022-07-10 at 2 34 52 AM" src="https://user-images.githubusercontent.com/99847786/178134116-4844e81f-786a-44a8-9f29-90eaad3a5e0c.png">

Finally, we divided our data set into two classes of schools, Charter and District schools. Despite changing the math and reading scores at Thomas High, all categories remain the same. 

## Summary

After replacing the math and reading scores for ninth graders at Thomas High School, we can come to the following conclusions. One, there was a slight decrease in the percentage of students passing math and reading, and passing overall across all schools. This would seem to indicate that the students at Thomas High School are performing better than average, however, not significantly more than other students at other schools. 

By changing the grades for ninth graders at Thomas High School, the percentage of students passing math and reading fell slightly, but not by much. In spite of the decrease, Thomas High School retains second place among schools in the district. 

Finally, by comparing the average amount of students passing across all categories, and comparing by school spending by student, school type, and school size, we can deduce that as Thomas High School falls under the charter school type as well as being a medium size school, both of which tend to produce the highest performing students when compared to other types and sizes, and falls into the secong highest spending bin, we can see that Thomas High School has the traits the highest performing schools in the district. As such, and given that ninth graders' scores aren't significantly different from other grade levels, we can come to the following conclusion: There is insufficient evidence to support the claim that there is academic dishonesty among ninth graders at THS. 
