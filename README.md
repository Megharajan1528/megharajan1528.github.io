# 🌐 Static Website Deployment – GitHub Pages

## 📌 Objective
Deploy a static website using **GitHub Pages**, a hosting service that allows you to publish HTML, CSS, JavaScript, and other static files directly from a GitHub repository.

---

## 🧰 Tools Required
- **Git** (for version control)
- **GitHub** account
- **Visual Studio Code (VS Code)**

---

## 🎯 Deliverable
A fully deployed static website accessible online at:


---

## 🚀 Deploying a Static Website on GitHub Pages

### 1️⃣ Create a GitHub Repository
- Go to GitHub → New Repository  
- Name the repository **exactly as:**
- Set repository to **Public**
- Click **Create Repository**

---

### 2️⃣ Clone the Repository Locally
Open a terminal and run:

```bash
git clone https://github.com/<yourusername>/<yourusername>.github.io
3️⃣ Add Your Static Website Files

Copy all your files into the cloned folder:

index.html (required)

style.css

script.js

images/ (optional)

Any other assets
git add .
git commit -m "Initial website upload"
git push
Enable GitHub Pages

In your GitHub repository:

Go to Settings

Scroll to Pages

Under Branch, select:

main

/ (root)

