# 📊 Student Scores Analysis with Pandas

## 📝 **Project Overview**

This project focuses on analyzing and managing student performance data using **Pandas** and **NumPy**. The objective is to simulate student scores for various graduate courses, perform statistical analyses, and derive meaningful insights through data manipulation techniques. The project covers data creation, modification, filtering, aggregation, and performance evaluation.

---

## 📂 **Table of Contents**

1. [Project Overview](#-project-overview)
2. [Dataset Description](#-dataset-description)
3. [Project Workflow](#-project-workflow)
4. [Key Analyses & Operations](#-key-analyses--operations)
5. [Results & Insights](#-results--insights)
6. [Technologies Used](#-technologies-used)
7. [How to Run the Project](#-how-to-run-the-project)
8. [Conclusions & Future Work](#-conclusions--future-work)
9. [Contribution Guidelines](#-contribution-guidelines)
10. [Author](#-author)

---

## 📊 **Dataset Description**

The dataset simulates student scores for three graduate courses:

- **Courses:** CS 5000, CS 5110, CS 5600
- **Students:** Alice, Mark, Bill, Tony, Jason, Ravi, Sandeep, Mounika, John, Curtis, and David
- **Score Range:** Random integers between 30 and 100

Each student has scores recorded for the three courses, and additional columns are calculated for average scores, GPA, and academic status.

---

## 🔍 **Project Workflow**

1. **Data Creation:**

   - Simulating random scores using `NumPy` with predefined seeds for reproducibility.
   - Organizing the data into `Pandas Series` and `DataFrames`.

2. **Data Manipulation:**

   - Adding new student records.
   - Filtering data based on score conditions.
   - Sorting data by multiple criteria.

3. **Statistical Analysis:**

   - Calculating average scores.
   - Assigning letter grades based on score thresholds.
   - Computing GPA using a weighted credit system.

4. **Performance Evaluation:**

   - Classifying students into academic standing categories (Honor Roll, Normal, In Probation).
   - Updating and correcting specific student records.

5. **Data Cleaning:**

   - Dropping unnecessary columns for final presentation.

---

## 📈 **Key Analyses & Operations**

### 1. **Score Simulation:**

- Used `NumPy` to generate random integers representing student scores.
- Created individual records (e.g., David) and integrated them into the main dataset.

### 2. **Top Performers Identification:**

- Retrieved the top 3 students in **CS 5000** using `nlargest()`.

### 3. **Conditional Filtering:**

- Identified students with CS 5000 scores > 80 and CS 5110 scores < 60.

### 4. **Sorting:**

- Sorted CS 5000 scores in ascending order and CS 5110 in descending order simultaneously.

### 5. **Data Correction:**

- Corrected John's CS 5600 score to reflect the accurate value.

### 6. **Statistical Metrics:**

- Calculated the average score across courses for each student.
- Assigned letter grades for CS 5000 based on defined score brackets.

### 7. **GPA Calculation:**

- Applied GPA scaling (4.0 system) using course credit weights.
- Incorporated letter grades (A-F) into GPA computations.

### 8. **Academic Status Classification:**

- Categorized students into "Honor Roll," "Normal," and "In Probation" based on GPA.

---

## 💡 **Results & Insights**

- **Top Performers:** Identified high-achieving students in CS 5000.
- **Academic Distribution:** Breakdown of students across letter grades and GPA standings.
- **Improved Accuracy:** Corrected errors in student scores to maintain data integrity.
- **GPA Trends:** Highlighted how grades across courses impact overall academic standing.

---

## 🛠️ **Technologies Used**

- **Languages:** Python
- **Libraries:** Pandas, NumPy
- **Tools:** Jupyter Notebook, Google Colab

---

## 🚀 **How to Run the Project**

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-repo-link.git
   cd student-scores-analysis
   ```

2. **Install Dependencies:**

   ```bash
   pip install pandas numpy
   ```

3. **Run the Notebook:**

   ```bash
   jupyter notebook student_scores_analysis.ipynb
   ```

4. **Dataset:** No external dataset required as the data is generated within the code.

---

## 🤝 **Contribution Guidelines**

We welcome contributions to enhance this project. To contribute:

1. **Fork the Repository:**

   - Click the "Fork" button at the top right of this page.

2. **Clone Your Fork:**

   ```bash
   git clone https://github.com/your-username/student-scores-analysis.git
   cd student-scores-analysis
   ```

3. **Create a New Branch:**

   ```bash
   git checkout -b feature-branch
   ```

4. **Make Your Changes:**

   - Add new features, optimize code, or improve documentation.

5. **Commit Your Changes:**

   ```bash
   git add .
   git commit -m "Add your commit message here"
   ```

6. **Push to GitHub:**

   ```bash
   git push origin feature-branch
   ```

7. **Create a Pull Request:**

   - Open GitHub, go to your fork, and click "Compare & Pull Request."

We’ll review your PR and provide feedback as soon as possible. Thanks for contributing! 🚀

---

## 💡 **Conclusions & Future Work**

- **Conclusions:**

  - Demonstrated the power of Pandas for data manipulation and analysis.
  - Showcased techniques for data correction, filtering, and performance evaluation.
  - Highlighted how to compute GPA and academic standing using real-world grading scales.

- **Future Work:**

  - Implement data visualization for score distributions.
  - Integrate more complex statistical analysis (e.g., regression analysis).
  - Automate report generation for student performance.

---

## 👨‍💻 **Author**

**Nikitha Kadaparthi**

[GitHub Profile](https://github.com/Nikithakadaparthi)

---

**If you find this project useful, please ⭐ the repository and consider contributing!** 🚀

