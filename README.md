# R - Hiring-outcome-of-TechCorp
Data analysis using R for hiring outcome of TechCorp

### Context Overview

TechCorp faces the increasing competition for top-tier talent in the tech industry. They aim to refine their talent acquisition strategies by analyzing their historical hiring data. They want to uncover the key factors that contribute the successful hires, such as education background, technical skills, digital presence, anand soft skills, as well as potential biases or areas for improvement in their hiring process.

### Data source:

`Candidate Interview and Hiring`: provides candidate’s information such as age, gender, and communication skill level, cultural fit, preferred work environment.

`Candidate Personal Data`: provides candidate personal data such as role, years of experience, education level, graduate from elite college.

`Candidate Technical Scores`: provides candidate technical test score such as python, java, machine learning, etc and GitHub profile.

### Goal of this project:

The goal of this project is to provide a detailed report highlight the main factors decision in the previous hiring outcomes. A series of data visualization that encapsulate key insights, the results of hired candidates. Identify the potential areas of improvement or bias in hiring process.

The report will focus on several characteristic such as education level, year of experience, technical skill score, interview score, communication skill, and digital profile.

### Analysis:

*The analysis will focus on these 6 questions:*

**1. Do candidates graduated from elite college are more likely to be favor in hiring process or it depend on their experience?**
   
Let candidates do not graduate from elite college denote group 1.
Let candidates graduate from elite college denote group 2.

In table 1. Those are hired have the average years of experience of group 1: [5.4 – 6.16]years, and group 2: [6.12 – 7.28] years.

*While group 2 those are not hired due to their below average of years’ experience. This show that graduate from elite is not the main decision factor in hiring process. We can see that the hiring outcome will be dependent on years of experience. From figure 1 in the appendix shows the hiring outcome of candidates applied in the company with their education level. Due to a larger amount of applied, group 1 get more rejection compared to group 2 because they are not qualified (years of experience).*

Result:

Regardless of whether they have an elite college degree or not, those are hired have around [6-6.2] years of experience start from high school to bachelor level, [5.4 – 5.5] years if candidates have master’s or PhD.

