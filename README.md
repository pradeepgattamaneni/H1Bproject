# H1Bproject

The H-1B is an employment-based, non-immigrant visa category for temporary foreign workers in the United States. For a foreign national to apply for H1-B visa, an US employer must offer a job and petition for H-1B visa with the US immigration department. This is the most common visa status applied for and held by international students once they complete college/ higher education (Masters, PhD) and work in a full-time position.

The goal of the project is get insights into H-1B applications over the year 2011 to 2016 by performing analysis using different technologies like MapReduce,Hive,Pig.

Dataset column description.

CASE_STATUS:Status associated with the last significant event or decision. Valid values include.
"Certified": Employer filed the LCA, which was approved by DOL
"Certified-Withdrawn": LCA was approved but later withdrawn by employer
"Denied": LCA was denied by DOL
"Withdrawn": LCA was withdrawn by employer before
EMPLOYER_NAME: Name of employer submitting labour condition application.
SOC_NAME: the Occupational name associated with the SOC_CODE. SOC_CODE is the occupational code associated with the job being requested for temporary labour condition, as classified by the Standard Occupational Classification (SOC) System.
JOB_TITLE: Title of the job.FULL_TIME_POSITION:
Y = Full Time Position.
N = Part Time Position.
PREVAILING_WAGE: Prevailing Wage for the job being requested for temporary labour condition. The wage is listed at annual scale in USD. The prevailing wage for a job position is defined as the average wage paid to similarly employed workers in the requested occupation in the area of intended employment. The prevailing wage is based on the employer’s minimum requirements for the position.
YEAR: Year in which the H1B visa petition was filed.
WORKSITE: City and State information of the foreign worker’s intended area of employment.
lon: longitude of the Worksite.
lat: latitude of the Worksite.


Questions that were answered after performing analysis.

1a) Is the number of petitions with Data Engineer job title increasing over time?
1b) Find top 5 job titles who are having highest growth in applications.
2a) Which part of the US has the most Data Engineer jobs for each year?
2b) Find top 5 locations in the US who have got certified visa for each year.
3) Which industry has the most number of Data Scientist positions?
4) Which top 5 employers file the most petitions each year?
5) Find the most popular top 10 job positions for H1B visa applications for each year?
6) Find the percentage and the count of each case status on total applications for each year. Create a graph depicting the pattern of all the cases over the period of time.
7) Create a bar graph to depict the number of applications for each year
8) Find the average Prevailing Wage for each Job for each Year (take part time and full time separate).Arrange the output in descending order.
9) Which are  employers along with the number of petitions who have the success rate more than 70% in petitions and total petitions filed more than 1000?
10) Which are the  job positions along with the number of petitions which have the success rate more than 70% in petitions and total petitions filed more than 1000?
11) Export result for question no. 12 to MySql database using sqoop.
