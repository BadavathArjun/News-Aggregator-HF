**📰 News Aggregator using NewsAPI**

## 📌 Project Overview

The **News Aggregator** is a smart AI-powered application that collects, analyzes, and presents news articles from various sources. It leverages **NewsAPI** to fetch real-time news content, providing users with categorized and summarized news updates for a quick and efficient reading experience.

## 🚀 Features

📡 **Fetch News**: Retrieve real-time news articles from multiple sources using NewsAPI.

🔍 **Categorization**: Automatically classifies news into different categories (e.g., politics, sports, technology, etc.).

📌 **Keyword-Based Search**: Allows users to search for news articles based on specific keywords.

🎨 **User-Friendly Interface**: Simple and intuitive UI for easy news browsing.

🏎 **Fast and Efficient**: Fetches and displays news quickly for a smooth user experience.

🛠 **Bookmarking**: Users can save favorite articles for later reading.

## 🛠️ Technologies Used

- **Python**
- **Flask/FastAPI** (Backend)
- **NewsAPI** (for fetching real-time news)
- **HTML, CSS, JavaScript** (Frontend UI)
- **SQLite/MongoDB** (Database for storing saved news)

## 📥 Installation & Setup

### 1️⃣ Clone the Repository

git clone https://github.com/BadavathArjun/News-Aggregator-HF.git
cd News-Aggregator-HF

### 2️⃣ Create a Virtual Environment (Optional)
```sh
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 4️⃣ Set Up NewsAPI Key
1. Sign up at [NewsAPI](https://newsapi.org/)
2. Generate an API key from your account.
3. Create a **.env** file in the project root and add:
```sh
NEWS_API_KEY=your_api_key_here
```

### 5️⃣ Run the Application
```sh
python app.py  # Or uvicorn main:app --reload (if using FastAPI)
```

## 🎯 How to Use

1. Open the application in your browser.
2. Enter a keyword or select a news category.
3. The system fetches articles using NewsAPI and displays them.
4. Click on an article to read more or bookmark it for later.

## 🔗 API Endpoints (If Applicable)

| Method | Endpoint       | Description                         |
|--------|---------------|-------------------------------------|
| GET    | `/news`        | Fetch latest news articles using NewsAPI |
| GET    | `/news?query=keyword` | Search news based on keywords |
| GET    | `/categories`  | Fetch news based on categories    |
| POST   | `/bookmark`    | Save an article to bookmarks      |
| GET    | `/bookmarks`   | Retrieve saved articles           |

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/71eb5ebc-f54b-41b1-9e73-559d7639f554)
![image](https://github.com/user-attachments/assets/a54428f5-f179-4a65-9ada-4f90b2afe1c6)

## 🏗️ Future Improvements

✅ **Implement multilingual news support**
✅ **Enhance news filtering options**
✅ **Implement user authentication and preferences**
✅ **Integrate real-time news notifications**
✅ **Improve UI/UX for better readability**

## 👨‍💻 Contributing

Contributions are welcome! If you want to improve this project:
1. Fork the repository.
2. Create a new branch.
3. Submit a pull request.

## 📜 License

This project is licensed under the **MIT License**.

