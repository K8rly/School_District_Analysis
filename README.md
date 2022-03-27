# School_District_Analysis

## Overview of the School District Analysis

The purpose of this analysis was to update the School District Summary in order to account for potential academic dishonesty. Due to the possibility that grades had been altered prior to submitting the dataset, Thomas High School data had to be re-analyzed to remove potentially erroneous grade data. The new analysis will compare results from the original analysis and describe how the changes affected the overall analysis.

## Results

  How is the district summary affected? The district summary did not significantly change based on the new analysis. There was a slight difference in scores, but around only a tenth of a percentage point.
  How is the school summary affected? The school summary was significantly different after the new analysis. The passing reading and math scores were more than 25% lower than the original summary after the ninth grade scores were replaced with "NaN" as seen below:
  
  ![Original School Summary](School_summary_original.png]
  
  ![Updated School Summary](School_summary_updated.png]
    
  
  How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? Replacing the ninth graders' math and reading scores moved Thomas High School to a much lower position in relation to the other schools.
  How does replacing the ninth-grade scores affect the following:
   - Math and reading scores by grade were not available for ninth grade, so this summary was incomplete.
   - Scores by school spending did not show a difference in the new summary.
   - Scores by school size increased slightly for the medium sized schools, but not by a significant amount.
   - Scores by school type also had a very slight increase for Charter schools, but again it was not a significant amount.

## Summary

Replacing ninth grade reading and math scores for students at Thomas High School with "NaN" values yielded four changes to the school district analysis:

- Thomas High School's passing reading percentage was significanly lower in relation to other schools
- Thomas High School's passing math percentage was significanly lower in relation to other schools
- Thomas High School's position moved down to one of the lower performing schools
- Thomas High School's data did not include all grades, which skewed the results of the summary


