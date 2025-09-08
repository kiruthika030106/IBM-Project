# IBM-Project
SmartSDLC
SmartSDLC is an AI-powered software development assistant designed to streamline the Software Development Life Cycle (SDLC).
It provides automated requirements analysis and code generation through a user-friendly interface.

🚀 Key Features
Requirements Analysis
Extracts requirements from uploaded PDF documents or user-provided text.
Categorizes requirements into:
         Functional Requirements
         Non-Functional Requirements
Technical Specifications
Automated Code Generation
Generates code snippets based on natural language requirements.
Supports multiple programming languages including Python, Java, JavaScript, C++, C#, PHP, Go, and Rust.

Interactive User Interface
Built with Gradio
, offering a clean and intuitive web-based interface.

🛠 Technology Stack
Model: ibm-granite/granite-3.2-2b-instruct

Libraries:
Transformers
PyTorch
Gradio
PyPDF2

⚙️ Installation
Clone this repository:
git clone https://github.com/yourusername/smartsdlc.git
cd smartsdlc

Install dependencies:
pip install -r requirements.txt
or manually:
pip install transformers torch gradio PyPDF2

▶️ Usage
Run the application with:
python smartsdlc.py

A local Gradio interface will open in your browser.
If share=True is enabled, a public link will also be generated for external access.

📌 Typical Workflow
Upload a requirements document (PDF) or enter requirements in the text box.
Click Analyze to receive structured requirements analysis.
Provide a requirement statement and select a programming language.
Click Generate Code to obtain AI-generated code snippets.
📂 Project Structure
smartsdlc.py        # Main application
README.md           # Documentation

Future Enhancements
Support for exporting results (Word, PDF, JSON).
Extended programming language coverage.
Advanced fine-tuning for domain-specific SDLC tasks.
Integration with project management tools.
