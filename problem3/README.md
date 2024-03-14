![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/c2a091b1-efa5-4936-af0e-8738452e19e2)

FIG.1 Creating mysql container , setting password to root and selecting the local sql database

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/9d83d885-0063-4850-8829-0545a978a0e6)

FIG.2 Executing the container we just created

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/fe708b79-01eb-406c-a334-a1bede76b3c6)

FIG.3 Creating company database in container

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/44482bdf-f801-4452-bc51-28cfc600b2f0)

FIG.4 Selecting the database

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/d1493284-da2e-46b1-8465-d33d792d43ae)

FIG.5 Selecting company.sql. It was an error in table employees at line 41, column departments it was 'Consulting' instead of '7' and in that way there was an error because it needs to be integer

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/913867ff-a83f-49c8-a1f2-369e50654255)

FIG.6 Creating a new user

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/386bb89a-e250-4a18-97c6-b19d1c47b2e1)

FIG.7 Granting all privileges

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/a491a0c8-404a-4e3e-83a2-523a80899c27)

FIG.8 If the error in the employee table is not fix for a simple select of the entire table the result will be null 

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/073f03b9-6429-4de4-88c9-a3d894b1321f)

FIG.9 After the changes and reselecting company.sql we can see that we already have more affected rows

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/3f16e195-dd09-4808-8fcb-51bf3fc8b0a1)

FIG.10 Checking that everything it's alright now

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/e73bfdcb-af36-4d9f-81b2-d17032b1e942)

FIG.11 We select the departments name and calculate the average salary for each department by selecting and grouping employees from the same department
