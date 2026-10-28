🏥 Smart Patient Readmission & Care Intervention Platform
📌 Project Overview
This project was developed for Kaiser Permanente to address the growing challenge of avoidable 30-day hospital readmissions among chronic disease patients.

The solution combines:

Data Analytics
Machine Learning
Deep Learning
NLP
Retrieval-Augmented Generation (RAG)
Power BI
to identify high-risk patients, analyze readmission drivers, and support proactive care interventions.

🎯 Business Objectives
The solution answers the following business questions:

Clinical Insights
Which patients are most likely to be readmitted?
What factors increase readmission risk?
Which clinical indicators contribute to poor outcomes?
Operational Insights
Which hospitals or regions have the highest readmission rates?
Which patient groups require intervention?
Financial Insights
What is the cost impact of readmissions?
What savings opportunities exist?
AI Insights
What can be learned from discharge notes?
How can AI assist care managers?
📂 Data Sources
Patient Master
Patient ID
Age
Gender
Region
Coverage Plan
Admissions
Admission Date
Discharge Date
Diagnosis
Length of Stay
Readmission Flag
Clinical Measures
BMI
HbA1c
Blood Pressure
Medication Count
Utilization
ER Visits
Previous Admissions
Treatment Cost
Discharge Notes
Physician Notes
Follow-up Instructions
🔧 Phase 1: Data Preparation
Activities Completed
Data Validation
Missing Value Analysis
Duplicate Detection
Data Integration
Data Cleaning
SQL Analysis
Implemented:

INNER JOIN
LEFT JOIN
GROUP BY
CASE Statements
Window Functions
Ranking Functions
Key Outputs
Readmission Rate by Diagnosis
Readmission Rate by Region
Average Length of Stay
High Utilizer Ranking
Admission Trend Analysis
📊 Phase 2: Statistical Analysis
Performed:

Descriptive Statistics
Mean
Median
Mode
Variance
Standard Deviation
Distribution Analysis
Length of Stay
Treatment Cost
Readmission Frequency
Risk Analysis
Outlier Detection
Correlation Analysis
Confidence Intervals
📈 Phase 3: Exploratory Data Analysis
Univariate Analysis
Age Distribution
Cost Distribution
LOS Distribution
Bivariate Analysis
Age vs Readmission
Cost vs Readmission
HbA1c vs Readmission
Advanced Analysis
Correlation Heatmap
Boxplots
Scatterplots
⚙️ Phase 4: Feature Engineering
Developed custom healthcare features:

Prior Utilization Score
Chronic Condition Count
Risk Index
Cost Per Day
Medication Burden Score
ER Dependency Ratio
Readmission History Flag
🤖 Phase 5: Predictive Modeling
Models Developed
Logistic Regression
Decision Tree
Random Forest
Gradient Boosting
Evaluation Metrics
Accuracy
Precision
Recall
F1 Score
ROC-AUC
Validation
Train-Test Split
Cross Validation
👥 Phase 6: Patient Segmentation
Techniques Used
K-Means Clustering
Hierarchical Clustering
PCA
Segments Identified
Healthy Recovery
Moderate Risk
Chronic High Risk
Frequent Utilizer
🧠 Phase 7: Deep Learning
Developed a Feedforward Neural Network to predict readmission risk.

Comparison Performed Against
Logistic Regression
Random Forest
📝 Phase 8: NLP Analysis
Discharge notes were analyzed using:

NLP Pipeline
Text Cleaning
Tokenization
Stop Word Removal
TF-IDF
Insights Generated
Common Readmission Themes
Keyword Extraction
Topic Identification
🤖 Phase 9: Care Management AI Assistant (RAG)
Objective
Provide healthcare staff with instant access to clinical guidelines, discharge policies, and care protocols.

Technologies Used
LangChain
FAISS
BM25
CrossEncoder
Sentence Transformers
Llama 3.2
Streamlit
RAG Architecture
Healthcare Documents
(PDF / DOCX / TXT)
          ↓
Document Loading
          ↓
Chunking
          ↓
Embeddings
          ↓
FAISS Vector Database
          +
BM25 Retrieval
          ↓
Hybrid Retrieval
          ↓
CrossEncoder Re-ranking
          ↓
Top Relevant Chunks
          ↓
Llama 3.2
          ↓
Answer + Sources
Supported Users
👩‍⚕️ Nurse
Example Questions:

What warning signs should heart failure patients monitor after discharge?
What patient education should be provided?
🏥 Discharge Team
Example Questions:

What follow-up actions are required after discharge?
What should be included in a discharge plan?
👨‍💼 Care Manager
Example Questions:

What interventions are recommended for high-risk patients?
How can hospitals reduce avoidable readmissions?
📏 RAG Evaluation Metrics
The assistant is evaluated using:

Answer Similarity
Precision
Recall
Grounding Score
Retrieval Time
Generation Time
📊 Phase 10: Power BI Dashboard
Dashboard Pages
Page 1 – Patient Overview
KPIs:

Total Patients
Total Readmissions
Readmission Rate
Page 2 – Readmission Trends
Monthly Trends
Readmission Patterns
Page 3 – Risk Prediction
High-Risk Patient Analysis
Page 4 – Patient Segmentation
Cluster Insights
Page 5 – NLP Insights
Discharge Note Analysis
Page 6 – Financial Impact
Readmission Cost Analysis
Potential Savings
🏗️ Power BI Features
Implemented:

✅ Star Schema

✅ DAX Measures

✅ Relationships

✅ Date Table

✅ Time Intelligence

✅ Drill Through

✅ Slicers

✅ Row Level Security (RLS)

💡 Key Results
Identified patients at high risk of 30-day readmission
Revealed major clinical and operational risk factors
Segmented patients for targeted interventions
Reduced effort in policy and guideline search
Improved access to care-management knowledge
Created executive-level healthcare dashboards
🚀 Future Enhancements
EHR Integration
Real-Time Risk Prediction
Azure OpenAI Integration
Voice-Based Healthcare Assistant
Multi-Hospital Knowledge Base
Personalized Intervention Recommendations
