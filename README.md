# Big-Data-Analytics-and-Architecture
AI Job Market Analysis Using Apache Hive
This project analyzes the AI job market dataset using Apache Hive on 

the Cloudera platform to explore hiring trends, skill demands, and 

salary patterns across industries. The dataset contains 2,000 job 

postings with details such as job titles, company information, 

experience levels, skills required, tools preferred, and salary ranges. 

Hive queries are used to perform data exploration, aggregation, and 

trend analysis, including identifying top hiring companies, in-demand 

AI skills, salary distribution by experience, and popular job locations. 

The project demonstrates how big data tools like Hive can efficiently 

process and analyze large-scale structured datasets stored in Hadoop.

Overall, this analysis provides valuable insights into the evolving AI 

employment landscape, helping professionals and organizations 

understand current market demands and emerging technology trends.

Dataset Description

The dataset ai_job_market.csv contains 2,000 records and 12 

attributes, representing real-world job postings from various industries 

such as Technology, Finance, and Healthcare.

Key attributes include:

 job_id: Unique identifier for each job posting

 company_name: Name of the hiring organization

 industry: Sector of the job (e.g., Tech, Finance)

 job_title: Designation (e.g., Data Scientist, AI Engineer)

 skills_required: Technical skills like Python, TensorFlow, SQL, 

PyTorch

 exprerience: Level of experience required (Entry, Mid, Senior)

 employment_type: Type of employment (Full-time, Contract, 

etc.)

 location strings: City and state of the job location

 salary_range_usd: Salary range offered for the position

 company_size: Organization size (Small, Medium, Large)

 tools_preferred: Preferred tools and frameworks used by the company

Technologies Used
 Apache Hive
 Hadoop (Cloudera Environment)
 HiveQL (SQL-like Queries)
 CSV File Data Ingestion
 HDFS Storage
Steps Performed
1. Created a database and Hive table schema for the job dataset.
2. Loaded CSV data from local storage or HDFS into the Hive 
table.
3. Executed multiple Hive queries to summarize and visualize 
insights:
o SELECT COUNT(*) → total number of job listings.
o GROUP BY → industry and company analysis.
o AVG() and MAX() → salary range insights by experience
level.
o ORDER BY and LIMIT → top hiring companies and skill
trends.
4. Generated analytical reports summarizing job market trends and 
data-driven insights.
Key Insights
 Identified top industries contributing the most AI job postings.
 Found top companies hiring for AI roles globally.
 Discovered average salary variations across different experience 
levels.
 Highlighted most in-demand tools and skills for AI 
professionals.
 Observed growth in AI job postings over recent years.

Results and Findings
 Tech and Finance industries dominated AI job openings.
 Mid-level and senior professionals were in highest demand.
 Python, TensorFlow, and SQL emerged as the most common 
skills.
 Large companies posted the majority of job listings.
 Salary analysis showed higher pay for AI Engineers and Data 
Scientists in tech-driven firms.
Conclusion
The AI Job Market Analysis Using Apache Hive project 
demonstrates the practical use of Hive for handling and 
analyzing structured datasets in a Big Data environment. The 
findings provide clear visibility into hiring patterns, skill 
requirements, and salary expectations within the AI industry. By 
integrating Hive’s querying capabilities with Hadoop’s storage 
efficiency, this project showcases how data-driven insights can 
be extracted effectively to support workforce planning, 
education strategies, and career decisions in the AI field.
