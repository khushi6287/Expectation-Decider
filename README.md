# Expectation Decider - Probability Analysis Project

## 📊 Project Overview
This project analyzes student performance data to predict mathematics exam success using probability theory. As a junior data analyst at an educational research institute, I developed an "Expectation Decider" model that examines relationships between study habits, attendance, group participation, and exam outcomes.

## 🎯 Objectives
- Analyze probability patterns from student dataset
- Calculate empirical and theoretical probabilities
- Examine relationships between variables using probability concepts
- Determine factors that most influence exam success
- Apply Bayes Theorem for predictive analysis

## 📁 Dataset Structure
The dataset contains 200 student records with the following fields:

| Field | Description |
|-------|-------------|
| `study_hours` | Hours studied per week |
| `attendance` | Percentage attendance in lectures |
| `group_discussion` | Participation in group discussions (Yes/No) |
| `previous_test_score` | Marks out of 100 from last internal test |
| `final_exam_pass` | Exam outcome (Pass/Fail) |

## 🔍 Key Analyses Performed

### 1. **Probability Fundamentals**
- Defined probability and key terminology
- Identified three event examples:
  - Event A: Student passes exam
  - Event B: Student attendance > 80%
  - Event C: Participates in group discussion

### 2. **Types of Probability**
- **Empirical Probability**: Calculated actual pass rate from data
- **Theoretical Probability**: Assumed equal likelihood (50%) for comparison

### 3. **Random Variable & Probability Distribution**
- Defined random variable: "Number of students passing" out of 3 randomly selected
- Constructed probability distribution table
- Calculated mean and variance

### 4. **Venn Diagram Analysis**
Visualized overlap between:
- Students studying >10 hours/week
- Students with attendance >80%
- Students satisfying both conditions

### 5. **Contingency Table & Probability Calculations**
Created cross-tabulation of group discussion vs. exam outcome:
- **Joint Probability**: P(Group Discussion AND Pass)
- **Marginal Probability**: P(Pass)
- **Conditional Probability**: P(Pass | Group Discussion)

### 6. **Relationship Analysis**
- Interpreted conditional probability intuitively
- Determined independence/dependence of events
- Analyzed correlation between group participation and exam success

### 7. **Bayes Theorem Application**
Calculated probability of passing given high attendance:
- P(Pass | High Attendance) = ?

## 💻 Implementation
The analysis is implemented in Python using:
- `pandas` for data manipulation
- `numpy` for statistical calculations
- `matplotlib` for visualizations
- `matplotlib-venn` for Venn diagrams

## 📈 Key Findings
- **Empirical Pass Rate**: [Insert calculated value]%
- **Relationship between Group Discussion and Passing**: [Dependent/Independent]
- **Most Influential Factors**: Study hours and attendance showed strongest correlation with passing

## 📋 How to Run
1. Install required packages:
```bash
pip install pandas numpy matplotlib matplotlib-venn
```

2. Ensure dataset file `expectation_decider_dataset.csv` is in the same directory

3. Run the analysis:
```bash
python expectation_decider.py
```

## 📚 Learning Outcomes
- Practical application of probability theory
- Data analysis with Python
- Statistical inference from real-world data
- Bayes Theorem implementation
- Probability distribution construction
