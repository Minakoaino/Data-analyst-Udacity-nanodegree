## Pisa Data 2012
## By Mina Tzana
This is an analysis for the PISA 2012 dataset for data analyst nanodegree of Udacity. In this analysis we are going to explore and clean the original PISA dataset and in the next notebook, we will present the findings.

The PISA database contains the full set of responses from individual students, school principals and parents. PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school.

Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.

In this dataset we have 485490 students and 18 selected rows. The original dataset had 640 columns. We chose the ones that we were interested in and create a new dataset. Most of the columns have categorical variables.


## Summary of Findings

Number of assessed students per country: As we can see in the chart, Mexico is by far the country with the most assessed students. Italy is the second one with 31073 students.

Gender distribution: there are slightly more women than men with a percentage of 1% difference.

Proporition of female students by country: We can see that in some countries there are more female than male students.
Proporition of male students by country: We can see that Thailand has a very low proportion of male students, Slovenia on the other hand has high proportion of male students.
We can see that Asian countries have more male than female students.

Correlation matrix about Greece: Slide Type
From this correlation matrix we can see that the scores of the students are very correlated to each other. For example math_score has a correlation of 0.968 with ave_score. 
That means that students with high math scores propably have a good average score as well.
We observe also a correlation of 0.960 for reading_score and average score.

Gender Distribution in Greece: 0.6% more females.

Distribution of scores in math, reading, science: all the scores are normaly distributed.

Plot top performance countries for the 3 subjects: the top performance countries are the Asian countries.
This is something I would expect to be honest.
It is interesting to see it plotted as well.
We can see that Estonia has a really good performance in Science (5th place). Estonia is in top 10 on the 3 subjects. Place 9 on math, place 10 on Reading Score.
Shanghai is the best on all subjects.
The top 3 on all subject is Shanghai-Hong Kong-Singapore. All those countries are Asian countries.

Average scores based on the gender: boys tend to score higher on maths and girls on reading and science.

Late for school vs Gender vs Ave score: the distribution is similar for both genres. There is a difference for males who are late three or four times.

Late for school vs Gender vs Ave score for Greece: we saw a big difference for the males who are late 5 or more times in Greece.

## Key Insights for Presentation

I did a new dataframe about Greece. I did some research based on my Country in order to find students behaviour in my country. This analysis can be further investigated.
