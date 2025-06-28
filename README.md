## 👥 Team Members and Contributions

| *Kanithi Harshitha(LEAD)* 
| *Madana Vishali*
| *Rella Bhavani Sowmya*                          |
---
# 🩺 HealthAI: Intelligent Healthcare Assistant
*Project by:* Kanithi Harshitha, Madana Vishali, Rella Bhavani Sowmya
*Institution:* SVCEW College, Bhimavaram
*Internship:* SmartInternz – Virtual Internship (AI using IBM Granite)
---
## 📌 Project Description
HealthAI is a Streamlit-based intelligent healthcare assistant that helps users with health-related queries. It includes the following AI-powered modules:
* 💬 *AI Health Chat* – Ask health-related questions
* 🦠 *Disease Prediction* – Predict illness based on symptoms
* 💊 *Treatment Plans* – Get AI-suggested treatments
* 📊 *Health Analytics* – Visualize health data and ask insights
> All modules use the IBM Granite 3.3B model (downloaded locally).
---


🎥 *Watch our demo video:*
🔗 [https://www.youtube.com/watch?v=sHO20zfQnuY-]
---
## 📸 Screenshots
> Screenshots are included in the documentation file submitted with this project.
---
## 📁 Folder Structure

HealthAI/
├── app.py
├── patient_chat.py
├── disease_prediction.py
├── treatment_plans.py
├── health_analytics.py
├── requirements.txt
├── healthai_logo.png
├── start_healthai.bat
├── granite/    ← Place downloaded model files here
└── README.md

---
## 🚀 How to Run This Project
1️⃣ *Clone the Repository*
bash
git clone https://github.com/harshithahoney16/Healthai
cd Health-ai

2️⃣ *Create Virtual Environment* (Optional but Recommended)
bash
python -m venv venv
venv\Scripts\activate  # On Windows

Here’s your *updated section* for the README.md, exactly as per your request — with your *Google Drive model link clearly added* in step 4 and *format preserved*:

---

3️⃣ *Install Dependencies*

bash
pip install -r requirements.txt

4️⃣ *Download Model Files (IBM Granite)*
Due to GitHub storage limits, the model files are hosted externally.
📥 *Download the Granite model files from Google Drive:*
🔗 [https://drive.google.com/file/d/1DOIGsywV6mKxiYrYz20Ef1tzYV3B9Lv9/view?usp=drive\_link](https://drive.google.com/file/d/1DOIGsywV6mKxiYrYz20Ef1tzYV3B9Lv9/view?usp=drive_link)

After downloading, *extract the files* and **place them inside the granite/ folder** in this project.
5️⃣ *Run the App*

bash
streamlit run app.py

---
## 🧪 Features in Detail
### 💬 AI Health Chat
Ask general health queries. Powered by IBM Granite model via local inference.
### 🦠 Disease Prediction
Type symptoms and get likely disease predictions.
### 💊 Treatment Plans
Get simple AI-suggested treatment plans for diagnosed conditions.
### 📊 Health Analytics
Displays graphs for:
* Heart Rate
* Blood Pressure
* Blood Sugar
With AI-based insights via prompt.
---
## 🧠 Tech Stack
* Python
* Streamlit
* Hugging Face Transformers
* IBM Granite 3.3B (offline model)
* Matplotlib & Pandas
---
## 🙏 Acknowledgements
* IBM Granite for open-source models
* SmartInternz for internship support
* SVCEW College, Bhimavaram
---
## 🔐 Notes
* Make sure to allow Google Drive access to the model files before submitting.
* You can rename the granite/ folder, but update the path in the code too.
---

---
