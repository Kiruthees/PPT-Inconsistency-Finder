**Presentation Inconsistency Analyzer 🔎**
A Python script that uses the Gemini 2.5 Flash API to analyze a PowerPoint presentation (.pptx) and identify inconsistencies in text and images across all slides. This tool acts as an expert business analyst, reviewing your presentation for contradictory data, conflicting claims, and timeline mismatches.

**✨ Features**
Holistic Analysis: Processes an entire PowerPoint presentation at once, sending all text and images to the Gemini API for a comprehensive review.

Identifies Discrepancies: Specifically looks for three types of inconsistencies:

Conflicting Numerical Data (e.g., mismatched revenue figures).

Contradictory Textual Claims (e.g., conflicting market descriptions).

Timeline Mismatches (e.g., inconsistent project dates).

Structured Reporting: Provides a clear, easy-to-read summary of findings, including the slide numbers involved and an explanation of each issue.

Simple Command-Line Interface: Easy to use by simply passing the file path to your presentation.

**🚀 Installation**
Before running the script, you need to install the required Python libraries. You can do this by running the following command in your terminal:

pip install google-generativeai python-pptx Pillow

**⚙️ Setup**
Get an API Key: You'll need an API key for the Google Gemini API. You can obtain one from the Google AI Studio.

Set the API Key: Open the analyze_ppt.py file and replace 'YOUR-API-KEY' with your actual API key.

API_KEY = 'YOUR-API-KEY'
Alternatively, for better security, you can set the API key as an environment variable and retrieve it in your script.

**🏃 How to Run**
After installing the dependencies and setting up your API key, you can run the script from your terminal. Simply provide the path to your PowerPoint file as an argument.

python analyze_ppt.py path/to/your_presentation.pptx
