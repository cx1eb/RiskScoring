---

# Vulnerability Scoring Tool

A lightweight web-based tool that allows you to score potential risks to a company and determine how soon they should be addressed. It also provides potential solutions and visual insights for decision-making.

---

## 🚀 Features

* Dynamic **scoring system** for vulnerabilities (0–5 scale).
* **Color-coded dropdowns** for easier visualization of severity.
* **Calculation Details** table with sortable columns (ascending/descending).
* **Preset buttons** (High risk / Low risk) that work dynamically with custom categories and suggestion rules.
* **Randomize button** to quickly test charts/graphs and generate example scenarios.
* **Fallback logic** ensures new categories/suggestion rules integrate automatically.

---

## ✅ Progress Tracker

### ✔ Already Implemented

* [x] Added more colors to dropdown menus for each score
* [x] Added Low risk example button and randomize button for charts/graphs
* [x] Removed css comments auto-added by GitHub Copilot complete
* [x] Made High/Low example buttons use fallback preset (not hardcoded)
* [x] Enabled sorting in “Calculation Details” table (asc/desc)
* [x] Fixed table row resizing issue when sorting
* [x] Beautified CSS for cleaner visuals

### ⏳ To Be Added

* [ ] Adjust **overall score calculation** based on category weights.
* [ ] Add more **default suggestion rules** for common scenarios.
* [ ] Documentation for how to **extend categories & rules** easily.
* [ ] Export results as **CSV or JSON** for reporting.
* [ ] UI polish: animations or hover tooltips for clarity.
* [ ] Add **unit tests** for calculation logic.
* [ ] Theme switcher.

---

## 📌 Notes

* The design is **extensible**: new categories and rules can be added by simply updating the configuration tables without editing core logic.
* Built for clarity and usability, prioritizing **fast adjustments** in security risk evaluation.

---
