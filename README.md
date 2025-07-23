
# 📘 YouTube Transcript to Detailed Notes Converter

This is a simple Streamlit web application that takes a **YouTube video URL**, extracts the **video transcript**, and generates a **detailed summary in bullet points** using **Google Gemini Pro (Generative AI)**.

---

## 🚀 Features

- 🔗 Paste any YouTube video link
- 📝 Automatically fetches transcript using `youtube-transcript-api`
- 🤖 Summarizes the transcript using Google Gemini Pro
- 📌 Provides structured, point-wise summary within 250 words
- 🖼️ Displays the video thumbnail for reference

---

## 📦 Tech Stack

- **Frontend:** Streamlit
- **Backend:** Python
- **AI Model:** Google Gemini Pro (`google-generativeai`)
- **Transcript Extraction:** `youtube-transcript-api`
- **Environment Management:** `python-dotenv`

---

## 🛠️ Setup Instructions

### 1. **Clone the repository**
```bash
git clone https://github.com/your-username/yt-transcript-notes-app.git
cd yt-transcript-notes-app
````

### 2. **Create and activate a virtual environment (optional)**

```bash
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows
```

### 3. **Install the dependencies**

```bash
pip install -r requirements.txt
```

### 4. **Create a `.env` file**

In the root directory, create a file named `.env` and add your **Google API Key**:

```
GOOGLE_API_KEY=your_google_gemini_api_key_here
```

### 5. **Run the Streamlit app**

```bash
streamlit run app.py
```

---

## ✅ Example Output

* Paste a YouTube video link (e.g., an educational tutorial)
* Click **"Get Detailed Notes"**
* The app fetches the transcript and generates a clean summary like:

```text
• Topic Introduction
• Key concepts explained clearly
• Real-world examples provided
• Summary and conclusion
```

---

## 🧠 Use Cases

* Quick revision from long educational videos
* Lecture note generation
* Research assistance
* Productivity tool for content creators and students

---




