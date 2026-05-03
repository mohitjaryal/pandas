# 🐼 Pandas — Complete Learning Repository

> A structured, hands-on collection of Jupyter Notebooks for mastering **Pandas** — from core basics to advanced data manipulation techniques.

---

## 📌 About This Repository

This repository is a **beginner-to-advanced guide** to the Pandas library in Python. Each notebook is focused on a specific topic, making it easy to learn progressively or jump straight to what you need.

Whether you're starting your data science journey or sharpening your Pandas skills, this repo has you covered — with real datasets and practical examples throughout.

---

## 📁 Repository Structure

```
pandas/
│
├── 📓 basic_pandas.ipynb                  # Core Pandas concepts and operations
├── 📓 series_method.ipynb                 # Series creation and methods
├── 📓 data_frames.ipynb                   # Deep dive into DataFrames
├── 📓 data_frames_methods.ipynb           # DataFrame methods and GroupBy operations
├── 📓 groupby_object.ipynb                # GroupBy — IPL deliveries dataset practice
├── 📓 merging_joining_concatenating.ipynb # Combining DataFrames
├── 📓 vectorized_operations.ipynb         # Fast vectorized operations with Pandas/NumPy
├── 📓 pandas_multi_index.ipynb            # Multi-level indexing
├── 📓 date_time.ipynb                     # DateTime handling in Pandas
├── 📂 data/                               # Datasets used across notebooks
└── 📄 README.md                           # You are here!
```

---

## 📓 Notebooks Overview

### 1. `basic_pandas.ipynb` — Pandas Basics
An introduction to the Pandas library covering essential concepts:
- Importing Pandas and understanding its role in data science
- Pandas **Series** — creating and manipulating 1D data
- Reading data from CSV, Excel, and other formats
- Inspecting data: `.head()`, `.tail()`, `.info()`, `.describe()`
- Indexing, selecting, and filtering rows
- Handling missing values (`NaN`)
- Sorting, renaming, and dropping columns

---

### 2. `series_method.ipynb` — Series Methods
A focused look at Pandas **Series** and its built-in methods:
- Creating Series from lists, dicts, and scalars
- Common methods: `.value_counts()`, `.sort_values()`, `.map()`, `.apply()`
- Arithmetic and statistical operations on Series
- Boolean indexing and masking

---

### 3. `data_frames.ipynb` — Working with DataFrames
An in-depth exploration of Pandas **DataFrames**:
- Creating DataFrames from dictionaries, lists, and CSV files
- Accessing rows and columns using `.loc[]` and `.iloc[]`
- Adding, removing, and renaming columns
- Filtering and querying DataFrames
- Exporting DataFrames to CSV/Excel

---

### 4. `data_frames_methods.ipynb` — DataFrame Methods & GroupBy
Practical usage of key DataFrame methods:
- Aggregation functions: `.sum()`, `.mean()`, `.count()`, `.min()`, `.max()`
- GroupBy objects — grouping and performing operations
- Finding insights like number of movies, average ratings, etc.
- Pivot tables and cross-tabulations

---

### 5. `groupby_object.ipynb` — GroupBy in Depth
Hands-on practice with `.groupby()` using the **IPL Deliveries Dataset**:
- Grouping by teams, players, and match conditions
- Aggregating runs, wickets, and other stats
- Chaining GroupBy with filtering and sorting
- Real cricket analytics use cases

---

### 6. `merging_joining_concatenating.ipynb` — Combining DataFrames
Everything you need to know about combining data:
- **Concatenation** — stacking DataFrames vertically and horizontally
- **Merging** — SQL-style joins (inner, left, right, outer)
- **Joining** — index-based combination
- Handling duplicate columns and overlapping keys

---

### 7. `vectorized_operations.ipynb` — Vectorized Operations
Writing fast, efficient Pandas code:
- Why vectorization beats loops in Pandas
- Arithmetic operations across Series and DataFrames
- Using NumPy with Pandas for numerical speed
- String vectorization with `.str` accessor
- Applying conditions without explicit iteration

---

### 8. `pandas_multi_index.ipynb` — Multi-Level Indexing
Working with hierarchical data structures:
- Creating and setting MultiIndex DataFrames
- Indexing with `.loc[]` on multiple levels
- Stacking and unstacking multi-level columns
- Practical use cases for nested/grouped data

---

### 9. `date_time.ipynb` — DateTime Handling
Parsing and working with time-series data:
- Converting strings to DateTime using `pd.to_datetime()`
- Extracting components: year, month, day, weekday
- DateTime indexing and slicing
- Resampling and rolling window operations
- Time-zone handling basics

---

### 10. `data/` — Datasets
Real-world dataset files (`.csv`, `.xlsx`, etc.) used across notebooks for practical examples — including IPL match data and more.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| 🐍 Python 3.x | Programming Language |
| 🐼 Pandas | Data Analysis & Manipulation |
| 📓 Jupyter Notebook | Interactive Python Environment |
| 📊 NumPy | Numerical & Vectorized Operations |

---

## 🚀 Getting Started

### Prerequisites

Make sure Python is installed, then install the required libraries:

```bash
pip install pandas numpy jupyter
```

### Run the Notebooks

1. **Clone this repository:**
```bash
git clone https://github.com/mohitjaryal/pandas.git
cd pandas
```

2. **Launch Jupyter Notebook:**
```bash
jupyter notebook
```

3. **Open any notebook** from the browser and start learning! 🎉

---

## 🗺️ Suggested Learning Path

```
basic_pandas.ipynb
      ↓
series_method.ipynb
      ↓
data_frames.ipynb
      ↓
data_frames_methods.ipynb
      ↓
groupby_object.ipynb
      ↓
merging_joining_concatenating.ipynb
      ↓
vectorized_operations.ipynb
      ↓
pandas_multi_index.ipynb
      ↓
date_time.ipynb
```

---

## 💡 Who Is This For?

- 🎓 Students learning Python for Data Science
- 👩‍💻 Beginners exploring data manipulation
- 📊 Anyone building a strong Pandas foundation step by step

---

## 🤝 Contributing

Contributions, suggestions, and improvements are always welcome!

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add: your feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📬 Connect with Me

| Platform | Link |
|----------|------|
| 🌐 Website | [mohitjaryal.online](https://mohitjaryal.online) |
| 💼 LinkedIn | [in/mohitjaryal](https://www.linkedin.com/in/mohitjaryal) |
| 🐦 Twitter/X | [@mohitjaryal04](https://x.com/mohitjaryal04) |
| 💻 GitHub | [mohitjaryal](https://github.com/mohitjaryal) |
| 🧩 LeetCode | [mohitjaryal](https://leetcode.com/u/mohitjaryal) |
| 🧩 HackerRank | [mohitjaryal](https://hackerrank.com/u/mohitjaryal) |

---

<div align="center">

**⭐ If this repo helped you, consider giving it a star — it motivates me to keep learning and sharing!**

*Made with 💙 by [Mohit Jaryal](https://mohitjaryal.online)*

> *"Data is the new oil, and Pandas is the refinery."* 🐼

</div>
