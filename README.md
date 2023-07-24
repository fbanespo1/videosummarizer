youtube_summarizer
The codes takes a YouTube video URL as input, loads the associated transcript, splits the transcript into smaller chunks, and then applies a summarization process using the OpenAI API. The summarized output is presented in the web application created with Streamlit.

Please use your own Open AI API key

Installation and run:

1. Clone the repo
2. Use a virtual environment python -m venv video
3. Activate the virtual environment with source video/bin/activate
4. now run pip install -r requiremnts.txt in order to install the libraries
5. Start the server streamlit run video.py  --- remember to add your password
6. If not automatically redirected point your browser to: [
](http://localhost:8501/)http://localhost:8501/

Chose a video from Youtube and copy paste the link press enter and wait for the summary.
