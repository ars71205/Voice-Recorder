# Voice-Recorder

This Python script records audio from your microphone and saves it as a WAV file. Using the PyAudio and Wave libraries, it captures sound input for a fixed duration of 5 seconds. Key parameters include a sample rate of 44.1 kHz, 16-bit depth, and mono channel audio. The recording is processed in chunks to ensure smooth data handling.

To use, simply run the script. It will automatically start recording and save the output as "output.wav" in the same directory. No user input is required during execution. This tool is ideal for quick audio captures, voice notes, or testing microphone functionality.

Ensure you have PyAudio installed (pip install pyaudio). Compatible with Windows, macOS, and Linux, though microphone access must be enabled. The resulting WAV file is standard and can be played by most media players or edited in audio software.
