# Business case study of Scaler Clustering 

# **About Scaler**
Scaler is an online tech-versity offering intensive computer science & Data Science courses through live classes delivered by tech leaders and subject matter experts. The meticulously structured program enhances the skills of software professionals by offering a modern curriculum with exposure to the latest technologies. It is a product by InterviewBit.

# **Problem Statement**

As a data scientist at Scaler working with the analytics vertical, I have to focus on profiling the best companies and job positions to work for from the Scaler database.

Data provided contains the information for a segment of learners and tasked to cluster them on the basis of their job profile, company, and other features. Ideally, these clusters should have similar characteristics.


# **Column Profiling**

1. ‘Unnamed 0’- Index of the dataset

2. Email_hash- Anonymised Personal Identifiable Information (PII)

3. Company_hash- Current employer of the learner.

4. orgyear- Employment start date

5. CTC- Current CTC

6. Job_position- Job profile in the company

7. CTC_updated_year: Year in which CTC got updated (Yearly increments, Promotions)



**Concept Used**:


1. Manual Clustering

2. Unsupervised Clustering - K- means, Hierarchical Clustering


# **Actionable Insights & Recommendations**
1. Maximum users have years of experience in the range of 3-10 years. Scaler can target the
audience with experience 3 to 10 because mostly they were looking for a career change
or upskilling.
2. In data, email_hash are repeating data and should store one email_hash for the
individual users.
3. Maximum users have job_positions as full stack engineer or backed engineer, so scaler can target
more on these 2 job_position.
4. With company_hash we can see the high-paying
companies for the different job roles so the scaler can target the audience or advertise
with these data insights.
5. In orgyear most of the years are invalid so the system should give an error if the user
enters the wrong orgyear.
6. Scaler should show insights about the updated ctc and use
this as a marketing strategy to bring in more audience
7. Scaler can definetly target the people of Cluster - 2,i.e., the ones who are always in the low CTC range and help them get good CTC's by working on their profile. These people are available in all the year of experience bucket.