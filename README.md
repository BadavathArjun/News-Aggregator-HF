News Aggregator using Hugging Face API

📌 Project Overview

The News Aggregator is a smart AI-powered application that collects, analyzes, and summarizes news articles from various sources. It leverages the Hugging Face API to process and categorize news content, offering users concise and relevant updates. This project aims to save time by presenting key insights instead of lengthy articles.

🚀 Features

📡 Fetch News: Retrieve news articles from multiple sources.

🧠 AI Summarization: Uses NLP models from Hugging Face to summarize articles.

🔍 Categorization: Automatically classifies news into different categories.

📌 Keyword Extraction: Identifies key topics in articles.

🎨 User-Friendly Interface: Simple and intuitive UI for easy news browsing.

🏎 Fast and Efficient: Processes and delivers news summaries quickly.

🛠️ Technologies Used

Python

Flask/FastAPI (Backend)

Hugging Face API (for NLP models)

HTML, CSS, JavaScript (Frontend UI)

News API (optional, for fetching real-time news)

SQLite/MongoDB (Database for storing news)

📥 Installation & Setup

1️⃣ Clone the Repository

 git clone https://github.com/your-badavatharjun/News-Aggregator-HF.git
 cd News-Aggregator-HF

2️⃣ Create a Virtual Environment (Optional)

 python -m venv venv
 source badav/bin/activate  # On Windows use: venv\Scripts\activate

3️⃣ Install Dependencies

 pip install -r requirements.txt

4️⃣ Set Up Hugging Face API Key

Sign up at Hugging Face

Generate an API key from your account.

Create a .env file in the project root and add:

HUGGINGFACE_API_KEY=your_api_key_here

5️⃣ Run the Application

 python app.py  # Or uvicorn main:app --reload (if using FastAPI)

🎯 How to Use

Open the application in your browser.

Enter a keyword or select a news category.

The system fetches articles, summarizes them, and displays key insights.

Click on an article to read more.

🔗 API Endpoints (If Applicable)

![image](https://github.com/user-attachments/assets/8dbf19d7-81ba-47b3-bee0-49a6ced68281)

📸 Screenshots

![image](https://github.com/user-attachments/assets/71eb5ebc-f54b-41b1-9e73-559d7639f554)
![image](https://github.com/user-attachments/assets/a54428f5-f179-4a65-9ada-4f90b2afe1c6)



🏗️ Future Improvements

✅ Add multilingual news support.

✅ Implement user authentication and preferences.

✅ Integrate real-time news notifications.

👨‍💻 Contributing

Contributions are welcome! If you want to improve this project:

Fork the repository.

Create a new branch.

📜 License

This project is licensed under the MIT License.
