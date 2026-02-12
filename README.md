# Student-Exam-Score-Analysis

## Project Overview

This project analyses student exam scores using Python and the NumPy library to demonstrate fundamental data analysis techniques. The dataset consists of five students — Sunny, Peter, Tilly, Safiyyah, and Tara — and their scores in three subjects: Math, Science, and English. The primary aim of the project is to understand overall student performance, identify top and bottom performers, compare subject averages, and practise core NumPy operations. By converting raw score data into NumPy arrays, the project highlights how numerical data can be processed efficiently using Python for analytical purposes.

## Features

The project utilises NumPy arrays to store and manipulate student score data efficiently. It includes functionality to calculate total scores across all subjects, compute average scores per student, and access specific data using array indexing. Core NumPy operations such as np.array(), np.sum(), np.mean(), np.argmax(), and np.argmin() are implemented to demonstrate essential data analysis techniques. The analysis is structured clearly, showing step-by-step computations and outputs, making it suitable for beginners learning Python for data analytics.

## Dataset

The student exam scores are stored in NumPy array.

## Analysis Performed

Several analytical operations were performed on the dataset. First, student score lists were converted into NumPy arrays to enable efficient numerical processing. A 2D NumPy array was created to combine subject scores, allowing totals to be calculated using np.sum() across the appropriate axis. Average scores per student were then computed using np.mean(). Array indexing was demonstrated by retrieving specific student averages, while np.argmax() and np.argmin() were used to identify the highest and lowest scores in Math. These operations showcase fundamental data analysis skills, including aggregation, comparison, and indexing.

## Key Insights

The analysis revealed clear performance differences among the students. Safiyyah achieved the highest total score (278) and was also the highest-performing student in Math with a score of 90, indicating consistently strong academic performance. Peter and Sunny also performed well overall, while Tara recorded the lowest total score (174) and the lowest Math score (56), highlighting potential areas for improvement. The project demonstrates how even a small dataset can provide meaningful insights when analysed systematically using NumPy. It also reinforces the importance of data manipulation and numerical computation skills in entry-level data analytics work.


## How to Use

Open the Student Exam Score Analysis.ipynb notebook in Jupyter Notebook or JupyterLab.
Run all cells sequentially to load the student data, convert lists into NumPy arrays, and view the calculated total and average scores. The outputs will display each student’s overall performance, as well as the highest and lowest scores identified using NumPy functions.
You can modify or expand the dataset by adding new student names or additional subject scores to the lists before converting them into NumPy arrays. This allows further analysis, such as comparing more students, adding new subjects, or exploring additional NumPy operations.

## Technologies Used
Python 3
Jupyter Notebook
NumPy

## Conclusion

This notebook demonstrates how NumPy can be used alongside Python to analyse student exam scores. NumPy provides powerful tools for numerical calculations and is widely used in data analysis and scientific computing.
