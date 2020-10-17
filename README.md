# School District Analysis
School District Analysis using `Anaconda`, `Jupyter Notebook`, `Pandas` &amp; `Python`

## Overview of Project
Here is the list of deliverables for the analysis of the school district: 

* A high-level snapshot of the district's key metrics, presented in a table format
* An overview of the key metrics for each school, presented in a table format
* Tables presenting each of the following metrics:
    * Top 5 and bottom 5 performing schools, based on the overall passing rate
    * The average math score received by students in each grade level at each school
    * The average reading score received by students in each grade level at each school
    * School performance based on the budget per student
    * School performance based on the school size 
    * School performance based on the type of school
Before we can begin these tasks, we need to import the datasets into Jupyter Notebook using Python.

## Resources

* Data Source: `PyCitySchools.ipynb` file and rename it `PyCitySchools_Challenge_testing.ipynb`.
* Software: Python 3.9, Visual Studio Code 1.50.0, Anaconda 4.8.5, Jupyter Notebook 6.1.4, Pandas

For more information, read the [`Documentation on Pandas DataFrame`](https://pandas.pydata.org/pandas-docs/stable/reference/frame.html). 

## Background Analysis and Challenges
The school board has notified Maria and her supervisor that the `students_complete.csv` file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.


#### Determine Data Types Challenge Data Background
> You have been tasked with getting key metrics from the datasets. This will involve performing calculations to get sums, averages, and percentages. Before you perform these calculations, though, you should check if the numbers in these datasets are the correct data type for making those calculations, as this is considered a best practice.

> Here are six common data types that we may encounter in this module and that you may come across in the future:

**Pandas Name, Data Types & Arithmetic Operators**

![name-of-you-image](https://github.com/emmanuelmartinezs/School_District_Analysis/blob/main/Resources/Six_common_data_types.PNG?raw=true)


## Deliverable 1: Replace Ninth-Grade Reading and Math Scores
**Instructions**: Using the Pandas `loc` method with conditional statements and comparison and logical operators, select the ninth-grade reading and math scores for Thomas High School. Then, use the Pandas NumPy module to change the reading and math scores to NaN.

### Deliverable 1 Requirements:

You will earn a perfect score for Deliverable 1 by completing all requirements below:

* The `loc` method is used to select all the reading and math scores from the ninth grade at Thomas High School. Inside the `loc` method, the following are completed:

    * A comparison operator is used to retrieve all the rows with Thomas High School in the **"school_name"** column of the `student_data_df`.
    * A comparison operator is used to retrieve all the rows with the ninth grade in the **"grade"** column of the `student_data_df`.
    * Logical and comparison operators are used to retrieve all the rows with the **"reading_score"** column for Thomas High School ninth graders from the `student_data_df`.
    * Logical and comparison operators are used to retrieve all the rows with the **"math_score"** column for Thomas High School ninth graders from the `student_data_df`.
    * The reading and math scores for the ninth graders in **Thomas High school** are replaced with **NaNs**.
 
### Deliverable 1 Results with detail analysis:

**1. A comparison operator is used to retrieve all the rows with Thomas High School in the **"school_name"** column of the `student_data_df`.**

> Image with `Python`, `Jupyter Notebook` and `Pandas` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/School_District_Analysis/blob/main/Resources/Six_common_data_types.PNG?raw=true)


**2. A comparison operator is used to retrieve all the rows with the ninth grade in the **"grade"** column of the `student_data_df`.**

> Image with `Python`, `Jupyter Notebook` and `Pandas` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/School_District_Analysis/blob/main/Resources/Six_common_data_types.PNG?raw=true)

**3. Logical and comparison operators are used to retrieve all the rows with the **"reading_score"** column for Thomas High School ninth graders from the `student_data_df`.**

> Image with `Python`, `Jupyter Notebook` and `Pandas` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/School_District_Analysis/blob/main/Resources/Six_common_data_types.PNG?raw=true)

**4. Logical and comparison operators are used to retrieve all the rows with the **"math_score"** column for Thomas High School ninth graders from the `student_data_df`.**

> Image with `Python`, `Jupyter Notebook` and `Pandas` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/School_District_Analysis/blob/main/Resources/Six_common_data_types.PNG?raw=true)

