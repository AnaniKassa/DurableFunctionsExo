# About me 
### Full name: Anani Thierry Kassa
### Student ID: 041140713

### 1- Function Code

There are two functions used in the `function_app.py`

### 2- Requirements
The `requirements.txt` have the database SDK dependencies

### 3- Database Documentation
`DATABASE_CHOICE.md` explain the database selection and justification.

### 4- Demo Video link: 
https://youtu.be/E6JOcNYaMhc

### 5- How to run the project locally:

### A- Required Software

| Tool                          | Description                           | Installation Link                                        |
| ----------------------------- | ------------------------------------- | -------------------------------------------------------- |
| **Azure Account**             | An active Azure subscription          | [Create free account](https://azure.microsoft.com/free/) |
| **Visual Studio Code**        | Code editor                           | [Download VS Code](https://code.visualstudio.com/)       |
| **Azure Functions Extension** | VS Code extension for Azure Functions | Install from VS Code Extensions                          |
| **Python 3.12**               | Programming language runtime          | [Install Python](https://www.python.org/downloads/)      |
| **Python Extension**          | VS Code extension for Python          | Install from VS Code Extensions                          |

### B- Clone the repository
### C- Deploy the azure function file `function_app.py` using VSCode
### D- Crete the following environement variablesin the file `local.settings.json`

    "COSMOS_DB_ENDPOINT": "<yourazure-db-endpoint>",
    "COSMOS_DB_KEY": "<yourazure-db-key>",
    "COSMOS_DB_DATABASE": "<yourazure-db-name>",
    "COSMOS_DB_CONTAINER": "<yourazure-db-container>"
### E- Test the first function using this http trigger in your browser
http://localhost:7071/api/TextAnalyzer?text=Cloud computing is amazing. It scales automatically.

### F- Test the second function using this http trigger in your browser
http://localhost:7071/api/GetAnalysisHistory
http://localhost:7071/api/GetAnalysisHistory?limit=5

