# Text-to-Audio Converter / Audiobook Creator

## Overview
This project is a web-based application that converts text into audio, primarily focusing on creating audiobooks. It leverages the OpenAI API to transform text into speech and offers users the ability to upload text files, including ePub, or directly input text for conversion. The application is designed to be minimalistic and user-friendly, emphasizing privacy and simplicity.

## Features
- **Text Input:** Users can type or paste text into a text box or upload text and ePub files for conversion.
- **OpenAI API Integration:** Utilizes the OpenAI Text-to-Speech API to generate audio from text.
- **Clienside Only:** You use your own OpenAI key to create the language. I don't have any serverside code running.
- **Audio File Generation:** Converts text segments into audio files and merges them into a single audio file.
- **Progress Tracking:** Includes progress bars to track the status of text-to-speech conversion and file creation.
- **Download Option:** Users can download the generated audiobook in a suitable audio format.
- **Client-Side Processing:** All functionalities, including audio file merging, are handled client-side for enhanced privacy.
- **No Ads or Tracking:** The application is free from advertisements and user tracking, ensuring a focus on functionality and user privacy.

## Technical Details
- **Frontend:** Built using HTML, CSS, and JavaScript.
- **Audio Processing:** Utilizes the Web Audio API for audio decoding and custom JavaScript logic for merging audio files.
- **Responsive Design:** Crafted with a responsive layout for a seamless experience across various devices.
- **No Backend:** Operates entirely on the client side, with no server-side processing.
- **Privacy-Focused:** Does not store user data, ensuring complete privacy.

## Usage
1. **Text Input:** Enter text or upload a file containing the text.
2. **API Key:** Provide your OpenAI API key for text-to-speech conversion.
3. **Generate Audiobook:** Initiate the conversion process and wait for the audio file to be processed.
4. **Download:** Download the final merged audio file.

## License
This project is licensed under the [MIT License](LICENSE).
