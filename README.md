# GitHub Codespaces Demo Project 🚀

This project demonstrates how to create, edit, and run a simple web project using **GitHub Codespaces**.
Codespaces provides a **cloud-based development environment that runs VS Code in your browser**, allowing you to write and run code without installing anything locally.

---

# 📌 What You Will Learn

By following this guide you will learn how to:

* Create a GitHub repository
* Launch a Codespace
* Create project files
* Run a website using a local server
* Commit and push changes to GitHub
* Stop a Codespace to save usage hours

---

# 🧰 Technologies Used

* HTML
* CSS
* JavaScript
* Node.js (for running a simple development server)

---

# Step 1 — Create a GitHub Repository

1. Go to https://github.com
2. Log into your GitHub account.
3. Click the **"+" icon** in the top-right corner.
4. Select **New repository**.

Fill in the following details:

Repository name:

codespace-demo

Description:

Demo project for learning GitHub Codespaces

Repository settings:

✔ Public
✔ Add a README file

Click **Create repository**.

---

# Step 2 — Launch GitHub Codespaces

1. Open the repository you just created.
2. Click the **Code** button.
3. Select the **Codespaces** tab.
4. Click **Create codespace on main**.

GitHub will now start a **cloud development environment**.

After a few seconds, a browser-based version of **VS Code** will open.

---

# Step 3 — Understand the Workspace Structure

Inside the Codespace you will see your project folder:

/workspaces/codespace-demo

Your repository files will appear inside this directory.

Initially the folder will contain:

README.md

This works the same way as a local project folder on your computer.

---

# Step 4 — Create Project Files

In the file explorer (left side panel), create the following files:

index.html
style.css
script.js

Your project structure should now look like this:

codespace-demo
│
├── index.html
├── style.css
├── script.js
└── README.md

---

# Step 5 — Add HTML Code

Open **index.html** and add the following code:

```html
<!DOCTYPE html>
<html>

<head>
    <title>Codespaces Demo</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<h1>Hello from GitHub Codespaces 🚀</h1>

<button onclick="sayHello()">Click Me</button>

<script src="script.js"></script>

</body>

</html>
```

---

# Step 6 — Add CSS Styling

Open **style.css** and add:

```css
body{
    font-family: Arial;
    text-align: center;
    margin-top: 100px;
    background: #f4f4f4;
}

h1{
    color: #333;
}

button{
    padding: 10px 20px;
    font-size: 18px;
    cursor: pointer;
}
```

---

# Step 7 — Add JavaScript

Open **script.js** and add:

```javascript
function sayHello(){
    alert("Codespaces is working!");
}
```

---

# Step 8 — Install a Local Development Server

Open the **terminal** inside Codespaces.

Run the following command to install a simple development server:

npm install -g live-server

This installs a tool that allows us to run our website locally.

---

# Step 9 — Start the Server

Run the following command:

live-server

Codespaces will detect that a server is running and open a **forwarded port**.

A notification will appear asking if you want to open the application in the browser.

Click **Open in Browser**.

Your demo website should now appear.

---

# Step 10 — Save Your Work to GitHub

To store your files permanently in the repository:

1. Click the **Source Control icon** in the left sidebar.
2. Stage all files.
3. Add a commit message:

Add demo website project

4. Click **Commit**.
5. Click **Push**.

Your code is now saved to GitHub.

---

# Step 11 — Stop the Codespace

Codespaces uses compute resources, so you should stop it when finished.

Steps:

1. Go to your GitHub profile.
2. Navigate to **Codespaces**.
3. Locate your running Codespace.
4. Click **Stop Codespace**.

You can restart it anytime later.

---

# 🎉 Congratulations

You have successfully:

✔ Created a GitHub repository
✔ Launched a Codespace
✔ Built a small web project
✔ Ran a development server
✔ Committed and pushed your code

---

# 📚 Next Steps

To continue learning, try:

* Running a Node.js backend project
* Creating a React application
* Adding a Dev Container configuration
* Using GitHub Actions for CI/CD

---

# 📌 Author

Demo created for learning **GitHub Codespaces workflow**.
