# 📊 Data Analysis Project (Custom Dataset + Titanic Dataset)

## 📌 Overview

This project consists of two main parts:

1. **Custom Dataset Creation** – Building a dataset from scratch using a Python dictionary
2. **Titanic Dataset Analysis** – Performing real-world data cleaning and analysis

The goal is to demonstrate foundational data analysis skills using Pandas.

## 🎯 Objectives

* Create a structured dataset manually
* Practice data exploration techniques
* Perform data cleaning on real-world data
* Analyze patterns using groupby operations
* Extract meaningful insights

## 🛠️ Tools & Technologies

* Python
* Pandas
* Jupyter Notebook / Visual Studio Code

## 📂 Project Structure

```id="projstruct"
Titanic-project/
│
├── CustomDataset.ipynb
├── Titanic-Dataset.csv
├── analysis.ipynb
├── README.md
```


# 🧱 Part 1: Custom Dataset Creation

## 📌 Description

In this section, a dataset was created manually using a Python dictionary and converted into a Pandas DataFrame.


## 📊 Dataset Features

The dataset contains:

* 5 columns (features)
* 15 rows (entries)
* Custom index values

Example features:

* Name
* Age
* Gender
* Score
* Passed


## 🎯 Purpose

This step helps in understanding:

* How datasets are structured
* How to create DataFrames manually
* How indexing works in Pandas


# 🚢 Part 2: Titanic Dataset Analysis

## 📊 Dataset Description

The Titanic dataset contains passenger information such as age, gender, class, and survival status.


## 🔍 Step 1: Data Exploration

Performed initial inspection using:

* `.head()` → preview data
* `.info()` → check structure and missing values
* `.describe()` → statistical summary


## 🧹 Step 2: Data Cleaning

Handled missing and unnecessary data:

* Filled missing **Age** values using median
* Filled missing **Embarked** values using mode
* Dropped **Cabin** column due to many missing values
* Removed duplicate rows


## 📈 Step 3: Data Analysis

### 🔹 Survival Rate by Gender

Females had a higher survival rate than males.

### 🔹 Survival Rate by Class

First-class passengers had the highest survival rate.

### 🔹 Average Age per Class

Different classes showed variation in average age.

### 🔹 Survival by Age Group

Passengers were grouped into:

* Child
* Teen
* Adult
* Senior


## 🔎 Step 4: Data Filtering

Filtered specific groups such as:

* Female survivors
* Child survivors
* First-class survivors


## 💡 Key Insights

* **Gender Impact:** Females were more likely to survive
* **Class Impact:** Higher class increased survival chances
* **Age Factor:** Children had better survival rates
* **Highest Survival Group:** First-class female children


## 🚀 How to Run

1. Clone the repository:

```id="clone"
git clone https://github.com/Ibsa-M/Custom-and-Titanic-project.git
```

2. Navigate to project:

```id="cd"
cd https://github.com/Ibsa-M/Custom-and-Titanic-project
```

3. Install dependencies:

```id="install"
pip install pandas
```

4. Run the notebook:

```id="run"
Open analysis.ipynb in Jupyter or VS Code
```


## 📌 Conclusion

This project demonstrates both basic and applied data analysis skills.
It starts with building a dataset from scratch and progresses to analyzing a real-world dataset, highlighting the importance of data cleaning and structured analysis.


<!-- ## ✨ Author

**Ibsa Magarsa**
 -->

## ⭐ Notes

This project is part of a data science learning journey and showcases practical skills in Python and Pandas.
