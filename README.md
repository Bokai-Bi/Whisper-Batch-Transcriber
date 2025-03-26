# Whisper Batch Transcriber

A Jupyter Notebook that transcribes videos of arbitrary formats to timestamped transcriptions using OpenAI's Whister-large-v3-turbo. 

To run:
- Clone the repo
- Make sure you're on a modern version of Python3, this repo was developed under 3.12.3 but others should work as long as the relevant packages are supported
- [Make a virtual environment](https://docs.python.org/3/library/venv.html) and attach to it in your notebook interpreter
- [Download an ffmpeg executable](https://ffmpeg.org/download.html) into this repo's directory (same directory as the notebook)
- Put the videos you want to transcribe in ./videos, then run the notebook cells in order and enjoy!
