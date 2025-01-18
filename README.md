# **Excel Generator**

This plugin enables users to generate Excel files (.xlsx) quickly and efficiently.

### 🎯 **It Supports**
- **Multiple Sheets:** Create and organize data across multiple sheets in a single workbook.
- **Multiple Tables per Sheet:** Add multiple tables with independent configurations to each sheet.
- **Formula Columns:** Define and apply formulas using Excel's syntax (e.g., `=SUM(A1:A10)`).
- **Auto Filtering Mode**: Enable or disable automatic filtering on table columns.
- **Customizable Headers:** Option to include or skip headers for tables, ensuring flexibility in design.
- **Dynamic Cell Range:** Specify starting cells for tables to ensure accurate placement.
- Ability to **customize basic excel attributes**  
    - Choose font family.
    - Adjust font size for text, table titles, and headers.
    - Set border styles (thin, double, dashed, thick).
    - Enable options for column width fitting, auto filtering, and text wrapping.

### 📝 **Note:** 
- A plugin server must be set up to use this feature. Follow the detailed guide to set up a plugin server on Render: [How to Deploy Plugins Server on Render](https://docs.typingmind.com/plugins/plugins-server/how-to-deploy-plugins-server-on-render)
- The generated Excel files will be automatically removed after one hour.
- The plugin currently does not support adding graphs or embedding images in Excel files.

## **Example Usage**  
>Please generate an Excel file for a gradebook. The gradebook should include the following columns:
> 1. Student Name
> 2. Student ID
> 3. Assignment 1 Score
> 4. Assignment 2 Score
> 5. Midterm Exam Score
> 6. Final Exam Score
> 7. Total Score (calculated as the weighted average of assignments, midterm, and final exam)
> 8. Letter Grade (based on total score)
>
>The total score should be calculated with the following weights:
> * Assignments: 40% (20% for Assignment 1 and 20% for Assignment 2)
> * Midterm Exam: 30%
> * Final Exam: 30%
>
>The letter grade should be assigned based on the total score:
>* A: 90% or higher
>* B: 80%–89%
>* C: 70%–79%
>* D: 60%–69%
>* F: Below 60%