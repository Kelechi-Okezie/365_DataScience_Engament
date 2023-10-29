# 365_DataScience_Engament
## STUDENT CONVERSION RATE ON 365 DATA SCIENCE PLATFORM
#### Data set can be found here:
https://learn.365datascience.com/projects/calculating-free-to-paid-conversion-rate-with-sql/?tab=description
The database includes three tables storing information about students’ registration dates, engagement dates, and subscription purchase dates

The chief aim of this project is to estimate the fraction of students who purchase a subscription after starting/watching a lecture, i.e., the free-to-paid conversion rate among students who’ve engaged with video content on the 365 platform. 
To achieve this, the key metrics to calculate are:
##Conversion Rate: What is the free-to-paid conversion rate of students who have watched a lecture on the 365 platform?
##Average Duration Between Registration and First-Time Engagement: What is the average duration between the registration date and when a student has watched a lecture for the first time (date of first-time engagement)?
##Average Duration Between First-Time Engagement and First-Time Purchase: What is the average duration between the date of first-time engagement and when a student purchases a subscription for the first time (date of first-time purchase)?

![image](https://github.com/Kelechi-Okezie/365_DataScience_Engament/assets/141277019/ce0c5a1a-4f49-46ca-af88-56961b407eb1)
The Venn diagram above illustrates how the three tables from the database relate and how they should extracted to solve the tasks for this project.

### Final Query Results Table
![image](https://github.com/Kelechi-Okezie/365_DataScience_Engament/assets/141277019/60d65d53-1cfb-453a-b07d-0ea364839348)
### How can we interpret these results, and what are their implications?
## Conversion Rate
Let’s first discuss the result we obtained for the free-to-paid conversion rate metric. The fraction of students who purchase monthly, quarterly, or annual subscriptions from those who watch a lecture is about 11%—i.e., for every 100 students who come to the 365 platform, roughly 11 of them purchase a subscription. At first glance, this number seems relatively low, but let’s dig a bit deeper.
A significant number of students register on the platform out of curiosity. Nevertheless, we can outline why most students aren’t prompted to benefit from the program entirely. One factor contributing to this could be that we’re targeting a broader audience rather than focusing specifically on data science enthusiasts eager to begin their journey in the field.
Second, since 365 platform targets a beginner audience, students may need clarification about what to start with. Should they first invest weeks in mastering an object-oriented programming language such as Python, a query language such as SQL, or maybe a data visualization software like Tableau? What prerequisites are necessary for each of these tools? In August 2023, the team at 365 put effort into making its audience’s journey much easier by introducing an onboarding sequence that creates a customized learning path for each of its students. This way, users will know exactly where to start and how to continue.
Still, some users might need more time to embark on a data science journey. They might be college students whose exam periods have just started or working people who can’t dedicate the desired time.
Finally, we must consider that some users might not fancy the platform and would instead take the first steps toward data science elsewhere. Still, whatever the reason, reaching out to customers is essential, pinpointing any flaws and striving towards a better product.
## Average Duration Between Registration and First-Time Engagement
The results from the second metric indicate that, on average, it takes students between three and four days to start watching a lecture after registering on the platform. Ideally, it would be great if a new student started watching a lecture on their first day. Every other element the platform offers (exams, projects, career tracks) requires more attention, while the lessons are easy to check out.
## Average Duration Between First-Time Engagement and First-Time Purchase
Let’s study analogously the average duration between the first-time engagement and purchase. The results we retrieved from our SQL analysis show that, on average, it takes students roughly 26 days to purchase a subscription after getting acquainted with the product. 



