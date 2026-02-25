# SQL Stored Procedure Documentation Tool 🚀

[Castellano / Spanish](https://github.com/Cbas12/store_procedure_documentation_tool/blob/main/README.es.md)

An automated solution designed to extract, analyze, and document SQL Server Stored Procedures using Python and Generative AI.

## 📌 Project Overview
In complex data environments, keeping database documentation up to date is a constant struggle. This tool automates the process by grabbing any kind and number of Stored Procedures file and generating structured documentation.

It is particularly effective for legacy systems, financial consolidation projects, and environments with hundreds of objects that require clear, human-readable logic explanations.

## 🚀 Key Features
- **AI-Powered Analysis:** Leverages Gemini AI to interpret complex SQL logic and explain it in plain language.
- **Structured Output:** Generates clear and simple documentation including input parameters, logic flow, and dependencies.
- **High Scalability:** Designed to batch-process hundreds of files in minutes.
- **Jupyter Integration:** Easy to run, test, and modify via a notebook interface.

## 💰 Cost Efficiency
This tool is designed for high-volume processing at a minimal cost. During development and testing:
- **Scalability:** Successfully documented **500+ Stored Procedures**.
- **Total Cost:** Less than **$3.00 USD** (using Gemini API).
- **Value:** High-speed documentation at a fraction of the cost of manual labor or enterprise tools.

## 🛠️ Tech Stack
- **Language:** Python
- **AI Orchestration:** Google Gemini API
- **Data Handling:** Pandas

## 📋 Prerequisites
Before running the notebook, ensure you have:
- Python 3.10+
- A Google AI (Gemini) API Key.

## ⚙️ Configuration
1. **Clone the repository:**
    git clone https://github.com/Cbas12/store_procedure_documentation_tool.git

2. **Setup Credentials:**
    - Use the file gemini.txt to write down your own Gemini API Key. Simply copy the text inside.

## 📖 Usage
1. Open *store_procedure_documentation_tool.ipynb* in VS Code or Jupyter.
2. Ensure you added the input and output paths:
    - *sp_location:* The folder path containing your Store Procedure files in .sql
    - *docutentation_output_location:* The folder where you want the documentation files to be saved.
3. Before running all cells, it is suggested that you check the last section of the python file *"CHECK FOR ERRORS IN THE STORE PROCEDURE FILES"* to ensure no file has errors that might prevent the docuementation.
4. It's also suggested that, in the beginning of the section *"PROCESS THE FILES"* you reduce the number of files processeced at first, just to ensure everything goes accordingly to your expectations.
4. Run all cells. The tool will process each file and generate a detailed natural language explanation for each Stored Procedure.

## 📄 License
This project is open-source. Feel free to clone, download, and adapt it to your own data workflows.