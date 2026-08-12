INSIGHT FLOW AI

Project Details:

*Project Name: InsightFlow AI
*Domain: Artificial Intelligence, Data Analytics & Database Management

InsightFlow AI is a conversational data-analysis platform that allows users to interact with databases using natural-language questions. Instead of writing SQL queries manually, users can ask questions such as “Show the top 5 products by revenue” or “Show monthly revenue trends.” The system analyzes the request, retrieves relevant data, generates suitable visualizations, and provides a simple explanation of the results. It also provides SQL transparency so users can understand how the answer was obtained.

Key Features:

    *Natural-language database interaction

    *Database schema discovery

    *Automated SQL query generation/execution

    *Interactive bar, line, and pie charts

    *Conversational data explanations

    *SQL query transparency

    *E-commerce SQLite database

    *Chat-based user interface

    *Future “Ask WHY” root-cause analysis

    *Planned ER diagrams and process flowcharts



---

*Setup Instructions:

1. Download/Clone the Repository

Open the GitHub repository and download the project, or clone it using:

git clone https://github.com/sec25it098-debug/Insight-flow-AI.git
cd Insight-flow-AI

2. Install Python

Make sure Python 3.x is installed on your computer.

Check using:

python --version

3. Install Required Libraries

Run:

pip install -r requirements.txt

4. Create the Database

Run:

python database/seed_db.py

This creates the demo SQLite e-commerce database.

5. Start the Application

Run:

streamlit run app.py

6. Open the Application

Streamlit will provide a local address, usually:

http://localhost:8501

Open this address in your browser.

7. Try Example Questions

You can ask:

Show the top 5 products by revenue

Show revenue by category

Show monthly revenue trend

Show customers with the most orders

The application will return the relevant data, visualization, explanation, and SQL query.

System Flow

User Question → AI Agent → Database Schema → SQL Query → Query Result → Visualization → Insight/Explanation

This setup is based on the project source code and documentation prepared for your InsightFlow AI MVP.



*Team Information:

Team Lead : D.RITHI JAYASRI

    Sec Id: SEC25IT098

Team Member 1:S.MEHA

    Sec Id: SEC25IT101

Team Member 2:R.RITHIKA

    Sec Id: SEC25IT395
