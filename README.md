
# IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies

This repository documents the **Capstone Project** completed during the **IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies**.
The internship was a collaborative initiative by **Edunet Foundation, AICTE, and IBM SkillsBuild**.

The primary goal of this internship was to provide **hands-on experience in emerging technologies (AI & Cloud)**, thereby enhancing employability and confidence through solving **real-world challenges** using the IBM SkillsBuild and IBM Cloud platforms.

---

## 📝 Table of Contents

* [Intern Details](#-intern-details)
* [About the Internship](#-about-the-internship)
* [Project: Power System Fault Detection and Classification](#-project-power-system-fault-detection-and-classification)

  * [Problem Statement](#problem-statement)
  * [Solution Overview](#solution-overview)
* [⚙️ Technology Stack](#️-technology-stack)
* [🚀 Project Workflow](#-project-workflow)
* [📊 Results](#-results)
* [📁 Repository Contents](#-repository-contents)

---

## 👨‍💻 Intern Details

* **Name**: Anand Jha
* **Institute**: Trinity Institute of Innovation in Professional Studies
* **Duration**: 4 Weeks (15th July 2025 – 7th August 2025)

---

## 📖 About the Internship

This 4-week program focused on **practical skills in AI and Cloud Computing**, structured with weekly virtual sessions, mentor guidance, and hands-on labs.

### Internship Curriculum:

* **Week 1**: Internship Orientation, IBM Cloud Registration, Artificial Intelligence basics.
* **Week 2**: Data Analytics concepts, Hands-On Labs, and Cloud-based Exploratory Data Analysis (EDA).
* **Week 3 & 4**: Building a Chatbot, AI/ML experiments on IBM Cloud, and deep dive into **AutoAI experiments**.

✅ Successful completion required:

* Active participation
* Completion of at least **two courses on IBM SkillsBuild**
* Submission of the **final project presentation**

---

## 💡 Project: Power System Fault Detection and Classification

### Problem Statement

Design a **machine learning model** to detect and classify different types of faults in a **power distribution system**.
Using **electrical measurement data** (e.g., voltage and current phasors), the model should distinguish between **normal operating conditions** and various **fault conditions** (line-to-ground, line-to-line, three-phase faults).

⚡ *Objective*: Enable **rapid and accurate fault identification**, crucial for maintaining **power grid stability and reliability**.

---

### Solution Overview

An **end-to-end ML solution** was developed for **Power System Fault Detection and Classification**.

* The system used the **Kaggle dataset**: [Power System Faults Dataset](https://www.kaggle.com/datasets/ziya07/power-system-faults-dataset).
* A **trained ML model** was developed using **IBM Watsonx.ai AutoAI**.
* The final model was **deployed as a REST API Web Service** on **IBM Cloud** for real-time fault classification.

---

## ⚙️ Technology Stack

* **Cloud Platform**: IBM Cloud
* **AI/ML Service**: IBM Watsonx.ai Studio
* **Automated ML Tool**: IBM AutoAI
* **Programming Language & Libraries**:

  * Python
  * scikit-learn
  * pandas
  * ibm-watsonx-ai
* **Best Model Selected**: Batched Tree Ensemble Classifier

---

## 🚀 Project Workflow

1. **Data Ingestion**

   * Uploaded dataset from Kaggle into IBM Cloud Project.

2. **Automated Model Building**

   * Configured an **AutoAI experiment** in Watsonx.ai for automated preprocessing, feature engineering, model training, and optimization.

3. **Model Selection**

   * AutoAI ranked multiple classification algorithms.
   * **Batched Tree Ensemble Classifier** achieved the best accuracy.

4. **Deployment**

   * Saved the top-performing pipeline as a **model asset**.
   * Deployed it as an **Online Web Service (REST API)** using IBM Watsonx.ai Deployment Space.

5. **Testing**

   * API endpoint successfully tested with sample data to validate real-time classification performance.

---

## 📊 Results

* The deployed model achieved **high classification accuracy**.
* Demonstrated the effectiveness of **AutoAI for rapid ML model development & deployment**.
* Project successfully met all requirements for the **final evaluation & submission**.


<img width="1137" height="517" alt="image" src="https://github.com/user-attachments/assets/20481788-0599-42b7-9518-8627e6c3ad12" />
<img width="1147" height="531" alt="image" src="https://github.com/user-attachments/assets/c79c0a19-4cda-4811-b16c-a986ae3080ca" />
<img width="1092" height="527" alt="image" src="https://github.com/user-attachments/assets/2ec0a6c4-0890-4354-bb50-1d86b7ae84af" />
<img width="1091" height="530" alt="image" src="https://github.com/user-attachments/assets/785dc8d7-a641-4ef6-9157-43c8394cce8b" />
<img width="1133" height="528" alt="image" src="https://github.com/user-attachments/assets/5f93f259-9356-46e4-8e0c-f3d113f33f00" />


---

**📁 Repository Contents**

`Completion Certificate _ SkillsBuild.pdf/` : certificate

`IBMDesign20250721-29-7dqhae.pdf/` : certificate

`IBMDesign20250721-31-97hofq.pdf/`: certificate

`Problem statement.docx/`: Given problem statement

`ProjectTemplate-aj.pdf/`: The final project presentation pdf submitted for evaluation.

`README.md/`: This file.

---

✨ This project showcases how **AI & Cloud technologies** can be leveraged to solve **real-world problems in power systems**, ensuring **efficiency, reliability, and automation**.

---




