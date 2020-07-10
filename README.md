# PDF Reader

A **simple** and **offline** PDF audio reader using Python which extract texts from the PDF using file handling methods and stores them in a string. This string is then passed  on to the TTS (Text-To-Speech) engine to speak the pdf text. This process in brief is converting Text to Speech. The GUI version has been made using tkinter to provide eased accessibility. The CLI version has been made using os and argparse libraries.


## How it works?

The task can be simply divided into 2 steps:

1. Text extraction from PDF. 

2. Conversion of text to speech.


## Dependencies
- PyPDF2: It helps to extract document information, merge multiple pages into a single page, encrypt and decrypt PDF files, and more.
- pyttsx3: A text-to-speech conversion library, which works offline, unlike others.
- tkinter: The standard Python interface to the Tk GUI toolkit.  
- os: Provides a way of using OS dependent functionality and interface.
- argparse: Makes it easy to write user-friendly command-line interfaces.

  
## Future developments to accomplish
- To strengthen the system since occasionally some texts could not be extracted properly.
- Identify the images present in the PDF.
- Building a more friendly GUI and CLI.
