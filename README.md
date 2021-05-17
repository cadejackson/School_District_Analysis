# <u>School District Analysis</u>

## <u>Project Overview</u>
The school board has suspicion that the grades from Thomas High School have been altered, specifically the reading and math scores for 9th graders.  The objective of this project is to remove the 9th grade scores from the dataset and recalculate the results to observe how the results change.

## <u>Results</u>

The project started by reading the school and student data, performing some data cleaning, and then merging the datasets together for further analysis.  Then we replaced math, reading, and overall passing percentages with "nan" for Thomas High School in order to re-calculate the statistics for 10th - 12th grades.  After re-caluclating the results we observed that the new results were very similar to hte original results.  The district summary had a slight change and the top 5 and bottom 5 schools remained unchanged.  This implies that the 9th grade scores were not altered.

Code Used:

- Pandas
    groupby with aggregate
    mean
    count
    .loc
    DataFrame filtering
    DataFrame merging
    cut
- Numpy
    np.nan

School District Summary DataFrame:

![School District Summary](https://github.com/cadejackson/School_District_Analysis/blob/main/Resources/District%20Summary.png)

Bottom 5 Performing Schools:

![Bottom 5 Performing Schools](https://github.com/cadejackson/School_District_Analysis/blob/main/Resources/Bottom%205%20Schools.png)

Top 5 Performing Schools:

![Top 5 Performing Schools](https://github.com/cadejackson/School_District_Analysis/blob/main/Resources/Top%205%20Schools.png)

Average Math Scores for Each Grade Level:



![Average Math Scores by Grade](https://github.com/cadejackson/School_District_Analysis/blob/main/Resources/Average%20Math%20Scores%20by%20Grade.png)

Average Reading Scores for Each Grade level

![Average Reading Scores by Grade](https://github.com/cadejackson/School_District_Analysis/blob/main/Resources/Average%20Reading%20Scores%20by%20Grade.png)

Average Scores by School Spending per Student

![Average Scores by School Spedning per Student](https://github.com/cadejackson/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Spending.png)

Average Scores by School Size

![Average Scores by School Size](https://github.com/cadejackson/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Size.png)

Average Scores by School type

![Average Scores by School Type](https://github.com/cadejackson/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Type.png)

## <u>Summary</u>

Overall, we saw slight changes to the district summary with the average math score dropping slightly but the percentage of passing students for math and reading icnreasing by 1%.  The slight change is due to the large district size of almost 40,000 students and we only removed 461 students from the dataset which only account for 1.18% of the total student population in the school district.  The scores for Thomas High School had slight changes which indicate that the 9th grade results were not altered.

![District Summary Comparison](https://github.com/cadejackson/School_District_Analysis/blob/main/Resources/District%20Summary%20Comparison.png)
