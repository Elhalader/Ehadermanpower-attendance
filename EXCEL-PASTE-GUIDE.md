# 📋 Smart Paste from Excel - Complete Guide

## How It Works

1. **Prepare your data in Excel** with the correct column order
2. **Select all rows** you want to paste (without header)
3. **Copy** (Ctrl+C)
4. **Click on the "No." field** in the DPR form (first row)
5. **Paste** (Ctrl+V)
6. **Confirm** the dialog
7. **Done!** All fields automatically filled

---

## 📊 Excel Column Format

### Your Excel Must Have These Columns (in this order):

| Column | Field Name | Type | Example |
|--------|------------|------|---------|
| **A** | No. | Number | 1 |
| **B** | Name | Text | ABC Construction |
| **C** | Title | Text | Mason |
| **D** | Gross Salary | Number | 18000 |
| **E** | Working Days | Number | 5 |
| **F** | Normal OT {1.5} | Number | 2 |
| **G** | Night OT {1.75} | Number | 0 |
| **H** | Sunday {2.00} | Number | 0 |
| **I** | Holiday {2.5} | Number | 0 |
| **J** | Performed Task | Text | Brick laying *(optional)* |

---

## 📝 Excel Template

Copy this into Excel:

```
No.	Name	Title	Gross Salary	Working Days	Normal OT {1.5}	Night OT {1.75}	Sunday {2.00}	Holiday {2.5}	Performed Task
1	ABC Construction	Mason	18000	5	2	0	0	0	Brick laying
2	XYZ Contractors	Carpenter	20000	6	3	1	0	0	Wood work
3	DEF Company	Electrician	22000	4	0	2	0	0	Wiring
4	GHI Ltd	Plumber	19000	5	1	0	1	0	Pipe installation
5	JKL Corp	Laborer	15000	10	4	0	0	0	General work
```

---

## 🎯 Step-by-Step Instructions

### Step 1: Prepare Excel Data

1. Open Excel
2. Create columns A through I (or J if including Performed Task)
3. Fill your data:
   - **Column A (No.)**: Sequential numbers (1, 2, 3, ...)
   - **Column B (Name)**: Company or contractor name
   - **Column C (Title)**: Job title (Mason, Carpenter, etc.)
   - **Column D (Gross Salary)**: Monthly salary in ETB
   - **Column E (Working Days)**: Number of days worked
   - **Column F-I**: OT hours for each multiplier (0 if none)
   - **Column J**: Task description (optional)

### Step 2: Copy from Excel

1. Select all data rows (WITHOUT the header row)
2. For example: Select from A2 to I6 (or J6 if you have Performed Task)
3. Press **Ctrl+C** to copy

### Step 3: Paste in DPR Form

1. Go to your DPR form in the browser
2. Click **"➕ New Report"**
3. Select your project
4. Click **"+ Add Trade"** (or "+ Add Role" for Indirect)
5. Click in the **"No." field** (first cell in the table)
6. Press **Ctrl+V** to paste

### Step 4: Confirm

1. A dialog will appear: "You're about to paste 5 rows..."
2. Click **OK**
3. Done! All rows created with all fields filled!

---

## ✅ What Gets Auto-Filled

When you paste, these fields are automatically filled:

### In the Table:
- ✓ No.
- ✓ Name
- ✓ Title
- ✓ Gross Salary
- ✓ Working Days
- ✓ Normal OT {1.5}
- ✓ Night OT {1.75}
- ✓ Sunday {2.00}
- ✓ Holiday {2.5}

### Below the Table (Auto-Calculated):
- ✓ Hourly Rate (Gross Salary ÷ 30)
- ✓ Normal Pay (Working Days × 8 × Rate)
- ✓ OT Pay (All OT calculations)
- ✓ Total Pay (Normal + OT)
- ✓ Performed Task (if you included Column J)

---

## 💡 Tips & Tricks

### Tip 1: Without Header
**Do NOT include the header row** when copying from Excel. Only copy the data rows.

❌ **Wrong:**
```
No.	Name	Title	Gross Salary	Working Days...
1	ABC	Mason	18000	5...
2	XYZ	Carpenter	20000	6...
```

✅ **Right:**
```
1	ABC	Mason	18000	5...
2	XYZ	Carpenter	20000	6...
```

