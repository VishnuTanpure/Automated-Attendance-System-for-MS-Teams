# Automated Attendance System for MS Teams

## Project Overview

This Python program automates the attendance process for online lectures conducted via MS Teams. Developed during the COVID-19 period to address challenges faced by students and teachers, the program is designed to reduce the tedious and time-consuming task of manually marking attendance. It tackles issues such as network disruptions, late arrivals, and students staying in the lecture for only a short amount of time. 

With this program, the attendance data is processed and recorded based on pre-defined rules, ensuring that students are marked appropriately. The processed attendance is automatically updated into an Excel file for the subject teacher’s convenience.

## Key Features

- **Attendance Rules**:  
  1. Students must be present for at least **60% of the total lecture duration**. If not, they will be marked as **PP (Partially Present)**, and their attendance will not be considered.
  2. If a student is **disconnected 5 or more times** during the lecture, they will be marked present regardless of the total time present.
  3. A **5-minute grace period** is provided for late arrivals. Students joining after the grace period will still be marked present, but their attendance cell will be highlighted in **yellow**.

- **Excel Output**: Attendance is automatically filled in a separate Excel file with proper formatting and color coding for late attendees.

- **Automated Workflow**: The program processes the raw attendance data downloaded from MS Teams, filters out multiple entries for the same student (due to disconnections), and applies the attendance rules efficiently.

## Technologies Used

- **Python**
- **Google Colab** (For code execution and testing)
- **Pandas** (For data manipulation)
- **Openpyxl** (For working with Excel files)

You can customize the README further to include more specific details about your code, or add any future updates or plans for the project.
