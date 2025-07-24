 🧙‍♂️ **WageWizard – Intelligent Salary Forecasting System**
 👨‍🎓 **Presented By:** Ramulapalli Jahnavi

**College:** Presidency University
**Department:** MCA (Computer Science)
**AICTE ID:** STU6820bb70ad0581746975600



1️⃣ **Problem Statement**

**WageWizard** is a smart machine learning tool that forecasts **monthly and annual salaries** using employee demographics and job-related attributes.

🔍 Core Objectives:

* Predict salaries for individuals and large employee datasets.
* Analyze how variables like education, experience, and occupation affect income.
* Provide actionable career insights and HR planning support.
* Handle **bulk data predictions** through CSV file upload.
* Present salary growth patterns via clear **visualizations**.



2️⃣ **Technology & Development Approach**

 🔧 Tools & Platforms:

* **Language**: Python
* **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Streamlit
* **Development**: Google Colab + Streamlit Cloud
* **Deployment**: Ngrok / Streamlit Sharing
 🧰 Libraries Used:

* `RandomForestRegressor`, `Pipeline`, `StandardScaler`, `LabelEncoder`
* `streamlit` for user interface
* `io` module for file handling


 3️⃣ **WageWizard Workflow**
📋 Data Preprocessing:

* Removed nulls, outliers, and redundant fields
* Replaced unknown values (`?`) with “Others”
* Normalized values and encoded categorical variables
* Added "experience" as a new feature
* Applied filters:

  * Age: 17–75
  * Education-num: 5–16
  * Hours-per-week: 1–99

🤖 Model Training:

* Used `RandomForestRegressor` with parameters:
  `n_estimators=50`, `max_depth=6`
* Data split: 80% training / 20% testing

 🌐 Web App via Streamlit:

* Sidebar with input controls (age, education, gender, etc.)
* Live prediction: displays annual and monthly salary
* Batch CSV upload for multi-employee prediction
* Graph: **Experience vs Predicted Salary**
* CSV download with salary output

 4️⃣ **Sample Output**

📌 Example Prediction:

* **Annual Salary**: ₹409,660.70
* **Monthly Salary**: ₹34,138.39

Batch File Output:

* Uploaded CSV processed and appended with salary results

📊 Graph Output:

* Experience vs Salary trendline shows **growth with experience**

 5️⃣ **Project Summary**

**WageWizard** offers a powerful and intuitive solution for salary prediction.

 ✅ Key Benefits:

* Dual use: for **individual users** and **HR departments**
* Clean UI built with Streamlit
* Handles noisy/incomplete data efficiently
* Accurate results from a robust Random Forest model
* Insight-rich visualizations and batch support

 6️⃣ **Future Scope**

🚀 Enhancements in Pipeline:

* Real-time integration with HRMS via API
* Add **job market benchmarking** for roles
* Allow model tuning through custom training data
* User authentication and PDF report generation


🔮 **WageWizard** empowers smarter salary decisions — for careers, compensation, and company planning.



