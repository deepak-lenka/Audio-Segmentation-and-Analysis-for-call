# Audio-Segmentation-and-Analysis-for-call

# Audio Transcription with Whisper ASR

This code demonstrates how to transcribe audio segments using the OpenAI Whisper ASR model. It covers the following steps:

1. **Audio Download**:
   - The code starts by downloading an audio file from Google Drive using its file ID.

2. **Audio Playback**:
   - The downloaded audio file is played using IPython to verify its content.

3. **Audio Splitting**:
   - The audio is split into two segments: caller and callee, each containing one half of the conversation.

4. **Whisper ASR Model**:
   - The Whisper ASR model is loaded, and audio segments are transcribed using the model.

5. **VTT File Generation**:
   - The transcriptions are saved in WebVTT (VTT) format, suitable for captioning and subtitles.

6. **Conversation Data Storage**:
   - Transcriptions and audio segments' paths are stored in a JSON file for further analysis or use.

## Prerequisites

Before running this code, make sure you have the necessary packages installed:
- pydub
- requests
- openai
- whisper

You can install these packages using pip:
```bash
pip install pydub requests openai whisper