### Tip 2: Empty OT Columns
If you have no OT, put **0** (zero) in OT columns, don't leave them empty:

✅ **Right:** `1  ABC  Mason  18000  5  0  0  0  0`
❌ **Wrong:** `1  ABC  Mason  18000  5`

### Tip 3: Decimal Numbers
For OT hours, you can use decimals:
- `2.5` = 2 hours 30 minutes
- `1.5` = 1 hour 30 minutes
- `0.5` = 30 minutes

### Tip 4: Test with One Row First
Before pasting 50 rows, test with just 1-2 rows to make sure your format is correct.

### Tip 5: Performed Task is Optional
If you don't have Column J (Performed Task) in Excel, that's OK! You can:
- Leave it blank (will be empty in form)
- Fill it manually later in the form

---

## 🚨 Common Mistakes

### Mistake 1: Wrong Column Order
❌ If your Excel has: `No. | Title | Name | Gross Salary...`  
✅ It MUST be: `No. | Name | Title | Gross Salary...`

### Mistake 2: Including Header Row
❌ Don't copy the header row with column names  
✅ Only copy data rows (A2:I6, not A1:I6)

### Mistake 3: Empty OT Columns
❌ `1  ABC  Mason  18000  5` (only 5 columns)  
✅ `1  ABC  Mason  18000  5  0  0  0  0` (9 columns)

### Mistake 4: Using Comma Instead of Tab
Excel uses TAB to separate columns. If you copy from Excel, tabs are automatic. If you type manually, make sure to use TAB between columns, not comma or space.

---

## 📖 Example: Complete Workflow

### Your Excel Data:
```
1	ABC Construction Co.	Mason	18000	5	2	0	0	0	Brick laying foundation
2	XYZ Contractors	Carpenter	20000	6	3	1	0	0	Framework installation
3	DEF Company Ltd	Electrician	22000	4	0	2	0	0	Main panel wiring
```

### What You Do:
1. Select rows 1-3 (all columns A through J)
2. Ctrl+C
3. Go to DPR form
4. Click in "No." field
5. Ctrl+V
6. Click OK

### What You Get:
✅ 3 rows created automatically  
✅ All 9 fields filled in each row  
✅ Hourly rates calculated (18000÷30=600, 20000÷30=666.67, 22000÷30=733.33)  
✅ All OT fields filled (2, 0, 0, 0) for row 1, etc.  
✅ All pay calculations done automatically  
✅ Performed Task filled with your descriptions  

---

## 🎯 Quick Reference Card

```
EXCEL COLUMNS (9 required, 1 optional):
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
 A: No.                    (1, 2, 3, ...)
 B: Name                   (Company name)
 C: Title                  (Mason, Carpenter, ...)
 D: Gross Salary           (18000, 20000, ...)
 E: Working Days           (5, 6, 4, ...)
 F: Normal OT {1.5}        (2, 3, 0, ...)
 G: Night OT {1.75}        (0, 1, 2, ...)
 H: Sunday {2.00}          (0, 0, 1, ...)
 I: Holiday {2.5}          (0, 0, 0, ...)
 J: Performed Task         (Optional text)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

STEPS:
1. Prepare Excel with columns A-I (or A-J)
2. Select data rows (NO header)
3. Copy (Ctrl+C)
4. Click "No." field in DPR form
5. Paste (Ctrl+V)
6. Click OK
7. Done!
```

---

## 💾 Download Excel Template

Create a file called **DPR-Template.xlsx** with this structure:

### Sheet 1: Direct Manpower
| A | B | C | D | E | F | G | H | I | J |
|---|---|---|---|---|---|---|---|---|---|
| **No.** | **Name** | **Title** | **Gross Salary** | **Working Days** | **Normal OT {1.5}** | **Night OT {1.75}** | **Sunday {2.00}** | **Holiday {2.5}** | **Performed Task** |
| 1 | | | | | 0 | 0 | 0 | 0 | |
| 2 | | | | | 0 | 0 | 0 | 0 | |
| 3 | | | | | 0 | 0 | 0 | 0 | |

Fill the template and paste into DPR!

---

**Remember:** Column order MUST match exactly for smart paste to work!

**Questions?** Check the STATUS-REPORT.md or QUICK-START.md files.
