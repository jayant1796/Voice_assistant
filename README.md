# Daya - Desktop Voice Assistant

Daya is a desktop voice assistant created in Python that can perform various tasks, such as telling the time, date, searching Wikipedia, and opening websites. It utilizes speech recognition and text-to-speech capabilities for interaction.

## Features

- Tells the current time and date
- Answers basic questions
- Searches Wikipedia
- Opens websites like YouTube, Instagram, Google, etc.
- Remembers user-provided information
- Takes screenshots

## Prerequisites

Ensure you have the following installed on your system:

- Python 3.x
- pip (Python package installer)

## Installation

Follow these steps to set up the project:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/jayant1796/Voice_assistant.git
   cd Voice_assistant



Then, run the following command to install the dependencies:

       bash
       pip install -r requirements.txt
Configure Microphone Permissions:

Make sure your microphone is set up and that Python has permission to access it.

Run the Application:

You can run the voice assistant using the following command:

           bash
           python Voice_assistant.py
Usage
Upon launching, Daya will greet you based on the time of day and prompt you for commands.
You can ask for the time or date, or request information from Wikipedia.
To remember something, say "remember that," followed by the information you want to store.
To retrieve the information, say "do you remember anything."
To take a screenshot, simply say "screenshot."
To quit the application, say "offline."
Notes
Ensure that your microphone is functioning properly, and you speak clearly for better recognition accuracy.
If you encounter issues with the speech recognition library, try adjusting the microphone settings or using an external microphone.
Acknowledgements
Pyttsx3: Text-to-speech conversion library.
SpeechRecognition: Library for performing speech recognition.
Wikipedia API: Simple Wikipedia API for fetching summaries.
PyAutoGUI: Library for programmatically controlling the mouse and keyboard.
