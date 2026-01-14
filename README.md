### Problem Statement -
Legacy Systems : Many educational institutions still use manual, excel based tracking that provides statics data but no actionable insights.
Lack of Predictive Power : Faculty can’t identify “at-risk” students early enough to provide intervention or extra training. 
Information Silos : Academic performance(CGPA) is often analyzed separately from technical skills (Coding/Aptitude) hiding the true drivers of placement success. 

### Proposed Solution -

The proposed system addresses the challenge of predicting student placement outcomes to ensure colleges can proactively bridge skill gaps. This involves leveraging Power BI's built-in data analytics and machine learning visuals to forecast placement success based on academic and technical parameters.

## Data Collection:
Gather historical student data including CGPA, age, gender, degree, and branch.
Integrate technical performance factors such as internship history, coding skills, aptitude scores, and soft skill ratings to enhance prediction accuracy.
## Data Preprocessing:
Clean and preprocess collected data in Power Query to handle missing values, outliers, and inconsistencies.
Perform feature engineering to extract relevant insights, such as categorizing CGPA ranges or creating composite skill scores that impact placement probability.
## Machine Learning Algorithm:
Implement native AI algorithms, such as Logistic Regression (via the Key Influencers visual), to identify the top drivers of student placement.
Utilize Decomposition Trees to visualize path-based outcomes and root-cause analysis for "Not Placed" status across different departments.
## Deployment:
Develop a user-friendly, interactive Power BI application featuring Bookmarks and Buttons for seamless navigation between "Executive Overview" and "Student Deep-Dives".
Deploy the solution via Power BI Service, providing cloud-based accessibility for faculty and placement officers with real-time "What-If" simulation capabilities.
## Evaluation:
Assess model effectiveness using accuracy metrics and confusion matrices to verify the reliability of "Predicted Placed" vs. "Actual Placed" outcomes.
Fine-tune the simulation parameters based on actual placement cycles to continuously improve the accuracy of student risk assessments.

