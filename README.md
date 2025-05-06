# ✅ To-Do List App

A privacy-first, cross-platform to-do list app powered by on-device LLMs. Here's a short [video](https://www.youtube.com/watch?v=mBk0T3oeKu8) (<1 min) on why its useful 

👉 **[Skip to How to Use the App »](#-how-to-use-the-app)**

---
# 📝 To-Do List App Installation Guide (macOS)

## 1. Download the App
- [Download the app here](https://github.com/kushalpatil07/TodoList/releases/download/v0.1/todolist.zip) 

## 2. Allow the App to Run (Unsigned App)
Since the app is not signed yet, macOS will block it by default. Follow these steps to allow it to run:

1. Try to open the downloaded app — macOS will block it.
2. On your Mac, go to **Apple menu > System Settings > Privacy & Security** (scroll down if needed).
3. In the **Security** section, click **Open Anyway** next to the warning about the app.
4. Confirm again by clicking **Open**.
   > ⚠️ This "Open Anyway" option is available for about an hour after you try to open the app.

## 3. Grant Accessibility Permissions
- When prompted, allow Accessibility permissions.  
  This enables features like pushing tasks into the app from slack.

## 4. App Settings
Once the app is running:

### ✅ Install Ollama (for on-device LLM support)
- Inside the app, go to **Settings**.
- Follow the link to install **Ollama**.

### 📦 Download the Model
- Recommended model: `llama3.2:latest`  
  You can download it via the text box provided. Or via the Ollama interface.

## 5. Install Chrome Extension
To push tasks directly from webpages or Gmail:

1. [Download the extension zip](https://github.com/kushalpatil07/TodoList/releases/download/v0.1/chrome_extension.zip)
2. Unzip the file.
3. Open **Chrome** and go to `chrome://extensions`.
4. Enable **Developer mode** (top-right toggle).
5. Click **Load unpacked** and select the unzipped extension folder.

---

## 🚀 How to Use the App

### 📨 Pushing Tasks
- Push tasks from **Slack** or **Gmail** using the in-app button.
- While browsing, use the **Chrome extension** to quickly add tasks.

### 🏷️ Labelling Tasks
- You can create custom **labels** to organize tasks (optional).
- Once a label is create, the app will **auto-label** incoming tasks.
- If the LLM mislabels, add some **User Context** in **Settings** to improve accuracy.

### 🗓️ Planning Your Day (for 15+ tasks)
1. Set a **date** for each task—Today, Tomorrow, or later. This is the day you want to start working. Not the due date
2. Go to the **Current Tasks** page and work only from there.
3. Reschedule tasks easily if something urgent comes up.

> 📌 No need to assign priorities like P1/P2—just assign a day you want to start working.

> 💡 Planning suggestions are coming soon to make this even easier!

---

## 🛠️ Support & Feedback
Have questions, issues, or ideas? We'd love to hear from you. [Contact us](#) or open an issue.

---

Happy tasking!
