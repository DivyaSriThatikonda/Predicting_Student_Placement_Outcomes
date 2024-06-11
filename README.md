# Predicting_Student_Placement_Outcomes
# Project Description
The objective of this project is to analyze and predict the employability of students based on various academic, demographic, and experiential factors. The dataset comprises details about students' secondary and higher secondary education, undergraduate degrees, work experience, and MBA performance. By examining these attributes, the project aims to determine which factors significantly influence the likelihood of securing a job and to predict potential salary ranges for students based on their profiles.

# Dataset Description
The dataset consists of the following columns:
    
**sl_no:** Serial number, a unique identifier for each student.
    
**gender:** Gender of the student (e.g., 'M' for male, 'F' for female).
    
**ssc_p:** Secondary Education percentage (10th Grade) - the overall marks obtained in secondary school.
    
**ssc_b:** Board of Education for secondary school (e.g., 'Central' for central board, 'Others' for other boards).
    
**hsc_p:** Higher Secondary Education percentage (12th Grade) - the overall marks obtained in higher secondary school.
    
**hsc_b:** Board of Education for higher secondary school (e.g., 'Central' for central board, 'Others' for other boards).
    
**hsc_s:** Specialization in Higher Secondary Education (e.g., 'Science', 'Commerce', 'Arts').
    
**degree_p:** Degree percentage - the overall marks obtained in the undergraduate degree.
    
**degree_t:** Type of undergraduate degree (e.g., 'Sci&Tech' for Science and Technology, 'Comm&Mgmt' for Commerce and Management, 'Others').
    
**workex:** Work experience (e.g., 'Yes' if the student has work experience, 'No' otherwise).
    
**etest_p:** E-test percentage - a score from an employability test.
    
**specialisation:** MBA specialization (e.g., 'Mkt&Fin' for Marketing and Finance, 'Mkt&HR' for Marketing and Human Resources).
    
**mba_p:** MBA percentage - the overall marks obtained in the MBA program.
    
**status:** Employment status (e.g., 'Placed' if the student has been placed in a job, 'Not Placed' otherwise).
    
**salary:** Salary offered to the student (applicable only if the student is placed).

## Installation

To run the project in your Jupyter Notebook or Google Colab, follow these steps:

1. **Clone the repository**:
   - If using Jupyter Notebook:
     ```bash
     !git clone https://github.com/DivyaSriThatikonda/Predicting_Student_Placement_Outcomes.git
     ```
   - If using Google Colab:
     - Open a new Colab notebook.
     - Execute the following code cell:
       ```python
       !git clone https://github.com/DivyaSriThatikonda/Predicting_Student_Placement_Outcomes.git
       ```
2. **Install dependencies**:
   - Run the following code cell in the notebook to install the required libraries:
     ```python
     !pip install numpy pandas matplotlib seaborn scikit-learn
     ```

3. **Access the dataset**:
   - The `insurance.csv` dataset is already included in the repository. 

4.**Tools used**:
- **Numpy**: Used for numerical computations and array manipulation.
- **Pandas**: Used for data manipulation, analysis, and cleaning.
- **Seaborn**: Used for data visualization and statistical plotting.
- **Scikit-learn**: Used for building and evaluating the linear regression model.
- **Descriptive Statistics**: Used to summarize and analyze the dataset, including measures such as mean, median, standard deviation, and correlation coefficients.
- **Matplotlib**:Used for data visualization

 # Results
 
**Overall Accuracy**: 72%

**Class 0 (Not Placed):**

**Precision:** 57% - Correctly identified not placed instances out of total predicted not placed.
    
**Recall:** 57% - Correctly identified not placed instances out of actual not placed instances.
    
**F1-Score:** 57% - Balance between precision and recall.
    
**Class 1 (Placed):**

**Precision:** 80% - Correctly identified placed instances out of total predicted placed.
    
**Recall:** 80% - Correctly identified placed instances out of actual placed instances.
    
**F1-Score:** 80% - Balance between precision and recall.
    
**The model performs better at predicting placed students than not placed students, with an overall accuracy of 72%.**
  
