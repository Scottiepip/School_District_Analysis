# School_District_Analysis
Analyse school district data to uncover schools' performance based on different aspects.
## Overview of Project
Maria, the Chief Data Scientist of City School District, is responsible for analyzing information from variety of sources and variety of formats. She is tasked to preparing all standardized test data for analysis,reporting and presentation to privde insights about performance trends and patterns. These insights are used to inform discussions and strategic decisions at the school district level. Maria asked us to help her analyze data on student funding and students' standardized score to aggregate the data and showcase trends in school performance.

However, after we done the analyze, The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. Maria has asked us to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. And Maria want us to repeat the school district analysis that we did and write up a report to describe how these changes affected the overall analysis.
## Result
   - How district summary is affected?
      
      Original district summary
      ![image](https://user-images.githubusercontent.com/108709071/181670606-a6420b49-75f5-48df-91f0-bbb2a987d9e1.png)
      
      New district summary
      ![image](https://user-images.githubusercontent.com/108709071/181670746-b301af6a-c68d-45d5-b8ed-b20cbb05d268.png)

      Baes on the two pictures shown above, we can see that after we removed the math score and reading score for 9th graders from Thomas High School, there's a small decline, less than 1% on all the results.
      
   - How is school summary affected?
   
      Original school summary
      ![image](https://user-images.githubusercontent.com/108709071/181675369-b1526b4a-43ac-479a-b92e-616a9996ab51.png)

      New school summary
      ![image](https://user-images.githubusercontent.com/108709071/181674182-3158ebad-0284-4a0e-ad04-041bd32e0b49.png)
      
      Base on the result shown on the above pictures, we can see that there's no change in other schools. For Thomas High School, the average math score decreses, average reading score increases and % passing for math, reading and overall decreases. But changes are less than 1%, it's pretty minimum.

   - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
   
      Original top school
      ![image](https://user-images.githubusercontent.com/108709071/181676224-d0026837-8fe3-4ec4-965b-42f1f19dcaf1.png)

      New top school
      ![image](https://user-images.githubusercontent.com/108709071/181676312-fedb2679-48ba-4871-bfb3-21741e256881.png)

      From the comparison, we can see that replacing the 9th graders math and reading scores doesn't affect Thomas High School's performance. It's still in the top five performing schools.
      
   - How does replacing the ninth-grade scores affect the following:
      - Math and reading scores by grade
      
         Original score by grade
         Math
         
         ![image](https://user-images.githubusercontent.com/108709071/181679281-c32b96fa-4f16-4d77-9ef7-e48e6364e04f.png)

         Reading
         
         ![image](https://user-images.githubusercontent.com/108709071/181679356-95ab103d-b6dc-4565-92b8-ab266c7c2dd8.png)

         
         New score by grade
         Math
         
         Reading
      - Scores by school spending
                
         Original score by spending
         ![image](https://user-images.githubusercontent.com/108709071/181678372-d4218d3a-932e-48cb-9212-46b1a86752c7.png)

         New score by spennding
         ![image](https://user-images.githubusercontent.com/108709071/181678526-29d30200-66b1-4150-bd14-bcb178a4e233.png)

      - Scores by school size
         
         Original score by size
         
         ![image](https://user-images.githubusercontent.com/108709071/181678727-16deb23f-b389-4a22-87d0-2c9f04ba5f68.png)

         New score by size
         
         ![image](https://user-images.githubusercontent.com/108709071/181678692-f11eeb70-faae-436f-9a2a-a60ec48014f2.png)

      - Scores by school type
      
         Original score by type
         
         ![image](https://user-images.githubusercontent.com/108709071/181679010-cdf2e59a-457b-4cd6-afc0-06355883813b.png)

         
         New score by type
         
         ![image](https://user-images.githubusercontent.com/108709071/181679047-6a4b4e8d-26fb-4aad-80e0-94d86409b55d.png)
