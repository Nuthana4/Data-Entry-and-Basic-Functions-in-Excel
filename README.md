**Data Entry and Basic Functions in Excel (Student Marks)**

**🔹 Step 1: Create Column Headers**

In Row 1, enter the following column headers:

S.No.

Name

Tel

Hin

Eng

Mat

Sci

Soc

These represent:

S.No.: Serial number of the student

Name: Student’s name

Tel to Soc: Marks in subjects (Telugu, Hindi, English, Maths, Science, Social)


**🔹 Step 2: Enter Student Data**

Starting from Row 2, enter student records.

Each row contains one student’s information.

Columns C to H will contain numerical marks.


**🔹 Step 3: Add Computed Columns (Optional but useful)**


You can add two new columns:

Total: Sum of all subject marks

Average: Average of all subject marks

Add these headers in the next columns (e.g., I1: Total, J1: Average)


**🔹 Step 4: Apply Excel Functions**


Assume subject marks are in C2 to H2 for a student in row 2. Adjust ranges as needed.

✅ Total Marks (per student)
=SUM(C2:H2)

✅ Average Marks (per student)
=AVERAGE(C2:H2)

✅ Total Marks (per subject)

For Telugu, assuming data in C2 to C6:

=SUM(C2:C6)


**Repeat for other subjects (columns D to H).**

✅ Average Marks (per subject)
=AVERAGE(C2:C6)

✅ Minimum Marks (per subject)
=MIN(C2:C6)

✅ Maximum Marks (per subject)
=MAX(C2:C6)


**🔹 Step 5: Use AutoFill**


After entering formulas in one cell, drag the fill handle down or across to apply them to other rows/columns.


**🔹 Step 6: Format for Clarity (Optional)**


Bold headers

Use borders for cells

Use number formatting for scores (if needed)

Apply Conditional Formatting to highlight top or low scores
