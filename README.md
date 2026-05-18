# automation-portfolio
Automation projects built with Make and n8n — workflows for AI and business process automation.
# Automation Portfolio
[scenario](screenshot.png)
No-code automation projects built with Make and n8n.

## Project 1 — Daily Currency Rates Tracker

**Problem:** Checking currency exchange rates manually every day is 
tedious and easy to forget.

**Solution:** A Make scenario that runs on a daily schedule, sends an 
HTTP request to a free currency exchange API, and appends the rates 
as a new row in Google Sheets.

**Result:** The spreadsheet updates automatically every day with no 
manual work.

**Tools & skills:** Make, HTTP module, Google Sheets, JSON parsing, 
data mapping, scheduled triggers.

### Files
- `currency-rates-make.json` — exportable Make blueprint
