# 🧭 Programming Fundamentals & Project Roadmap

Welcome to your **AI-assisted programming fundamentals and project roadmap**!
This repository guides you through structured, project-based learning in **Python, Go, and TypeScript** — all with the goal of building a solid programming foundation that lets you **leverage AI effectively for development** and **build practical, day-to-day tools**.

---

## 🎯 Learning Goals

- Understand core programming concepts: variables, data types, control flow, functions, and OOP.
- Build confidence in problem-solving by creating small, functional projects.
- Learn by developing practical applications that can be run locally.
- Develop general knowledge in modern languages & ecosystems.
- Use AI responsibly — as a teacher, not a crutch.

---

## 🐍 Python Fundamentals

### 🧩 Key Concepts
- Variables, data types, loops, conditionals
- Functions and modules
- Lists, dictionaries, and sets
- File handling
- Error handling

### 🧠 AI Practice Prompts
- “Explain why a for-loop is better than a while-loop here.”
- “How can I refactor this to make it more modular?”
- “What’s the time complexity of this list search?”

---

## 🦫 Go (Golang)

### 🧩 Key Concepts
- Static typing, structs, interfaces
- Packages and modules
- Error handling and concurrency (goroutines, channels)
- HTTP and JSON handling


### 🧠 AI Practice Prompts
- “Help me write idiomatic Go code.”
- “Explain this panic message and how to fix it.”
- “Can you review this Go function for clarity and efficiency?”

---

## ⚙️ TypeScript

### 🧩 Key Concepts
- Type annotations and interfaces
- Functions, modules, and imports
- Generics and utility types
- Working with APIs (fetch, async/await)
- Basic Node.js CLI development


### 🧠 AI Practice Prompts
- “Explain what this TypeScript error means.”
- “Convert this JavaScript snippet into safe TypeScript.”
- “What’s the right way to type an async function returning JSON?”


---

## 📚 Project Ideas for Learning Programming Fundamentals

These projects are designed to grow from simple Python scripts to full APIs and eventually to cloud deployment.

---

### 🌱 Tier 1 — Local Python Projects (Your Starting Point)

These are simple, local scripts you run from Terminal while learning Python fundamentals.

#### 1. Personal Finance Tracker (Local CSV → Numbers Automation)
A project that automates your spreadsheet workflow without relying on bank APIs.

**You will learn:**
- File handling
- CSV parsing
- Data cleaning
- Pivot-style analysis
- Basic data modelling

**Possible extensions:**
- Monthly spending summaries
- Detect recurring expenses
- Category-based trend analysis

#### 2. Watchlist Manager (Notes → Structured System)
Turn messy TV show/film notes into a proper local database.

**You will learn:**
- Text parsing
- CRUD operations
- SQLite database basics
- CLI design patterns

**Possible extensions:**
- Episode progress tracking
- Local recommendation engine
- (Optional) Check where shows are streaming

#### 3. Nutrition / Calorie Tracker (Local Only)
A basic calories-in / calories-out tracker.

**You will learn:**
- Relational data design
- Handling user input
- Calculations & summaries

**Possible extensions:**
- Graphs and progress charts
- Weekly reports
- Pre-defined meal templates

#### 4. Life Admin Dashboard (CLI Version)
Combine multiple utilities into one personal tool:
- tasks
- reminders
- habits
- finances

Great for practicing basic system architecture thinking.

---

### 🌿 Tier 2 — Local Web Apps (FastAPI / Flask / Streamlit)

Once you are comfortable with Python basics, move to web applications that run locally.

#### 5. Personal Finance API + Dashboard
Build your own REST API and front-end dashboard.

**Tech stack:**
- **Backend:** FastAPI
- **Frontend:** React or Next.js
- **Database:** SQLite

**Features:**
- `/transactions`
- `/categories`
- `/summary/monthly`
- Budget alerts

This project teaches real API fundamentals and prepares you for cloud deployment.

#### 6. Streaming Watchlist Web App
Expand the Tier 1 Watchlist Manager into a full web app.

**Features:**
- Store shows in a database
- Track episodes watched
- Display progress
- Optional: call public streaming availability APIs

#### 7. Nutrition App (Web Version)
A more polished version of your calorie tracker.

**Features:**
- Food database
- Meal logs
- Weekly calorie graphs
- Weight tracking dashboard

---

### 🌳 Tier 3 — Projects for GCP + Kubernetes Deployment

These let you learn containerization, microservices, and cloud architecture.

#### 8. Finance Microservice Architecture
A cloud-ready version of your Finance API.

**Services:**
- `transactions-service`
- `categories-service`
- `reports-service`
- `auth-service`

**Skills you learn:**
- Docker
- Microservice boundaries
- API gateways
- Monitoring & logging
- Deployment to GKE or Cloud Run

#### 9. Streaming Discovery Service
A scalable system for finding and organizing series/film metadata.

**Includes:**
- Metadata ingestion service
- Recommendation logic
- Web UI

#### 10. Nutrition AI Service
Use ML/AI services (e.g., Vision API) to build a smarter nutrition system.

**Features:**
- Food recognition
- Calorie estimation
- Meal suggestions
- Analytics dashboard

---

## ⭐ Choosing the Right Starting Point

Here’s the best path depending on your initial focus:

| Goal | Best Starting Project |
|------|------------------------|
| File handling & data processing | Personal Finance Tracker |
| CRUD + databases | Watchlist Manager |
| Data modelling & calculations | Nutrition Tracker |
| Web development fundamentals | Finance API |
| Long-term project for cloud/Kubernetes | Finance API or Nutrition API |

---

## 🎯 Recommended Starting Project

Based on your interests (automation, APIs, spreadsheets), start with:

### 👉 **Personal Finance Tracker API**

**Why:**
- starts simple
- grows into a real API
- can evolve into a full web app
- perfect candidate for Docker, microservices & GCP deployment

---

## 💬 How to Use AI Effectively

| Scenario | Best Prompt Style |
|-----------|-------------------|
| Debugging | “Explain this error in simple terms and how to fix it.” |
| Refactoring | “How can I make this function more modular?” |
| Learning | “Compare Python lists and Go slices with examples.” |
| Exploration | “Give me 3 small project ideas using React and APIs.” |

---

## 🧠 Mindset & Habits

- **Start with curiosity.** Ask “why?” before asking “how?”
- **Use AI as a collaborator, not a substitute.** Always read and tweak generated code.
- **Document your learning.** Each folder includes a README for your reflections.
- **Build in public.** Share your projects and progress to stay motivated.

---

## 📚 Suggested Tools

- **VS Code** with Python, Go, TypeScript, and React extensions.
- **Git + GitHub** for version control.
- **Homebrew** to install dependencies on macOS.
- **Postman or cURL** for testing APIs.
- **.NET SDK** (`dotnet`) and the C# extension for VS Code (for building and running C# projects).
- **SQLite Browser** for managing SQLite databases.
- **Docker Desktop** for containerization.

---

## 🚀 After the Roadmap

When you’ve completed the initial project tiers, you’ll be able to:
- Read and write code in multiple languages.
- Debug, refactor, and improve AI-generated code.
- Design and implement small to medium-sized projects independently.
- Build and deploy web applications locally and to the cloud.
- Contribute to open-source or AI-assisted development workflows.

---

### 🌟 Next Steps

- Explore **advanced backend frameworks** (e.g., FastAPI, Fiber, Express).
- Learn **more about databases** (e.g., PostgreSQL, MongoDB).
- Practice **system design** and **API architecture**.
- Continue to use AI — but always verify and understand what it produces.
