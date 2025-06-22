# Mini-Project-Marks-Adding
Marks Adding System is a scalable Python tool that automates score aggregation from CSV files. It reads roll numbers or candidate IDs, calculates total marks and exports the results. Ideal for academic institutions, training programs, online test platforms and recruitment bodies handling bulk evaluations.

## Project Structure
```mermaid
flowchart TB
    A["Start"] --> B["Import necessary libraries e.g., pandas, csv, os"]
    B --> C["Load CSV dataset(Roll No. & Marks)"]
    C --> D["Validate & clean data e.g., missing or invalid IDs"]
    D --> E["Calculate total marks per student (Roll No.)"]
    E --> F["Store results in new file e.g., result.csv"]
    F --> G["Display/export summary average, topper, etc."]
    G --> H["End"]
```
## Aim
<img src="https://github.com/psrana/Mini-Project-Marks-Adding/assets/7460892/9be14aa0-eaa0-403a-9575-32771724f0e2" width="60%" height="80%" />

## Industrial Applications
- Educational Institutes: Exam and internal assessment score processing
- Corporate Training: Skill test score aggregation across sessions
- EdTech Platforms: Backend for test evaluation and analytics
- Recruitment Agencies: Score tabulation across multi-stage evaluations

## Future Enhancements
- Add grading (A/B/C based on marks)
- Visualize data using bar/pie charts
- Add web or GUI interface using Tkinter/Streamlit
- Integrate into school ERP systems









