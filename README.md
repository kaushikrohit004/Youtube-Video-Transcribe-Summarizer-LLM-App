# Youtube-Video-Transcribe-Summarizer-LLM-App


App to transcribe and summarize YouTube videos using Llama 2, Whisper, and Streamlit.

Features:

Download and transcribe YouTube videos.

Generate concise video summaries.

User-friendly web interface.

Installation:

Clone the repository:

git clone https://github.com/your-username/youtube-video-summarizer.git
cd youtube-video-summarizer

Install dependencies:

pip install -r requirements.txt

Add the Llama 2 model file: llama-2-7b-32k-instruct.Q4_K_S.gguf.

Usage:

Run the app:

streamlit run app.py

Open in your browser and input a YouTube URL.

File Structure

|-- app.py                # Main application
|-- model_add.py          # LlamaCPP integration
|-- requirements.txt      # Dependencies
|-- README.md             # Documentation

Contributions

Contributions are welcome! Fork, create a branch, and submit a pull request.

License

Licensed under MIT. See LICENSE for details.
