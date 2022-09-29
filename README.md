# Whisper with Silero VAD
This notebook combines Whisper with a separate VAD. This improves long-form transcriptions, at the cost of possibly missing a few lines. 
It also attempts to filter out hallucinations and obvious mistranslations.
## How to use
* [Click here](https://colab.research.google.com/github/ANonEntity/WhisperWithVAD/blob/main/WhisperWithVAD.ipynb) to open the notebook in Google Colab.
* Upload your input audio to either the runtime itself, Google Drive, or a file hosting service with direct download links.
* Set the audio_path and language variables. Run the Setup Whisper cell, and then the Run Whisper cell.
* Once it's done, click on Files in the sidebar, and download the generated SRT file.
