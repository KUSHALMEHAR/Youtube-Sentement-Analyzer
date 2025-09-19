🎬 YouTube Sentiment Analysis Web App

This is a Flask-based web application that retrieves and analyzes YouTube video comments using sentiment analysis.
It classifies comments into positive 😀, neutral 😐, or negative 😡 sentiments and displays the results with a pie chart 📊.

✨ Features

🔍 Fetches comments from YouTube videos using the YouTube Data API

🤖 Performs sentiment analysis with VADER (NLTK)

📊 Generates a pie chart showing sentiment distribution

🏠 Includes separate pages: Home, About, and Input

🌐 Built with Flask for a simple web interface

🛠️ Tech Stack

Languages: Python 🐍, HTML, CSS

Frameworks/Libraries: Flask, VADER (NLTK), Matplotlib/Seaborn

APIs/Tools: YouTube Data API

🚀 How It Works

🎥 User enters a YouTube video ID and number of comments.

📥 The app fetches comments using YouTube Data API.

🤖 Each comment is analyzed using VADER Sentiment Analyzer.

📊 Results are displayed in a table + visualized with a pie chart.

📷 Screenshot (Example)

(Add your project screenshot here!)

⚡ Installation & Usage
# Clone the repository  
git clone https://github.com/your-username/youtube-sentiment-analysis.git  

# Navigate into project directory  
cd youtube-sentiment-analysis  

# Install dependencies  
pip install -r requirements.txt  

# Run the app  
python app.py  


Then open 👉 http://127.0.0.1:5000/ in your browser 🌍

📌 Example Use Case

🎯 Understand audience reactions to YouTube videos

📈 Track sentiment trends for creators or brands

🛠️ Learn how to integrate Flask + APIs + NLP in one project

🤝 Contributing

Pull requests are welcome! 🙌 For major changes, please open an issue first to discuss what you’d like to change.

📜 License

This project is licensed under the MIT License 📝
