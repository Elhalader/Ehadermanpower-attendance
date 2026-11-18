# 🚀 QUICK START GUIDE

## Open the Application

### Windows:
1. Double-click `index.html`
2. It will open in your default browser

### OR:
1. Right-click `index.html`
2. Select "Open with" → Chrome/Edge/Firefox

---

## First Time Setup (5 minutes)

### Step 1: Login
```
Username: Admin
Password: admin@Elhader
```

### Step 2: Create Projects
1. Click "📁 Projects" button (top right)
2. Click "➕ Add New Project"
3. Fill in:
   - Project Name: Your Project Name
   - Location: City/Area
   - Status: Active
4. Click "💾 Save Project"
5. Repeat for all your projects

### Step 3: Create Users
1. Click "👥 Users" button (top right)
2. Click "➕ Add New User"
3. Fill in:
   - Username: employee.name (no spaces)
   - Full Name: Employee Full Name
   - Role: Select role (Office Engineer, Project Manager, etc.)
   - Password: Create password (write it down!)
   - Project Access: Select "ALL PROJECTS" or specific projects
4. Click "💾 Save User"
5. Repeat for all your team members

**Recommended Roles:**
- Project Admin (First approver)
- Office Engineer (Second approver)
- Project Engineer (Third approver)
- Project Manager (Fourth approver)
- Project Follow up (Fifth approver)
- Project Coordinator (Sixth approver)
- CDGM (Final approver)

---

## Creating Your First Report

### Step 1: Select Project
1. Click "➕ New Report"
2. Select project from dropdown
3. Click "✓ Confirm & Continue"

### Step 2: Fill Report Info
- Report Date: Today's date (auto-filled)
- Report Number: e.g., RPT-001
- Reporter: Select from dropdown

### Step 3: Add Manpower Data

**Option A: Manual Entry**
1. Click "+ Add Trade"
2. Fill all fields
3. Repeat for each worker

**Option B: Import from Excel** (RECOMMENDED)
1. Prepare Excel file with columns:
   ```
   No | Name | Title | Quantity | Gross Salary | Task | Working Hour | OT1.5 | OT1.75 | OT2.0 | OT2.5
   ```
2. Click "📂 Import from Excel File"
3. Select your Excel file
4. Done! All rows imported

**Option C: Smart Paste** (FASTEST!)
1. Open Excel
2. Select all data rows (without header)
3. Copy (Ctrl+C)
4. Click in the "No" field of first row
5. Paste (Ctrl+V)
6. Click OK in confirmation dialog
7. Done! All rows created automatically

### Step 4: Fill Safety Section
- Lost Time Incidents: 0 (if none)
- Near Misses: Number of near misses
- Safety Observations: Number of observations
- First Aid Cases: Number of first aid cases
- Toolbox Talks: Number of toolbox talks conducted
- Safety Status: Green/Yellow/Red
- Remarks: Any safety notes

### Step 5: Add Notes (Optional)
- Type any additional notes or comments

### Step 6: Save
1. Click "💾 Save Report"
2. Report saved to dashboard!

---

## Approving Reports

### For Approvers:
1. Login with your credentials
2. Go to "📊 Dashboard"
3. See red badge with number of pending approvals
4. Click "✓ Approve" on reports
5. Enter your name
6. Click "✓ Approve"

**Approval Flow:**
```
Draft → Project Admin → Office Engineer → Project Engineer → 
Project Manager → Project Follow up → Project Coordinator → CDGM → ✅ Fully Approved
```

---

## Viewing & Downloading Reports

### View Report:
1. Go to Dashboard
2. Click "👁 View" on any report
3. See all details
4. Print if needed (🖨 Print button)

### Download Report:
1. Report must be fully approved (all 7 approvals)
2. Click "⬇ Download" button
3. HTML file downloads
4. Open in browser or share via email

---

## Dashboard Features

### Filter Reports:
- **Date Filter**: Today, Yesterday, This Week, This Month
- **Project Filter**: Select specific project
- **Search**: Type project name, date, or report number

### View Project Dashboards:
1. Click on a project card
2. Choose dashboard type:
   - 👷 Direct Manpower - See all direct workers
   - 🧑‍💼 Indirect Manpower - See all indirect workers
   - ⛑ Safety - See all safety reports

---

## Tips & Tricks

### Excel Template for Smart Paste:
```
| No | Name       | Title  | Qty | Gross Salary | Task         | Work Hour | OT1.5 | OT1.75 | OT2.0 | OT2.5 |
|----|------------|--------|-----|--------------|--------------|-----------|-------|--------|-------|-------|
| 1  | ABC Co.    | Mason  | 5   | 18000        | Brick laying | 8         | 2     | 0      | 0     | 0     |
| 2  | XYZ Co.    | Laborer| 10  | 15000        | Carrying     | 8         | 3     | 0      | 0     | 0     |
```

### Keyboard Shortcuts:
- **Tab**: Move to next field
- **Ctrl+C**: Copy
- **Ctrl+V**: Paste (triggers smart paste)
- **Ctrl+P**: Print report
- **F5**: Refresh page

### Best Practices:
1. Create report daily (don't wait)
2. Save frequently (auto-saves to browser)
3. Review before submitting for approval
4. Once approved, report is locked
5. Download approved reports for records

---

## Troubleshooting

### Can't login?
- Check username and password (case-sensitive)
- Default: Admin / admin@Elhader
- Clear browser cache and try again

### Data disappeared?
- Data stored in browser localStorage
- Don't clear browser data
- Use same browser each time
- Export reports regularly

### Smart paste not working?
- Make sure you're pasting in the "No" field
- Data must be from Excel (tab-separated)
- Try copying one row first to test

### Calculations wrong?
- Gross Salary ÷ 30 = Hourly Rate (automatic)
- Normal Pay = Quantity × Working Hour × Hourly Rate
- OT Pay = Quantity × OT Hour × Hourly Rate × Multiplier
- Check all numbers entered correctly

---

## Need Help?

1. Check **STATUS-REPORT.md** for complete feature list
2. Check browser Console (F12) for errors
3. Contact system administrator
4. Check all fields are filled correctly

---

**El-Hadar Projects - Daily Progress Report System**  
**Version 1.0 - Complete Edition**  
**All features ready to use!** ✅
