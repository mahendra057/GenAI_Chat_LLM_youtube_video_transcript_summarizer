# Youtube_video_Transcript_to_to-Detailed-Notes-Converter

# YouTube Transcript to Detailed Notes Converter

The **YouTube Transcript to Detailed Notes Converter** is a user-friendly Streamlit application designed to simplify the process of reviewing YouTube video content. Users can input a YouTube video link, extract its transcript (in English or Hindi), and generate a detailed summary using the **Google Gemini API**.

---

## 🚀 Features

### 1. **Transcript Extraction**
- Leverages `youtube-transcript-api` to fetch the transcript of a YouTube video.
- **Primary Language Support**: Prioritizes English transcripts; defaults to Hindi if English is unavailable.
- Provides the complete transcript text or an error message if extraction fails.

### 2. **Content Summarization**
- Summarizes the extracted transcript using **Google Gemini’s generative AI model**.
- Generates a concise **250-word summary**, capturing the core ideas of the video.

### 3. **Streamlit Interface**
- Simple and intuitive UI:
  - Accepts a YouTube video link from the user.
  - Displays the video thumbnail for visual confirmation.
  - Includes a "Get Detailed Notes" button to initiate the process.
- Presents the summarized notes upon successful completion.

---

## 🛠️ Core Components

1. **Transcript Extraction**
   - Extracts video transcripts using `youtube-transcript-api`.
   - Automatically falls back to Hindi if English is unavailable.
   - Ensures accurate and complete retrieval of transcript text.

2. **Content Summarization**
   - Uses the **Google Gemini API** with a predefined prompt for summarization.
   - Delivers a compact and detailed set of notes for easy review.

3. **Streamlit Application**
   - Interactive interface with a focus on usability and clarity.
   - Seamlessly integrates transcript extraction and summarization processes.

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mahendra057/GenAI_Chat_LLM_youtube_video_transcript_summarizer.git
   cd GenAI_Chat_LLM_youtube_video_transcript_summarizer

2. pip install -r requirements.txt
3. streamlit run app.py
