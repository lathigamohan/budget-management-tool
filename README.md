# 🧾 Budget Management Tool

A Python-based desktop application for managing personal finances with ease, built using `Tkinter`, `Pandas`, and `Matplotlib`. This tool allows users to set a budget, add and categorize expenses, and visualize spending through interactive charts—all while maintaining offline functionality and data privacy.

---

## 📌 Overview

Effective personal finance management begins with understanding where your money goes. This Budget Management Tool provides:

- A user-friendly graphical interface for daily expense tracking.
- Clear categorization and organization of spending habits.
- Visual insights to support better financial decisions.
- Complete offline access with no reliance on third-party apps or cloud services.

---

## 🎯 Key Features

### ✅ Dashboard
- View current budget in real-time.
- Summary of financial status.

### ✍️ Add Expense
- Enter expense description, amount, and category.
- Supported categories: `Food`, `Transport`, `Entertainment`, `Utilities`, `Other`.

### 📂 View Expenses
- Display all recorded expenses in a sortable table.
- Option to delete selected entries.

### 📊 Export Reports
- Generate pie charts showing category-wise expense distribution.
- Uses `Matplotlib` for visual representation.

---

## 🛠 Technologies Used

| Library             | Purpose                                           |
|---------------------|---------------------------------------------------|
| `Tkinter` / `ttkbootstrap` | GUI interface with themed widgets            |
| `Pandas`            | Data storage and manipulation (CSV format)        |
| `Matplotlib`        | Expense visualization via charts                  |
| `os`                | File existence checks and local storage handling  |

---

## 💻 How to Use

### ⚙️ Prerequisites

Ensure Python 3.9+ is installed on your system. Install the required libraries:

```bash
pip install pandas matplotlib ttkbootstrap
