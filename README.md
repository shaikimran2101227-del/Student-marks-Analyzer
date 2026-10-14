# Student-marks-Analyzer
# Student Marks Analyzer

## Project Overview

Student Marks Analyzer is a beginner-friendly Python project that uses NumPy and Matplotlib to generate and analyze the marks of 50 students across 5 subjects.

The project calculates subject-wise averages, identifies toppers and failing students, checks pass percentages, and displays student performance through graphs.

## Objectives

- Generate marks for 50 students in 5 subjects.
- Analyze array properties using NumPy.
- Practice array slicing and indexing.
- Filter marks using Boolean masking.
- Divide marks into different grade bands.
- Find subject-wise toppers and pass percentages.
- Visualize results using Matplotlib.

## Technologies Used

- Python
- NumPy
- Matplotlib
- Google Colab

## Features

### 1. Marks Generation
Generates random marks for 50 students across 5 subjects using NumPy.

### 2. Array Analysis
Displays the shape, dimensions, size, data type, total marks, and average marks.

### 3. Slicing and Indexing
Displays the first 10 students, last subject marks, and selected subject columns.

### 4. Boolean Masking
Identifies marks below 40 and marks above 90 using Boolean conditions.

### 5. Grade Classification
Groups marks into four bands:
- A Grade: 80 and above
- B Grade: 60 to below 80
- C Grade: 40 to below 60
- Below 40: Marks less than 40

### 6. Subject-Wise Analysis
Calculates average marks, identifies the highest marks, and finds the topper in each subject.

### 7. Pass Percentage
Calculates the percentage of students scoring at least 40 marks in each subject.

### 8. Student-Wise Results
Calculates each student's total and average marks and displays their pass or fail status.

### 9. Class Performance
Identifies the class topper and lists students who have failed in at least one subject.

### 10. Data Visualization
Creates graphs for:
- Subject-wise average marks
- Grade distribution
- Student-wise average marks

## NumPy Concepts Used

- `np.array()`
- `np.random.randint()`
- `shape`, `ndim`, `size`, `dtype`
- Array slicing and negative indexing
- Boolean masking
- `np.max()`
- `np.argmax()`
- `np.mean()`
- `np.sum()`
- `np.where()`
- `np.any()` and `np.all()`

## How to Run the Project

1. Open Google Colab.
2. Create a new Python notebook.
3. Copy the code blocks into separate cells in the correct order.
4. Run all cells from top to bottom.
5. View the generated reports and graphs.

## Expected Output

- Student marks dataset
- Array information and summary
- Marks below 40 and above 90
- Grade band counts
- Subject-wise toppers and averages
- Subject-wise pass percentages
- Student-wise results
- Class topper and failed students
- Three performance graphs

## Conclusion

This project demonstrates how NumPy can be used to generate, filter, and analyze student marks efficiently. Matplotlib helps visualize the results and makes it easier to understand subject-wise and student-wise performance.

## Author

Created as a Python, NumPy, and Matplotlib learning project.
