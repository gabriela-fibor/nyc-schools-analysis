# NYC Public Schools SAT Score Analysis

This project explores SAT test results from NYC public schools. It includes basic data analysis using `pandas` to identify top-performing schools and analyze borough-level statistics.

## Dataset
The data was provided by [DataCamp](https://www.datacamp.com/) as part of an exercise:  
**"Exploring NYC Public School Test Result Scores"**

##  Goals

1. **Best Math Scores**  
   Identify schools where the average math SAT score is at least 80% of the maximum possible score (800).  
   Output: `best_math_schools` DataFrame with `school_name` and `average_math`, sorted descending.

2. **Top 10 Combined SAT Scores**  
   Calculate a total SAT score by summing math, reading, and writing scores.  
   Output: `top_10_schools` DataFrame showing the 10 schools with the highest `total_SAT`.

3. **Borough with Highest SAT Score Variability**  
   Group schools by borough and calculate:
   - number of schools,
   - average total SAT score,
   - standard deviation.  
   Output: `largest_std_dev` — one-row DataFrame with borough having the highest SAT standard deviation.
