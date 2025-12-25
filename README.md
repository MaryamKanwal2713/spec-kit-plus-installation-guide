# Spec-Kit-Plus: Easy Installation & Getting Started Guide

This repository provides a simple, step-by-step guide to installing and using Spec-Kit-Plus for Spec-Driven Development.  
It is written for beginners who want clear instructions without confusion.

---

## 📌 What is Spec-Driven Development?

Spec-Driven Development is a modern approach to building software where specifications are the primary source of truth.

Instead of writing code first and treating documentation as an afterthought, this method:

- Starts with clear, structured specs  
- Turns those specs into actionable plans  
- Uses AI tooling to help generate and implement code  

In short:  
📄 Specs don’t just describe software — they help build it.

---

## 🚀 Why Use Spec-Kit-Plus?

Spec-Kit-Plus helps you:

- Define project principles clearly  
- Describe features in plain language  
- Convert ideas into technical plans  
- Break plans into executable tasks  
- Implement features step-by-step with AI assistance  

This repository focuses on installation and first usage, not theory.

---

## ⚙️ Prerequisites

Before installing Spec-Kit-Plus, make sure you have:

- Python 3.9 or newer  
- pip or uv installed  
- A terminal (Command Prompt, PowerShell, or Bash)  
- An AI provider account (e.g., Claude), if you plan to use AI features  

---

## 📦 Installation Options

You can use Spec-Kit-Plus in two ways:

### ✅ Option 1: Install Once (Recommended)

Install Spec-Kit-Plus globally so you can use it anytime.

Install using pip:

~~~bash
pip install specifyplus
~~~

Or install using uv:

~~~bash
uv tool install specifyplus
~~~

Verify installation by running either command:

~~~bash
specifyplus check
~~~
or
~~~bash
sp check
~~~

If the command runs successfully, installation is complete 🎉

### 🔄 Upgrade Spec-Kit-Plus Later

Upgrade using pip:

~~~bash
pip install -U specifyplus
~~~

Or upgrade using uv:

~~~bash
uv tool upgrade specifyplus
~~~

### 🗑️ Uninstall (if needed)

Uninstall using pip:

~~~bash
pip uninstall specifyplus
~~~

Or uninstall using uv:

~~~bash
uv tool uninstall specifyplus
~~~

---

### ⚡ Option 2: Run Without Installing

Run Spec-Kit-Plus directly without installing:

~~~bash
uvx specifyplus --help
~~~

Create a project:

~~~bash
uvx specifyplus init my-project
~~~
or
~~~bash
uvx sp init my-project
~~~

> ⚠️ This method is best for testing. Long-term use is easier with a persistent install.

---

## 📂 Create a New Project

After installation, create a new project:

~~~bash
specifyplus init my-project
~~~

Or use the short form:

~~~bash
sp init my-project
~~~

To initialize in the current directory:

~~~bash
sp init --here --ai claude
~~~

---

## 🧭 Core Workflow (Step-by-Step)

Once your project is initialized, Spec-Kit-Plus follows this workflow:

### 1️⃣ Define Project Principles

~~~bash
/sp.constitution
~~~

Define:
- Code quality expectations  
- Testing standards  
- Performance goals  
- UX consistency  

### 2️⃣ Describe What You Want to Build

~~~bash
/sp.specify
~~~

Example:

> Build an application that organizes photos into albums by date. Albums appear on a main page and can be reordered by dragging. Albums cannot be nested. Photos are displayed in a grid layout.

### 3️⃣ Choose the Technical Approach

~~~bash
/sp.plan
~~~

### 4️⃣ Generate Development Tasks

~~~bash
/sp.tasks
~~~

### 5️⃣ Implement the Feature

~~~bash
/sp.implement
~~~

---

## 📁 Suggested Repository Structure

spec-kit-plus-guide/
├── README.md
├── docs/
│ ├── installation.md
│ ├── workflow.md
│ └── troubleshooting.md
└── examples/
└── sample-spec.md


---

## ❗ Common Issues & Tips

- If the `sp` command is not recognized, restart your terminal  
- Run `sp check` to verify setup  
- Prefer persistent installation for daily usage  
- Keep specs clear and non-technical in early steps  

---

## 📚 Helpful Resources

- Spec-Kit official repository  
- AI provider documentation (Claude, etc.)  
- Python & uv tool documentation  

---

## 🤝 Contributing

If you want to improve this guide:

- Fork the repo  
- Create a new branch  
- Submit a pull request  