![Screenshot 2024-11-03 151749](https://github.com/user-attachments/assets/5cf1fbea-8867-479b-88bd-266c67357693)


**2. How much technical skill score and interview score candidates need to in order to be hired?**

*From table 1. The average of technical score in group 1: [8.94 – 9.12] point and average interview score [8.86 – 9.14] point. The average of technical score in group 2 have a range from [7.8 – 9.00] point and average interview score from [7.72 – 8.46] point.
Technical score: candidates with a wide range in technical test score [2.5 – 9.5] were hired. Indicating technical skill is important but may be less decisive.
Interview score: Candidates with interview score [7.5 – 10] are frequently hired, even if their technical score were below average.However, candidates with interview score below 7 required technical score of at least 6 to be considered for hiring.
Together, candidates must prepare well their interview because it’s the main factors decision.*

**Results**:
Candidates need to earn interview score from 7 or above to highly security their offer.Candidates who can earn at that average or more for both technical & interview score will highly security their offer.

![Screenshot 2024-11-03 151847](https://github.com/user-attachments/assets/a8cc67f9-fbb6-4ee0-a106-3ab2dbcf066c)


**3. What are top 3 of average specific technical skill score needed for an applied role?**

*The analysis highlights that specific technical skills have a higher average score for different roles, which may indicate areas of expertise that are most valuable for each position.For instance, Data Scientists show strength in Java and JavaScript, while System Analysts excel in Python and JavaScript.*

**Results**:
For future hiring, TechCorp must modify job descriptions to emphasize the top 3 or skills for each role, ensuring that candidates with the right expertise apply.TechCorp can focus on screening candidates who display strong performance in the top skills identified for each role.If a candidate is selected for a role where they lack one of the key technical skills, targeted training could bridge the gap.

![Screenshot 2024-11-03 152056](https://github.com/user-attachments/assets/2b1a14cd-6844-49b0-ab92-b3744a9fb784)

   
**4. How do communication skill level correlate and hiring success?**

*From table 2, there are around 670 – 730 candidates each level of communication. The result of candidates who are hired at poor level of communication is 50, below average is 57, average is 35, good is 50 and excellent is 54. Candidates have lowest communication level are still being hire this show that the low level of communication is not affected to the hiring outcome.*

**Results**:
Communication skill is not a factor that influence to the hiring outcome.Some candidates have the lowest communication level but still get hired.

![Screenshot 2024-11-03 152208](https://github.com/user-attachments/assets/4f17e918-8d42-4d4e-9036-7a9eead7112d)
   
**5. Do candidates with digital presence will get a higher hiring success?**

*From table 5, with candidates are hired with both accounts have 25, with LinkedIn profile only have 53 and have GitHub profile only have 72, with no profile have 96.The result show having a GitHub profile might be more beneficial for hiring outcome compared to LinkedIn alone or having both profiles.Company can check candidate project on GitHub, bring more information about that candidate’ skill.*

**Results**:
Tech job are more flavor to candidates who have GitHub profile to check their projects. Having only LinkedIn project or both profiles appears to be less effective in this context.

![Screenshot 2024-11-03 152500](https://github.com/user-attachments/assets/60ce8be2-7ebb-47a8-b189-9f57b8ec3e4f)

  
**6. Does candidate’ age and hiring outcome have a relationship?**

*From figure.6. The range of age candidates were hired from [22-32].The group age of 28 has the highest count of hired candidates (30) and there are 3 notable peaks of age [23 – 24], [27 – 29] and [31-32].The peak correlate with candidates who completed their education level: bachelor, master or PhD.Which aligns with TechCorp’s focus on youthful talent.*

**Results**:
Indicates TechCorp’ strong attraction to younger, educated talent. The hiring trend suggest outreach to universities and higher education or campus recruitment events for maintain these age group.

![Screenshot 2024-11-03 152419](https://github.com/user-attachments/assets/fbe77ec7-b8f0-4b6b-bb08-bfb6045695b4)


### Insights/Recommend:

### Insights
• `Education Level vs. Experience`: Graduates from elite colleges show a slight edge in hiring, but years of experience are more critical.

• `Technical & Interview Scores`: Candidates need interview scores of 7 or above to secure offers. Technical scores are important but less decisive.

• `Top Technical Skills by Role`: Emphasizing key skills in job descriptions will help attract the right candidates.

• `Soft Skills & Hiring Success`: Communication skills show minimal impact on hiring outcomes; low-level candidates still get hired.

• `Digital Presence`: Having a GitHub profile is more beneficial for hiring success than just a LinkedIn profile or having both.

• `Age & Hiring Outcome`: TechCorp has a preference for younger, educated candidates, particularly those in the 22-32 age range.


### Recommendations:

• `Balanced Skill Evaluation`: TechCorp should place equal emphasis on technical and communication level in their hiring processes to ensure well-rounded hires.

• `Tailor Job Offerings`: create more opportunities for younger talent such as internship, partnership with university. Implement policies that promote work-life balance and professional development to retain employees.

• `Continuous Feedback Loop`: Establish a feedback loop that included hiring managers and candidates to continuously refine the hiring process based on outcome and candidate experiences.

• `Encourage Digital Presence`: Use platforms like GitHub and LinkedIn as supplementary evaluation criteria, particularly for candidates with lower interview scores.


**Additional Observations**:

TechCorp’s hiring strategies could benefit from focusing on experience and specific technical skills rather than solely educational pedigree. TechCorp should position itself as attractive by highlight career growth in job posting to recent graduates, emphasizing growth opportunities.

**Future Directions**:

• `Develop New Evaluation Metrics`: TechCorp should consider creating more nuanced evaluation metrics that assess practical skills through real-world
simulations or projects than the traditional technical assessments.

• `Enhance Interview Processes`: Implementing structured interviews that focus on specific competencies can reduce bias and ensure that all candidates are evaluated consistently.










