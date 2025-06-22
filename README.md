# Mini-Project-Marks-Adding
Marks Adding System is a scalable Python tool that automates score aggregation from CSV files. It reads roll numbers or candidate IDs, calculates total marks and exports the results. Ideal for academic institutions, training programs, online test platforms and recruitment bodies handling bulk evaluations.

## Project Structure
marks_adding_system/
├── marks.csv          # Input file containing roll numbers and marks
├── total_marks.csv    # Output file with total marks per candidate
├── marks_adder.py     # Main Python script for processing data
└── README.md          # Project documentation

## Industrial Applications
Start
  │
  ▼
Read `marks.csv`
  │
  ▼
Extract Header (Roll Num, Marks)
  │
  ▼
For each row in CSV:
  ├─► Check if Roll Num exists in dictionary
  │      ├─ Yes: Add marks to existing total
  │      └─ No: Create new entry with initial marks
  │
  ▼
Print Total Marks per Student
  │
  ▼
Write results to `total_marks.csv`
  │
  ▼
End

## Future Enhancements
- Add grading (A/B/C based on marks)
- Visualize data using bar/pie charts
- Add web or GUI interface using Tkinter/Streamlit
- Integrate into school ERP systems









