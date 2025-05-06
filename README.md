# TodoList

# 📝 To-Do List App Installation Guide (macOS)

## 1. Download the App
- [Download the app here](#https://github.com/kushalpatil07/TodoList/releases/download/v0.1/todolist.zip) 

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

1. [Download the extension zip](#https://github.com/kushalpatil07/TodoList/releases/download/v0.1/chrome_extension.zip)
2. Unzip the file.
3. Open **Chrome** and go to `chrome://extensions`.
4. Enable **Developer mode** (top-right toggle).
5. Click **Load unpacked** and select the unzipped extension folder.

---

Enjoy managing your tasks seamlessly
