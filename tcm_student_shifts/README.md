# 📘 TCM_Shifts.ipynb

## 🧾 Project Overview

This Jupyter notebook is designed to manage and visualize student shift schedules for Traditional Chinese Medicine (TCM) clinical practice. It handles loading, assigning, and analyzing student responsibilities across multiple weeks while ensuring fairness and avoiding conflicts due to absences.

## 📂 Input Data

- `student_shifts.csv`: A CSV file containing the shift schedule and student names.

## 🔧 Features

- Load and display student shift data.
- Automatically assign students to **Cleaner** and **Receptionist** roles.
- Ensure fair distribution of tasks across students.
- Avoid scheduling students during their known absence periods.
- Analyze and visualize task assignment statistics using graphs and tables.

## 🛠️ Libraries Used

- `pandas` – for data manipulation
- `numpy` – for numerical operations
- `matplotlib` – for visualizations
- `random` – for fair shuffling when assigning roles

## ▶️ How to Use

1. Ensure the file `student_shifts.csv` is present in the same directory.
2. Open and run `Ttcm_shifts.ipynb` step-by-step in Jupyter Notebook.
3. Review the final schedule and visual reports for each student's shift participation.
