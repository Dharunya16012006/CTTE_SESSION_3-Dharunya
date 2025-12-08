# 📘 CTTE Session 3 – Python Homework  
### Using CodeSandbox (No Installation Needed)

Welcome to the homework environment for **Session 3** of the CTTE x UWC Career Catalyst program.  
This sandbox lets you complete your homework fully online, without installing Python on your laptop.

You will complete two components:

1. **Python refresher exercises** (Jupyter Notebook)  
2. **Rule-based chatbot** (Python CLI script)

Everything runs in **CodeSandbox**, inside a preconfigured virtual environment (VM).

---

## 🚀 1. Getting Started

### **Step 1 — Open the CodeSandbox link shared by your instructor**
This link loads a fully configured environment with Python and Jupyter Notebook preinstalled:

🔗 **https://codesandbox.io/p/devbox/ctte-session3-homework-df48ql**

### **Step 2 — Sign in to CodeSandbox (required for saving your work)**
Click **“Sign in”** at the top-right.  
You can use:
- Your **Google account**
- Your **GitHub account**
- Or create a simple CodeSandbox account

You must be signed in so that:
- You can **Fork** the project  
- Your work will **auto-save**  
- You can **publish to GitHub** at the end

### **Step 3 — Fork the sandbox**
Click the **Fork** button at the top-right.  
This creates **your own editable workspace** (your personal copy of the environment).

### **Step 4 — Run Setup Tasks to complete**
1. Go to the left hand side pane, and select the 4th icon from top 'CODESANDBOX'.
2. Select on the 'Run Setup Tasks', it should open a pane in the right hand side and install dependencies.


<img width="318" height="762" alt="image" src="https://github.com/user-attachments/assets/a10cc542-c376-4056-8b05-d441d017e030" />


3. This should enable the preview and allow you to open external tab in the bottom right corner pop-up.


<img width="797" height="883" alt="image" src="https://github.com/user-attachments/assets/fae9ba99-d100-4971-ad91-fbcfdc40d9dd" />


CodeSandbox will automatically:
- Install dependencies using `pip install -r requirements.txt`
- Start **Jupyter Notebook** on port **8888**

Watch the logs in the terminal.  
Once you see *“Jupyter Notebook is running on port 8888”*, move to the next step.

---

## 📓 2. Opening the Homework Notebook

### **Step 1 — Open port 8888**
CodeSandbox will show a notification or a port badge: Jupyter Notebook running on port 8888

Click:

> **Open in external**

❗ *Do NOT use the small preview panel — always open the external browser tab.*

### **Step 2 — Open the notebook file**
In the Jupyter Notebook interface:

1. Navigate to the `homework/` folder  
2. Click **`python_refresh.ipynb`**  
3. Work through all the exercise cells and TODOs

Your progress is saved automatically in CodeSandbox.

---

## 🤖 3. Running the Rule-Based Chatbot (Homework Part)

Inside the repository, you will find:

Chatbot/ Sample_chatbot_rule-based_CLI.py -> Runs in the terminal

Chatbot/ Sample_chatbot_rule-based_Streamlit.py -> Opens a separate window and runs using Streamlit UI

To run the CLI chatbot:
1. Open the **terminal** in CodeSandbox  
2. Run: python Chatbot/Sample_chatbot_rule-based.py

To run the Streamlit chatbot:
1. Open the **terminal** in CodeSandbox  
2. Run: streamlit run Chatbot/Sample_chatbot_rule-based.py

This helps you understand how rule-based chatbots work before we build more advanced ones in the session and for your own chatbot development.

---


## 💾 4. Saving and Submitting Your Work

Your sandbox auto-saves, but you must **submit your work via GitHub**.

### **Step 1 — Open the Source Control panel**
Click the **Source Control** icon on the left sidebar (it looks like a branching tree).

### **Step 2 — Click “Publish Branch”**
This will:

- Create a GitHub repository under **your GitHub account**
- Push all your work:  
  - `python_refresh.ipynb`  
  - Your chatbot Python file  
  - Any updates you made  

If prompted, log in to GitHub.

### **Step 3 — Copy your GitHub repo link**
It will look like: https://github.com/<your-username>/ctte-session3-python-homework

Submit this link as instructed to your faculty/ teacher.

---

## 🛠 5. Troubleshooting Guide

### **Jupyter Notebook doesn’t open**
Make sure you clicked **“Open in browser”** for port **8888** (not the small preview window).

### **Notebook appears as raw JSON**
This happens if you open `.ipynb` inside the CodeSandbox editor.  
Instead, always open the notebook from the **Jupyter browser interface**.

### **Chatbot gives `ModuleNotFoundError`**
You may have:
- Opened a wrong file, or
- Not forked the full environment  
Reopen the sandbox using the instructor’s link → click **Fork** again.

### **“Publish Branch” keeps spinning forever**
Try pushing manually:

```bash
git push
```

If it still fails, wait 10–15 seconds and retry — CodeSandbox occasionally delays GitHub syncing.

### **My notebook changes are not visible**

Refresh the Jupyter tab.
Jupyter auto-saves frequently, but sometimes the browser tab lags behind.

### **Port 8888 does not appear**

Wait for the setup tasks to finish.
Once you see a log message like: 'Jupyter Notebook is running on port 8888' the port should become available.



