# 🌐 Task 6: Host a Static Website with GitHub Pages

## 🎯 Objective
The goal of this task is to deploy a simple static HTML website using GitHub Pages — a free and easy way to host personal projects online.

---

## 🛠 Tools Used
- GitHub
- GitHub Pages
- HTML & CSS (optional)

---

## ✅ Steps to Complete the Task

### 📁 Step 1: Create Project Directory Locally
```bash
mkdir github-pages-website
cd github-pages-website
📝 Step 2: Create index.html
Create a basic homepage using HTML:

html
Copy
Edit
<!-- index.html -->
<!DOCTYPE html>
<html>
  <head>
    <title>My GitHub Pages Site</title>
  </head>
  <body>
    <h1>Hello, World!</h1>
    <p>This is my first GitHub Pages website.</p>
  </body>
</html>
You can create this using any text editor (nano, VS Code, etc.).

🔧 Step 3: Initialize Git and Push to GitHub
Initialize Git:

bash
Copy
Edit
git init
git add .
git commit -m "Initial commit"
Create a new repository on GitHub.

Connect the local repo to GitHub and push:

bash
Copy
Edit
git remote add origin https://github.com/<your-username>/github-pages-website.git
git branch -M main
git push -u origin main
🚀 Step 4: Enable GitHub Pages
Go to your GitHub repository.

Navigate to: Settings → Pages.

Under Source, select:

Branch: main

Folder: / (root)

Click Save.

GitHub will generate a link to your live website.

📎 Example Link:
https://<your-username>.github.io/github-pages-website/
