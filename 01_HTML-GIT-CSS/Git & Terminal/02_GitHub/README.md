# Github

| 💻 Prerequisite | Basic knowledge with Command Line |
| --- | --- |
| 💼 **Learning Outcomes** | • Know how to create your first repo <br>• Know the basic git commands<br>• Know how to upload your project<br>|
| 🔗 **Reference** | [About GitHub and Git](https://docs.github.com/en/get-started/start-your-journey/about-github-and-git) |


## What is Github? 👁️👄👁️

* 🤔 It is a **cloud-based platform** that allows developers to store, manage, and track changes to their code.

* 🤔 It is primarily used for **version control and collaborative software development**.

* 🤔 Companies want you to get familiar with using version control and using a cloud platform that would allow you to do what is mentioned above.

* 🤔 You may also want to **store your projects here**, because God forbid, your computer breaks on you and everything you did are all gone.

* 🤔 It is also a great habit to create **version controls** and **branches** (we will go over this in a bit), so if you ever mess up your code, you have a back-up.


## 🚀 Creating a New Project on GitHub
### 🧰 What You Need
* A GitHub account
* Git installed on your computer (optional but recommended)

---

### 📁 Step 1: Save your project into Github
1. Go to https://github.com
2. Log in to your account
3.  Click the “+” (top right corner) → New repository
4. Fill in:
	* Repository name (e.g., my-first-project)
	* Description (optional but helpful)
5. Choose:
	* Public (anyone can see it) OR Private
6. Click **Create repository**

##### 😉 **Note**:

* We’ll save the new sandbox directory we just created here. So, **DON'T initialize with a README** (keep things clean for your first repo)
---

### 💻 Step 2: Open your Project in Terminal

1. Navigate to your project folder:
	* cd path/to/your-project

```
</> Bash example:
cd Desktop
cd sandbox
```

2. Open your project in your code editor:
	* On your terminal, type 'code .'

```
</> Bash example:
code .
```
---
### 🔧 Step 3: Initialize Git

1. This turns your folder into a Git-tracked project:
	* On your code editor, open the terminal. You will be using this terminal when you're working on a specific project
	* Then type: 'git init'

```
</> Bash example:
git init
```

---
### 📦 Step 4: Stage and Commit Your Files
* On the terminal, you will now type these:

```
</> Bash example:
git add .
git commit -m "Initial commit"
```

---
### 🔗 Step 5: Connect to GitHub
* Copy the repository URL from GitHub, then on your terminal:

```
</> Bash example:
git remote add origin https://github.com/your-username/your-repo-name.git
```

---
### ☁️ Step 6: Push Your Project
* On your code editor terminal, type:

```
</> Bash example:
git branch -M main
git push -u origin main
```
---
### ✅ Done
* Your local project is now:
	* Backed up on GitHub
	* Version-controlled
	* Ready to share or build on

---
## Next Steps:
* In lesson 03_Git, we will create our very first Readme and get experience in how to write in **Markdown**
* You will also learn more Git commands

---

*© All rights reserved @CCASALME Steal My Notes Here 2026*