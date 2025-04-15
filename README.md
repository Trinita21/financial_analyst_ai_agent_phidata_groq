Financial Analyst AI Agent with PhiData & Groq
This project leverages the PhiData framework and Groq large language models to create an intelligent financial analyst agent. The agent provides real-time financial data, including stock prices, analyst recommendations, company fundamentals, and the latest news, by integrating tools like YFinance and DuckDuckGo.​

Features
Real-Time Stock Data: Fetch current stock prices, analyst recommendations, and company fundamentals using YFinance.

Latest News Retrieval: Obtain the most recent news articles related to specific stocks via DuckDuckGo search.

Interactive Playground: Utilize the PhiData Playground for an interactive experience with the AI agent.​
GitHub
+5
GitHub
+5
GitHub
+5
GitHub
+2
GitHub
+2
GitHub
+2
GitHub
+1
GitHub
+1

Installation
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/Trinita21/financial_analyst_ai_agent_phidata_groq.git
cd financial_analyst_ai_agent_phidata_groq
Create a Virtual Environment:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Set Up Environment Variables:

Create a .env file in the root directory and add your API keys:

env
Copy
Edit
PHI_API_KEY=your_phidata_api_key
GROQ_API_KEY=your_groq_api_key
Usage
Run the Financial Agent
Execute the financial agent script to start the AI agent:​
GitHub
+4
GitHub
+4
GitHub
+4

bash
Copy
Edit
python run_financial_agent.py
This will initialize the agent, ready to process financial queries.​
GitHub
+5
GitHub
+5
GitHub
+5

Launch the PhiData Playground
For an interactive experience, launch the PhiData Playground:​
GitHub

bash
Copy
Edit
python run_phidata_playground.py
Access the playground at http://localhost:7777 or via the PhiData web interface.​
GitHub

Example Queries
"What is the current stock price of Tesla?"

"Show me the latest news about Nvidia."

"Provide the stock fundamentals for Microsoft."​
GitHub
+1
GitHub
+1

Project Structure
run_financial_agent.py: Initializes and runs the financial AI agent.

run_phidata_playground.py: Launches the PhiData Playground for interactive use.

requirements.txt: Lists all Python dependencies.​
GitHub
+3
GitHub
+3
GitHub
+3
GitHub
+1
GitHub
+1
GitHub
+1
GitHub
+1

Technologies Used
PhiData: Framework for building and deploying AI agents.

Groq: High-performance API endpoints for large language models.

YFinance: Python library for accessing financial data from Yahoo Finance.

DuckDuckGo Search: Tool for retrieving the latest news related to specific stocks.​
