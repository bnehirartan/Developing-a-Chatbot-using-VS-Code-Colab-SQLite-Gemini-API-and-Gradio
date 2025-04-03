# Developing-a-Chatbot-using-VS-Code-Colab-SQLite-Gemini-API-and-Gradio

This project features a chatbot application that allows a manager to interact with a company’s SQLite database using natural language queries in either **Turkish** or **English**. The chatbot leverages the **Gemini API** to convert natural language inputs into SQL queries, which are then executed on the database. The results are returned as structured **JSON** for better handling and processing.

## Key Features:
- **Natural Language Understanding**: Understands queries in both Turkish and English.
- **SQL Query Generation**: Converts natural language queries into SQL statements using the Gemini API.
- **Database Interaction**: Executes SQL queries on an SQLite database to retrieve the requested information.
- **Structured JSON Output**: Gemini API is configured to return structured JSON responses, enhancing the clarity and usability of query results.
- **Gradio Interface**: A simple and functional chat interface to display chatbot responses interactively.

## Technologies Used:
- **Gemini API**: Used for generating SQL queries from natural language.
- **SQLite**: The database used for storing company data.
- **Gradio**: Provides a user-friendly interface for interacting with the chatbot.
- **Python**: Backend implementation, including handling database interaction and API requests.
- **Exponential Backoff**: Implemented for API request retries in case of rate limits.
