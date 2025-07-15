🎬 Tamil Movie Recommender Based on Emotion
This Python script helps you get top Tamil movies from IMDb based on a user's current emotion — like Drama, Comedy, Action, Horror, or Crime vibes. It's your mood-based movie genie 🧞‍♂️!

📌 Features
🔍 Scrapes IMDb using requests + BeautifulSoup

🎭 Maps user-selected emotions to IMDb genres

🌐 Uses real-time IMDb data (no outdated junk!)

🧠 Super lightweight and beginner-friendly

⚙️ Command-line interface (CLI)

💻 Demo
bash
Copy
Edit
$ python script.py
Enter the emotion First Letter Cap: Comedy

The Boss Baby
Doctor Strange
Kaathuvaakula Rendu Kaadhal
...
🧠 Supported Emotions
Emotion	IMDb Genre
Drama	drama
Action	action
Comedy	comedy
Horror	horror
Crime	crime

✅ Make sure to enter the first letter capitalized (e.g., Drama, not drama).

🛠️ How It Works
Takes the user's emotion as input.

Maps it to a Tamil-language IMDb genre URL.

Makes an HTTP request to IMDb with browser headers.

Scrapes the movie titles using BeautifulSoup and a regex pattern.

Returns top results (max of 14 movies).

🔧 Tech Stack
Python 3.7+

requests

beautifulsoup4

lxml

re

Install dependencies via pip:

bash
Copy
Edit
pip install requests beautifulsoup4 lxml
📁 File Structure
Copy
Edit
📦 imdb-emotion-recommender
├── script.py
└── README.md
🧪 Example Usage
python
Copy
Edit
emotion = "Drama"
movies = main(emotion)
print(movies[:5])
⚠️ Limitations
IMDb might change its HTML structure anytime, which could break the scraper.

No pagination handling yet (just grabs the first page).

Needs stable internet connection.

🚀 Future Upgrades (Ideas)
Add more emotion categories (e.g., Romance, Sci-fi, Thriller)

Build a web UI using Flask or Streamlit

Use IMDb API instead of scraping (more stable)

Add sentiment analysis for user-written text to auto-detect emotion 🤯

🤝 Contributions
PRs are welcome! Open issues, suggest features, or just vibe with the code.

📄 License
MIT License — do whatever you want, just don't sue me 😎

🌟 Show Some Love
If you liked this, drop a ⭐️ on the repo and share it with your movie buff friends!

