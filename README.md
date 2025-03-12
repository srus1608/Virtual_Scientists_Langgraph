### Virtual Scientists - Generative AI Research Assistant
Virtual Scientists is a Generative AI-based multi-agent system designed to generate professional abstracts on any given research topic. It simulates collaborative 'scientists' (AI agents) to generate diverse perspectives and synthesize them into a final abstract.

## Features
- Auto-generation of abstracts from any topic.
- Multi-agent system (S1, S2, S3) with defined personas.
- Uses tools like DuckDuckGo, Tavily for web data gathering.
- Final abstract generated using LLaMA3 (Groq API).
- Data stored in PostgreSQL.
- Flask-based user interface with LangGraph workflow.
## ## ⚙️ Technologies Used

- **Python 3**
- **Flask** - Web framework
- **LangGraph** - Workflow orchestration
- **Groq API (LLaMA3-8B)** - LLM backend
- **PostgreSQL** - Database for storage
- **DuckDuckGo API** - Optional web search agent
- **dotenv** - For secure environment variable management.
  
## Setup Instructions
1. Clone repository and navigate to project directory.
2. Install dependencies using: pip install -r requirements.txt
3. Configure .env file with Groq API key and DB credentials.
4. Run Flask app: python app.py or CLI version: python main.py
      
## 🚨 Note:
Ensure PostgreSQL is running.
Create .env file 

## 📝 Sample Output:
Enter the topic: Artificial Intelligence in Healthcare
Generating abstract...
Final Abstract:
(Generated abstract content here)


## Future Improvements
- Integration of ReAct prompting for dynamic agent reasoning.
- Improved API handling and distributed agent processing.
  
## 🙋‍♂️ Author
Developed by: Srushti Talwekar
Contact: srushtirt1608@gmail.com

⭐ If you like this project, give it a star!
