# Project 1
# PHQ-9 ANALYSIS - Using PHQ-9 to Analyze Seasonal Depression
----------------------------------------
GITHUB DIRECT CODE LINK (PHQ-9 ANALYSIS): 
https://github.com/meera-patel01/Project-1.git
DATA SET DIRECT CODE LINK (PHQ-9 Depression Assessment): 
https://zenodo.org/records/3384860#.Y8OrbdJBwUE
https://www.kaggle.com/datasets/thedevastator/phq-9-depression-assessment

Citation : 
 -Seasonal affective disorder (SAD): 
    https://www.mind.org.uk/information-support/types-of-mental-health-problems/seasonal-affective-disorder-sad/about-sad/
 -Patient Health Questionnaire-9 (PHQ-9): 
    https://med.stanford.edu/fastlab/research/imapp/msrs/_jcr_content/main/accordion/accordion_content3/download_256324296/file.res/PHQ9%20id%20date%2008.03.pdf
 -Association between Vitamin D Supplementation and Mental Health in Healthy Adults: A Systematic Review:
    https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8584834/
 -Vitamin D deficiency during winter months among an adult, predominantly urban, population in Northern Poland: 
    https://pubmed.ncbi.nlm.nih.gov/24802733/
## HYPOTHESIS - Association with Seasonal Changes:
	Individuals have higher PHQ-9 scores, indicating more severe depressive symptoms, during the winter months compared to the summer months.

### BACKGROUND/ANALYSIS
----------------------------------------
The Patient Health Questionnaire (PHQ) is widely used as a diagnostic tools for many common depressive illnesses. With 9 questionaries rating the frequency of each symptoms from 0 (not as all) to 3 (nearly everyday), the final total of the survey assist medical profesional in categorizing the severity of the patient depession into a 5 point scale.
    - 0 to 4 (None to minimal)
    - 5 to 9 (Mild)
    - 10 to 14 (Moderate)
    - 15 to 19 (Moderately severe)
    - 20 to 27 (Severe)

Seasonal Affective Disorder (SAD) is the expreriences of worsening of mental states during the certain particular season, most commonly during the winter momths. Currently with no definitive cause, many researchs theorize there are correlation to the changes in amount of sunlight with the seasons. Previous research have shown a reduced in the general population levels of Vitamin - D, a compound made by our skin by just being exposed to sunlight, during the winter months. Not only are Vitamin - D crucial to many bodily functioning to maintain the physical health, it is also an essential food source to the brain in order to maintain the mental health. 

The selected dataset surveyed 185 individuals of the general population to perform self-screening of mental health by taking the PHQ-9 assesment for a 2 weeks period. The survey had a rolling enrollment date system started from September 30th, 2016 to last enrollement date of August 23rd, 2017. During the 2 week period, the participant are free to self-assest during any time and as many times as they want.

From this dataset, further sorting of the data was done grouping participant by user ID, genders, the seasons and time of day test was taken. Looking at the average score separated by the seasons, the average PHQ9 score narrowing between 14-16 throughout the year, most noticiby the lowest average is in the summer and the highest in the winter. Further analysis shown a left-skewed distribution of total test score in the summer months, indicating more people are scoring lower than the median on the tests. In correspondence when looking at the depression severity indicated by the test score, the biggest section of severe depression is seen in the depression severity distribution of Winter. This finding coincide with the the current hypothesis.

When taken the paticipant gender/sexuality into consideration, male participants data also refect the current hypothesis. The average of the total test score is the highest during the winter compared to the lowest in the summer months for this participant group. Interestingly, female participants data is consistantly high through out the year and also reflect an opposite narrative, with the winter month average test score being the lowest and the highest score in the summer month. This raises future question on other factors caused by the gender differences and how it could correlate into differences in mental health.

Lastly, the time of day the assessment was taken is put into consideration. For this sample population with the assumption of standard working/active hours: waking up in the morning, working and  ending their day in the evening, people are to be more depressed at the end of the day due to the inherent stress exprerience during the active hours. The visual resulted from the analysis by the time of day and by the season are in tune to the current hypothesis. As the day ends, people are shown to be more stressed in the evening than the morning time. The winter time have the highest percentage of severe depression  and the summer have lowest percentage of severe depression regardless of which time of the day it was. 

#### Conclusion

This dataset show to be true with the the current hypothesis. Even though the differences in the statistic numbers might seem small, this can be explained due to the small sample size and short testing period. The consistent trend of higher depressive severity in the winter months compare to the summer months is seen thoughout the data analysis. Gender identity and time period assessment was taken also played an important part in the depression fluctuation. Since there are many complex factors that could also influence mental health, a larger population size will allow for a more significant diffencences in the statistic. 
