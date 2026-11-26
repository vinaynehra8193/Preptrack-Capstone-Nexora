# Preptrack Capstone – Student Analytics
### Team Nexora

## Project Overview
Preptrack is a student analytics capstone project developed using Python.
The project uses a synthetic student dataset to explore academic performance,
attendance, assignments, study habits, activity, and student engagement.

## Objectives
- Generate and analyze student data.
- Perform data quality checks.
- Clean and preprocess datasets.
- Engineer useful analytics features.
- Track analytical experiments.
- Store and query data using SQLite.
- Perform descriptive and rule-based academic risk analysis.
- Create visual analytics dashboards.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQLite
- Google Colab

## Dataset
The project uses a synthetic dataset containing 500 student records.

Features include:
- Student ID
- Department
- Semester
- Attendance percentage
- Total classes
- Classes attended
- Assignment totals
- Assignments completed
- Weekly study hours
- Average marks
- Activity score

The data is synthetic and does not represent actual students.

## Project Workflow
1. Workspace setup
2. Library imports
3. Synthetic dataset generation
4. Data inspection
5. Data quality testing
6. Data cleaning
7. Cleaned dataset export
8. Exploratory data analysis
9. Feature engineering
10. Reusable preprocessing pipeline
11. Experiment tracking
12. SQLite integration
13. Advanced analytics
14. Dashboard development
15. Final output packaging

## Data Cleaning
The cleaning process includes:
- Duplicate removal
- Missing value handling
- Invalid marks correction
- Study-hours validation
- Attendance consistency correction
- Assignment value validation

## Feature Engineering
Engineered features include:
- Attendance category
- Assignment category
- Study category
- Assignment completion percentage
- Engagement score
- Engagement level
- Academic risk category

## Engagement Score
The engagement score uses a weighted combination of:
- Attendance: 40%
- Assignment completion: 35%
- Activity score: 25%

## Academic Risk
Academic risk is classified using rule-based conditions based on attendance,
average marks, and engagement score.

The risk labels are:
- Low Risk
- Medium Risk
- High Risk

These classifications are analytical rules and are not machine-learning predictions.

## Experiment Tracking
Experiments are recorded with:
- Experiment ID
- Experiment name
- Timestamp
- Dataset
- Preprocessing method
- Metrics
- Notes

## Database
SQLite is used to store processed student data and perform queries including:
- Low attendance analysis
- High-risk student analysis
- Department-level analysis
- Semester-level analysis

## Advanced Analytics
The project includes:
- Performance segmentation
- Academic risk vs performance analysis
- Attendance group analysis
- Assignment analysis
- Study-hours analysis
- Engagement ranking
- Correlation analysis

## Dashboard
The dashboard includes:
- KPI summary
- Department-wise average marks
- Semester-wise average marks
- Performance category distribution
- Attendance distribution
- Academic risk distribution
- Department engagement analysis

## Limitations
- The dataset is synthetic.
- Risk categories are rule-based.
- Correlations do not establish causation.
- Results should not be used for real student decisions.

## Future Scope
- Use real anonymized datasets where permitted.
- Explore validated predictive models.
- Add interactive dashboards.
- Improve analytics and reporting.
- Evaluate models using appropriate metrics.

## Conclusion
Preptrack demonstrates a complete student analytics workflow covering synthetic
data generation, quality checks, cleaning, feature engineering, experiment
tracking, database integration, descriptive analytics, and visualization.

---
### Team Nexora