# 🧠 PySocialLab

**PySocialLab** is a lightweight, pure Python project simulating a miniature social network with data cleaning and recommendation features — all built with **no external libraries**, designed to be run inside **Jupyter Notebooks**.

> 🔍 Explore social connections  
> 💡 Get friend & page recommendations  
> 🛠 Clean messy JSON data  
> 🐍 100% Python, zero dependencies, Jupyter-ready

## 🚀 Project Overview

This project processes unstructured JSON data describing users, their friendships, and liked pages. It provides:

- **Data Cleaning**: Removes duplicates, empties, and inactive users/pages.  
- **Friend Recommendations**: Suggests "People You May Know" based on mutual friends.  
- **Page Recommendations**: Suggests pages you might like based on similar interests.  
- **Pure Python Logic**: Implemented using only Python’s standard library, ideal for learning and simplicity.

## 🧩 Features

- Remove users with empty names  
- Deduplicate friend lists  
- Filter out inactive users  
- Deduplicate pages  
- Recommend friends based on mutual connections  
- Recommend pages based on shared likes

## 🖥️ How to Run

To run this project locally in **Jupyter Notebook**:

```bash
git clone https://github.com/DSxManash/PySocialLab.git
cd PySocialLab
jupyter notebook
```

Open the notebooks and run each cell step-by-step.  

## 🛠 Technology Stack

- Python 3.x (Standard Library only)  
- Jupyter Notebook  
- No external dependencies

## 📄 Sample Data Format

```json
{
  "users": [
    {
      "id": 1,
      "name": "Amit",
      "friends": [2, 3],
      "liked_pages": [101]
    }
  ],
  "pages": [
    {
      "id": 101,
      "name": "Python Developers"
    }
  ]
}
```