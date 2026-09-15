# Smart Placement Eligibility Bot

## 📌 Project Overview

The Smart Placement Eligibility Bot is an RPA-based automation project developed using UiPath. The bot automatically checks whether students are eligible for a placement drive based on predefined company criteria.

It reads student details and placement requirements from Excel files, compares the data, determines eligibility, provides reasons for ineligibility, and generates a final eligibility report.

---

## 🚀 Features

- Reads student data from an Excel file
- Reads placement drive criteria from an Excel file
- Checks student CGPA
- Validates 10th percentage
- Validates 12th percentage
- Checks the number of backlogs
- Verifies eligible branches
- Checks graduation year
- Determines Eligible or Not Eligible status
- Generates reasons for ineligibility
- Creates an automated placement eligibility report

---

## 🛠️ Technologies Used

- UiPath Studio
- Robotic Process Automation (RPA)
- Microsoft Excel
- UiPath Excel Activities

---

## 📂 Project Structure

```text
placementBot/
│
├── Main.xaml
├── project.json
│
└── Data/
    ├── Students.xlsx
    ├── Placement_Drive.xlsx
    └── Placement_Eligibility_Report.xlsx
