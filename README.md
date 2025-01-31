# Data-manipulation-with-pandas
# Student Scores Data Processing and Analysis

## Overview
This project focuses on **data manipulation and analysis using Pandas** to manage student scores for three graduate courses: **CS 5000, CS 5110, and CS 5600**. It involves generating random scores, performing data transformations, sorting, filtering, calculating averages, assigning grades, and computing GPA.

## Dependencies
Ensure you have the following Python libraries installed:
```python
import numpy as np
import pandas as pd
```

## Tasks and Implementation

### **1. Generate David's Scores (Series)**
- Used `np.random.seed(123456)` to generate 3 random integers between **30 and 100**.
- Created a **Pandas Series** named "David" with courses as indices.

### **2. Generate Scores for 10 Students (DataFrame)**
- Used `np.random.seed(123)` to generate a **10x3** DataFrame with random scores.
- Assigned student names as row indices and course names as column headers.

### **3. Add David’s Scores to the DataFrame**
- Appended David’s **Series** as a new row in the `scores` DataFrame.

### **4. Find Top 3 Scores in CS 5000**
- Used `nlargest(3)` to extract students with the highest scores.

### **5. Filter Students Based on Conditions**
- Selected students with `CS 5000 > 80` and `CS 5110 < 60`.

### **6. Sort Data by Course Scores**
- Sorted `CS 5000` in **ascending order** and `CS 5110` in **descending order**.

### **7. Extract Specific Student Scores**
- Retrieved **Ravi** and **Mounika**'s scores for `CS 5000` and `CS 5600`.

### **8. Update Incorrect Score**
- Corrected **John’s CS 5600 score** to **94**.

### **9. Calculate Average Scores**
- Inserted a new column `Average` containing the mean scores of all three courses.

### **10. Assign Letter Grades for CS 5000**
- Applied grading criteria to create a **CS 5000 Grade** column:
  - **A**: `>= 90`
  - **B**: `80 – 89`
  - **C**: `70 – 79`
  - **D**: `60 – 69`
  - **F**: `< 60`

### **11. Count Students in Each Grade**
- Used `value_counts()` to display the **number of students per grade**.

### **12. Compute GPA for Each Student**
- Used a **4.0 scale** based on letter grades to compute the **GPA**.
- Formula:
  ```
  (3 * grade_points_CS5000 + 3 * grade_points_CS5110 + 3 * grade_points_CS5600) / 9
  ```

### **13. Assign Academic Status Based on GPA**
- Created a `Status` column with the following conditions:
  - **Honor Roll**: `GPA >= 3.5`
  - **Normal**: `3.0 <= GPA < 3.5`
  - **In Probation**: `GPA < 3.0`

### **14. Remove CS5000 Grade Column**
- Dropped the `CS 5000 Grade` column from the DataFrame.

## Summary
This project demonstrates key **data manipulation** techniques using Pandas, including:
✅ **Data Generation** (random scores using NumPy)
✅ **Data Transformation** (adding/modifying rows & columns)
✅ **Sorting & Filtering**
✅ **Statistical Calculations** (averages, GPA computation)
✅ **Categorization** (letter grades, academic standing)

This structured workflow can be extended to other academic performance analysis projects. 🚀

