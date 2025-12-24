Spec-Kit-Plus: Easy Installation & Getting Started Guide

This repository provides a simple, step-by-step guide to installing and using Spec-Kit-Plus for Spec-Driven Development.
It is written for beginners who want clear instructions without confusion.

📌 What is Spec-Driven Development?

Spec-Driven Development is a modern approach to building software where specifications are the primary source of truth.

Instead of writing code first and treating documentation as an afterthought, this method:

Starts with clear, structured specs

Turns those specs into actionable plans

Uses AI tooling to help generate and implement code

In short:
📄 Specs don’t just describe software — they help build it.

🚀 Why Use Spec-Kit-Plus?

Spec-Kit-Plus helps you:

Define project principles clearly

Describe features in plain language

Convert ideas into technical plans

Break plans into executable tasks

Implement features step-by-step with AI assistance

This repository focuses on installation and first usage, not theory.

⚙️ Prerequisites

Before installing Spec-Kit-Plus, make sure you have:

Python 3.9 or newer

pip or uv installed

A terminal (Command Prompt, PowerShell, or Bash)

An AI provider account (e.g., Claude), if you plan to use AI features

📦 Installation Options

You can use Spec-Kit-Plus in two ways:

✅ Option 1: Install Once (Recommended)

This installs Spec-Kit-Plus globally so you can use it anytime.

Install using pip
pip install specifyplus

OR install using uv
uv tool install specifyplus

Verify installation
specifyplus check


or

sp check


If the command runs successfully, installation is complete 🎉

🔄 Upgrade Spec-Kit-Plus Later

Using pip:

pip install -U specifyplus


Using uv:

uv tool upgrade specifyplus

🗑️ Uninstall (if needed)
pip uninstall specifyplus


or

uv tool uninstall specifyplus

⚡ Option 2: Run Without Installing

If you don’t want a permanent install, you can run it directly:

uvx specifyplus --help


Create a project:

uvx specifyplus init my-project


or

uvx sp init my-project


⚠️ Note: This method is best for testing. Long-term use is easier with a persistent install.

📂 Create a New Project

After installation:

specifyplus init my-project


or shorter:

sp init my-project


To initialize in the current directory:

sp init --here --ai claude

🧭 Core Workflow (Step-by-Step)

Once your project is initialized, Spec-Kit-Plus follows a clear workflow:

1️⃣ Define Project Principles

Create rules and standards that guide development:

/sp.constitution


Use this to define:

Code quality expectations

Testing standards

Performance goals

UX consistency

These principles influence everything that comes next.

2️⃣ Describe What You Want to Build

Explain the feature in plain language:

/sp.specify


Example:

Build an application that organizes photos into albums by date. Albums appear on a main page and can be reordered by dragging. Albums cannot be nested. Photos are displayed in a grid layout.

Focus on what the app does, not how it’s built.

3️⃣ Choose the Technical Approach

Now explain your tech decisions:

/sp.plan


Example:

Use Vite with minimal dependencies. Prefer vanilla HTML, CSS, and JavaScript. Store metadata locally using SQLite. Images remain on the user’s device.

4️⃣ Generate Development Tasks

Convert the plan into actionable steps:

/sp.tasks


This creates a structured task list.

5️⃣ Implement the Feature

Execute tasks and build the feature:

/sp.implement

📁 Suggested Repository Structure
spec-kit-plus-guide/
├── README.md
├── docs/
│   ├── installation.md
│   ├── workflow.md
│   └── troubleshooting.md
└── examples/
    └── sample-spec.md


You can expand this later as your guide grows.

❗ Common Issues & Tips

If sp command is not recognized, restart your terminal

Run sp check to verify setup

Prefer persistent installation for daily usage

Keep specs clear and non-technical in early steps

📚 Helpful Resources

Spec-Kit official repository

AI provider documentation (Claude, etc.)

Python & uv tool documentation

🤝 Contributing

If you want to improve this guide:

Fork the repo

Create a new branch

Submit a pull request