# Exploring NYC Public School Test Result Scores

This project uses data manipulation and summary statistics to analyze SAT scores from public high schools in New York City. The goal is to highlight top-performing schools and examine score variability across boroughs. The SAT consists of Math, Reading, and Writing sections, each scored out of 800. All analysis was completed using DataCamp’s Datalab environment.

## 🎯 Project Objectives

- Identify schools with **high average SAT math scores**
- Find the **top 10 schools** based on total SAT scores
- Determine which **borough has the largest standard deviation** in SAT scores

## 🗃️ Dataset Overview

The dataset used in this analysis is [`schools.csv`](./schools.csv) and contains the following columns:

| Column             | Description                                |
|--------------------|--------------------------------------------|
| `school_name`      | Name of the public high school             |
| `borough`          | NYC borough where the school is located    |
| `average_math`     | Average SAT Math score                     |
| `average_reading`  | Average SAT Reading score                  |
| `average_writing`  | Average SAT Writing score                  |

An additional column was created during the analysis:
- `total_SAT`: Sum of Math, Reading, and Writing scores

## 🔍 Key Findings

- 🧮 **Stuyvesant High School** had the highest average math score (754)
- 🏅 The **top 10 schools** were ranked by total SAT score (math + reading + writing)
- 🗺️ **Manhattan** had the highest **standard deviation** in SAT scores, indicating the widest performance range

## 🛠️ Tools Used

- **Python**
- **pandas** for data manipulation and summary statistics

## 📌 How to Use

1. Clone or download this repository
2. Open the notebook [`Exploring_NYC_Public_School_Scores.ipynb`](./Exploring_NYC_Public_School_Test_Result_Scores.ipynb) in Jupyter or any compatible environment
3. Run the cells to reproduce the results
4. Adjust filters to explore different subjects, score thresholds, or borough-level patterns

## ✍️ Author

Project by **Achraf Salimi** — part of an ongoing journey to build and showcase data skills.