**5. The reading and math scores for the ninth graders in **Thomas High school** are replaced with **NaNs**.**

> Image with `Python`, `Jupyter Notebook` and `Pandas` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/School_District_Analysis/blob/main/Resources/Six_common_data_types.PNG?raw=true)


## Deliverable 2: Repeat the School District Analysis
**Instructions**: Repeat the school district analysis you did in this module, and recreate the following metrics:

* The district summary 
* The school summary
* The top 5 and bottom 5 performing schools, based on the overall passing rate
* The average math score for each grade level from each school
* The average reading score for each grade level from each school
* The scores by school spending per student, by school size, and by school type

### Deliverable 2 Requirements:

You will earn a perfect score for Deliverable 2 by repeating the school district analysis and updating the following required metrics in the `PyCitySchools_Challenge.ipynb` file:

* The district summary DataFrame.
* The school summary DataFrame.
* The top 5 performing schools, based on the overall passing rate.
* The bottom 5 performing schools, based on the overall passing rate.
* The average math score for each grade level from each school.
* The average reading score for each grade level from each school.
* The scores by school spending per student.
* The scores by school size.
* The scores by school type.
 
### Deliverable 2 Results with detail analysis:

**1. The district summary DataFrame.**

> Image with `Python`, `Jupyter Notebook` and `Pandas` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/School_District_Analysis/blob/main/Resources/Six_common_data_types.PNG?raw=true)



**2. The school summary DataFrame.**

> Image with `Python`, `Jupyter Notebook` and `Pandas` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/School_District_Analysis/blob/main/Resources/Six_common_data_types.PNG?raw=true)



**3. The top 5 performing schools, based on the overall passing rate.**

> Image with `Python`, `Jupyter Notebook` and `Pandas` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/School_District_Analysis/blob/main/Resources/Six_common_data_types.PNG?raw=true)



**4. The bottom 5 performing schools, based on the overall passing rate.**

> Image with `Python`, `Jupyter Notebook` and `Pandas` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/School_District_Analysis/blob/main/Resources/Six_common_data_types.PNG?raw=true)



**5. The average math score for each grade level from each school.**

> Image with `Python`, `Jupyter Notebook` and `Pandas` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/School_District_Analysis/blob/main/Resources/Six_common_data_types.PNG?raw=true)



**6. The average reading score for each grade level from each school.**

> Image with `Python`, `Jupyter Notebook` and `Pandas` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/School_District_Analysis/blob/main/Resources/Six_common_data_types.PNG?raw=true)



**7. The scores by school spending per student.**

> Image with `Python`, `Jupyter Notebook` and `Pandas` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/School_District_Analysis/blob/main/Resources/Six_common_data_types.PNG?raw=true)



**8. The scores by school size.**

> Image with `Python`, `Jupyter Notebook` and `Pandas` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/School_District_Analysis/blob/main/Resources/Six_common_data_types.PNG?raw=true)


**9. The scores by school type.**

> Image with `Python`, `Jupyter Notebook` and `Pandas` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/School_District_Analysis/blob/main/Resources/Six_common_data_types.PNG?raw=true)



## Deliverable 3: A Written Report for the School District Analysis
**Instructions**: For this part of the Challenge, write a report that summarizes your updated analysis and compares it with the results from the module.

The analysis should contain the following:

1. **Overview of the school district analysis:** Explain the purpose of this analysis.

2. **Results:** Using bulleted lists and images of DataFrames as support, address the following questions.

* How is the district summary affected?
* How is the school summary affected?
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
* How does replacing the ninth-grade scores affect the following:
    * Math and reading scores by grade
    * Scores by school spending
    * Scores by school size
    * Scores by school type

3. **Summary:** Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

### Deliverable 3 Requirements:
**Structure, Organization, and Formatting**
The written analysis has the following structure, organization, and formatting:

* There is a title, and there are multiple sections.
* Each section has a heading and subheading.
* Links to images are working, and code is formatted and displayed correctly.
 
**Analysis**
The written analysis has the following:

* Overview of the school district analysis:
    * The purpose of this analysis is well defined.
* Results:
    * There is a bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data.
* Summary:
    * There is a statement summarizing four major changes to the school district analysis after reading and math scores have been replaced.
