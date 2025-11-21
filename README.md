# vasuki_sachin_personal-study-plan-recommendation
Below is a **clean, professional, and complete README.md** written specifically for the project you shared (PlanAlert – AI-Powered Student Study Companion).
You can copy-paste it directly into a `README.md` file.

---

# 📘 **PlanAlert – AI-Powered Student Study Companion**

A modern, AI-powered study planning app built with **React**, **React Router**, and **Glassmorphism UI**—all inside a single-page HTML environment using **Babel** and **UNPKG CDN** libraries.

PlanAlert helps students create personalized weekly study plans, view curated learning resources, and take AI-generated weekly knowledge tests.

---

## 🚀 **Features**

### 🧠 **AI-Generated Weekly Timetable**

* Automatically generates a personalized weekly study plan.
* Adjusts topics based on:

  * Chosen Category
  * Degree
  * Weekly Goal
* Smart links to relevant study resources.

### 📚 **Curated Notes & Video Resources**

* Filter by:

  * Subject
  * Resource Type (Notes / Videos)
  * Language
* Automatically shows resources based on your selected degree.

### 📝 **Weekly Test System**

* AI-generated quiz questions per subject.
* Tracks:

  * Answers
  * Score
  * Accuracy
* Provides quick assessment of knowledge gaps.

### 🗂️ **Clean, Modern UI with Glassmorphism**

* Sidebar navigation
* Floating header
* Responsive layout
* Animated transitions

### 🔐 **(Optional) Login / Register Pages**

The template supports routes for Login & Register (components can be added as needed).

---

## 🧩 **Technology Stack**

| Component            | Technology                      |
| -------------------- | ------------------------------- |
| **Frontend**         | React 18 (via CDN)              |
| **Routing**          | React Router DOM 6              |
| **Compiler**         | Babel Standalone                |
| **UI**               | Glassmorphism + Custom CSS      |
| **Icons**            | Custom SVG Components           |
| **State Management** | React Hooks                     |
| **Data Persistence** | LocalStorage (Degree Selection) |

---

## 📁 **Project Structure**

Although this runs in a **single HTML file**, the structure follows a component-based approach:

```
index.html
 ├── <script> React Components
 │     ├── Landing
 │     ├── Dashboard
 │     ├── Resources
 │     ├── Test
 │     ├── Support
 │     ├── Utility Functions
 │     │     ├── generateTimetable()
 │     │     └── generateWeeklyTest()
 │     ├── Sidebar (to be added)
 │     ├── Header  (to be added)
 │     └── Router Setup
 └── CSS: Glass UI + Animations
```

---

## ⚙️ **How It Works**

### **1. Select Category & Degree**

Users pick a Category → Degree combo from preset educational fields such as:

* Engineering
* Medical
* Arts & Humanities
* Commerce

Each degree includes its own subject list.

---

### **2. Enter a Study Goal**

Example:

> “I want to focus on Thermodynamics this week.”

This goal is embedded into the AI-generated plan.

---

### **3. Generate Plan**

The system maps subjects to relevant topics via `topicMap` and produces:

* Daily schedule
* Subject focus
* Topic of the day
* AI-generated details
* Direct link to matching resources

---

### **4. Resource Filtering**

Resources include:

* PDF Notes
* DOCX Notes
* Video Lectures
* Multi-language support

Users can filter by:

* Subject
* Type
* Language

---

### **5. Weekly Knowledge Test**

Generates simple AI-based questions like:

* Key concept questions
* True/False patterns
* Real-world application checks

After completion, students receive:

* Score
* Performance indicator
* Return to dashboard option

---

## 🧪 **Mock Data Included**

### **Categories, Degrees & Subjects**

Pre-loaded academic fields with multiple degree programs.

### **Resource Library**

18+ mock resources:

* English, Hindi, Spanish, French
* Notes + Videos
* Science, Engineering, Commerce, Arts subjects

### **AI Test Bank Template**

Generic multiple-choice generator (`generateWeeklyTest()`).

---

## 🗺️ **Routing Overview**

| Route        | Component | Purpose                  |
| ------------ | --------- | ------------------------ |
| `/`          | Landing   | Marketing homepage       |
| `/login`     | Login     | User authentication page |
| `/register`  | Register  | User signup page         |
| `/dashboard` | Dashboard | Study plan generator     |
| `/resources` | Resources | Notes + Video listing    |
| `/test`      | Test      | Weekly knowledge test    |
| `/support`   | Support   | Contact info             |

---

## 🛠️ **How to Run Locally**

### **Option 1: Directly open the HTML file**

You can simply open the HTML file in any modern browser.

✔️ No setup
✔️ No build tools
✔️ Works instantly

---

### **Option 2: Run on a Local Server (Recommended)**

Use VS Code Live Server or:

```bash
npx serve
```

---

## 🧰 **Future Improvements**

* Add real authentication (Firebase / Supabase)
* Store study plans in a backend
* Replace mock data with API-driven content
* Add AI chatbot (OpenAI API)
* Add Calendar Sync (Google Calendar API)


