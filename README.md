**IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies**

This repository documents the capstone project completed during the IBM SkillsBuild 4-Weeks Internship on AI & Cloud Technologies. This program is a collaborative initiative by the Edunet Foundation, AICTE, and IBM SkillsBuild.

The internship's primary goal is to provide hands-on experience in emerging technologies, enhancing employability and confidence by solving real-world challenges using the IBM SkillsBuild and IBM Cloud platforms.

**📝 Table of Contents**

Intern Details

About the Internship

Project:Power System Fault Detection and Classification 

Problem Statement

Solution Overview

⚙️ Technology Stack

🚀 Project Workflow

📊 Results

📁 Repository Contents

**👨‍💻 Intern Details**

**Name**: Anand Jha

**Institute**: Trinity Institute of Innovation In Proffesional Studies

**Duration**: 4 Weeks (15th July 2025 to 7th August 2025)

**📖 About the Internship**

This 4-week program focused on providing practical skills in AI and Cloud Computing. The internship was structured with weekly virtual sessions, mentor guidance, and hands-on labs. The curriculum included:

**Week 1**: Internship Orientation, IBM Cloud Registration, Artificial Intelligence.

**Week 2:** Data Analytics concepts, Hands-On Labs, and Cloud EDA.

**Week 3 & 4**: Building a Chat Bot, AI/ML experiments on the cloud, and a deep dive into AutoAI experiments on IBM Cloud.

Successful completion required active participation, completion of at least two courses on IBM SkillsBuild, and the submission of a final project presentation. This internship was offered with no stipend.


**💡 Project: Power System Fault Detection and Classification**

**Problem Statement**

Design a machine learning model to detect and classify different types of faults in a power distribution system. Using electrical measurement data (e.g., voltage and current phasors), the model should be able to distinguish between normal operating conditions and various fault conditions (such as line-to-ground, line-to-line, or three-phase faults). The objective is to enable rapid and accurate fault identification, which is crucial for maintaining power grid stability and reliability. 


**Solution Overview**

An end-to-end machine learning solution was developed to automate Power System Fault Detection and Classification  projects. The system uses a Kaggle dataset – https://www.kaggle.com/datasets/ziya07/power-system-faults-dataset to predict the fault type from the dataset. The final, trained model was deployed as a real-time web service on the IBM Cloud platform.


**⚙️ Technology Stack**

Cloud Platform: IBM Cloud

AI/ML Service: IBM watsonx.ai Studio

Automated ML Tool: IBM AutoAI

Core Language & Libraries:

Python

scikit-learn

pandas

Batched Tree Ensemble Classifier

ibm-watsonx-ai

**🚀 Project Workflow**

**Data Ingestion**:  Kaggle dataset – https://www.kaggle.com/datasets/ziya07/power-system-faults-dataset was uploaded to an IBM Cloud project.

**Automated Model Building**: An AutoAI experiment was configured in watsonx.ai. This powerful tool automated the entire machine learning pipeline, including data preprocessing, feature engineering, model selection, and hyperparameter optimization.

**Model Selection**: AutoAI trained and ranked multiple classification algorithms. The Batched Tree Ensemble Classifier was identified as the best-performing model based on accuracy.

**Deployment**: The top-performing pipeline was saved as a model asset and deployed as an Online Web Service within a Deployment Space on IBM Watsonx.ai, which provides a REST API for real-time predictions.

**Testing**: The deployed API endpoint was successfully tested with sample data to validate its real-time classification capabilities.


**📊 Results**

The deployed model demonstrated high accuracy in classifying infrastructure projects, proving the effectiveness of using automated AI tools for rapid development and deployment. The project successfully met all requirements for the final evaluation and submission.

<img width="1137" height="517" alt="image" src="https://github.com/user-attachments/assets/20481788-0599-42b7-9518-8627e6c3ad12" />
<img width="1147" height="531" alt="image" src="https://github.com/user-attachments/assets/c79c0a19-4cda-4811-b16c-a986ae3080ca" />
<img width="1092" height="527" alt="image" src="https://github.com/user-attachments/assets/2ec0a6c4-0890-4354-bb50-1d86b7ae84af" />
<img width="1091" height="530" alt="image" src="https://github.com/user-attachments/assets/785dc8d7-a641-4ef6-9157-43c8394cce8b" />
<img width="1133" height="528" alt="image" src="https://github.com/user-attachments/assets/5f93f259-9356-46e4-8e0c-f3d113f33f00" />


**📁 Repository Contents**

/Completion Certificate _ SkillsBuild.pdf

/IBMDesign20250721-29-7dqhae.pdf

/IBMDesign20250721-31-97hofq.pdf

/Problem statement.docx

/ProjectTemplate-aj.pdf: The final project presentation pdf submitted for evaluation.

/README.md: This file.




