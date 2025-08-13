# Presentation Inconsistency Analyzer 🔎

A Python tool that uses the **Gemini 2.5 Flash API** to scan PowerPoint presentations (`.pptx`) and detect inconsistencies in **text** and **images** across all slides.  
It acts like an **expert business analyst**, reviewing your presentation for contradictory data, conflicting claims, and mismatched timelines.

---

## ✨ Features

- **Holistic Analysis** – Processes the *entire* presentation at once, sending all text and images to Gemini for a comprehensive review.  
- **Discrepancy Detection** – Flags three main types of inconsistencies:  
  1. **Conflicting Numerical Data** (e.g., mismatched revenue figures)  
  2. **Contradictory Textual Claims** (e.g., inconsistent market descriptions)  
  3. **Timeline Mismatches** (e.g., different project dates)  
- **Structured Reporting** – Provides a clear summary with slide numbers and explanations for each issue.  
- **Simple CLI** – Run from the terminal by passing the presentation path.

---

## 🚀 Installation

Install dependencies:

```bash
pip install google-generativeai python-pptx Pillow
```
---

## 🏃 How to Run
After installing the dependencies and setting up your API key, you can run the script from your terminal. Simply provide the path to your PowerPoint file as an argument.

```bash
python analyze_ppt.py path/to/your_presentation.pptx
```
