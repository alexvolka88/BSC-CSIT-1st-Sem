### **Steps to Calculate Total Marks and Percentage in Excel**

- Open **Microsoft Excel**.
- Enter your data in a table format with columns like **Student**, **Subject 1**, **Subject 2**, **Subject 3**, **Subject 4**, **Subject 5**.
- Click on the first empty cell in a new column (e.g., **G2**) and type:
    
    =SUM(B2:F2)
    
    This calculates the **total marks** for the first student.
    
- Press **Enter**.
- Click the **fill handle** (small square at the bottom-right of the cell) and drag it down to calculate total marks for all 5 students.
- Click on the next empty column (e.g., **H2**) to calculate the **percentage** for the first student.
- Type:
    
    =G2/(500)
    
    _(Here 5 = number of subjects, 100 = maximum marks per subject)_
    
- Press **Enter**.
- Drag the **fill handle** down to calculate percentage for all students.
- Format the **Percentage column**(if required):
    - Select the percentage cells → Right-click → **Format Cells** → **Percentage** → Click **OK**.
- To make the table neat, select the whole table, go to the **Home** tab, and click **Borders → All Borders**.