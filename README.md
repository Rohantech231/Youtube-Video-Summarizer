
# YouTube Transcript to Detailed Notes Converter

This project is a YouTube video transcript summarizer built with Python, Streamlit, Google Gemini API, and YouTube Transcript API. It extracts the transcript from a YouTube video and generates a concise summary of key points in under 250 words using Google Gemini's AI capabilities.

## Features

- Extracts video transcripts from YouTube using the YouTube Transcript API.
- Generates concise summaries of video content using Google Gemini API.
- User-friendly interface built with Streamlit.
- Displays a thumbnail of the YouTube video once the URL is provided.

## Tech Stack

- **Backend**: Python, YouTube Transcript API, Google Gemini API
- **Frontend**: Streamlit
- **Environment Management**: dotenv

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/youtube-transcript-summarizer.git
   ```
2. Navigate to the project directory:
   ```bash
   cd youtube-transcript-summarizer
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up environment variables by creating a `.env` file:
   ```bash
   GOOGLE_API_KEY=<your-google-api-key>
   ```

## Usage

1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
2. Enter a YouTube video URL in the text input field.
3. Click on the **Get Detailed Notes** button to retrieve the transcript and summary.
4. The app will display a summary of the video content in bullet points.

## Project Structure

```bash
.
├── app.py              # Main application file
├── requirements.txt    # List of required packages
├── .env                # Environment variables file
└── README.md           # Project documentation
```

## Dependencies

- Python 3.x
- Streamlit
- YouTube Transcript API
- Google Generative AI API
- dotenv

## License

This project is licensed under the MIT License.

## Acknowledgments

- [Streamlit](https://streamlit.io/)
- [YouTube Transcript API](https://pypi.org/project/youtube-transcript-api/)
- [Google Gemini API](https://developers.google.com/)
