# Transcribing Audio
A python program to transcribe an audio file to text format using the google cloud api.
It uses SpeechRecognition, Google API Client Library for Python and PyDub libraries.

SpeechRecognition is the main library used for it's recognizer method, it interfaces with the google cloud api using an API key file obtained from GoogleCloudConsole.

I'm using PyDub(requires ffmpeg codec) to slice the given audio file into parts, it's a hugely popular and powerful library for manipulation audio files.
