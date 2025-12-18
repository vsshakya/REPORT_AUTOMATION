# REPORT_AUTOMATION
# REPORT AUTOMATION – USER GUIDE

## Purpose
This tool generates billing metrics (DOS, Billing, Adjudication, Status)
using a standardized and validated logic.

---

## Folder Structure
- logic/ → core business logic (DO NOT EDIT)
- runner/ → notebook to run reports
- data/ → place Excel files here

---

## How to Run
1. Open Jupyter Notebook
2. Go to `runner/`
3. Open `run_report.ipynb`
4. Edit ONLY the CONFIG cell:
   - REPORT_TYPE
   - FILE_NAME
   - START_DATE / END_DATE
5. Run: Kernel → Restart & Run All

---

## Rules
❌ Do NOT edit files in `logic/`
❌ Do NOT change logic cells
✅ Only change CONFIG values

---

## Output
Notebook prints:
- DOS count
- Billed count
- Adjudicated count
- Pending billing status breakup

---

## Support
If numbers mismatch dashboards:
- Verify column names
- Validate sample rows
- Contact analytics owner

