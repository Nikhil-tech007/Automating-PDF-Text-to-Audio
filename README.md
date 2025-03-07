# Automating-PDF-Text-to-Audio

This Python script converts the text content of a PDF file into an audible MP3 file using the pyttsx3 (text-to-speech) and PyPDF2 (PDF reading) libraries.

## Project Overview
This project provides a simple and efficient way to convert PDF documents into audio files, making the content accessible for listening.

## Prerequisites
Before running the script, ensure you have the following installed:

- Python 3
- pyttsx3: pip install pyttsx3
- PyPDF2: pip install PyPDF2
  
## How to Use
- Clone the Repository
- Place Your PDF: Put the PDF file you want to convert in the same directory as the Python script.
  
## Run the Script:
- Open cmd.
- Navigate to the directory containing the script.
- Run the script using Python
  
## Audio Output:

The script will create an audio.mp3 file in the same directory.
If the PDF doesn't contain any text, it will print "Text not found in the PDF."

## Customization
Adjust Speech Rate/Volume: You can modify the speech rate and volume using speaker.setProperty('rate', value), speaker.setProperty('volume', value).
