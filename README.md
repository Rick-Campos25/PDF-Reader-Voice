This Python project is a simple voice assistant that reads aloud the contents of a PDF file. It functions like a basic version of Alexa for documents, using text-to-speech to convert PDF content into spoken words. The program starts reading from page 4 (index 3) until the end of the document.

Language Used:
Python

Libraries Used:
- pyttsx3 (for offline text-to-speech synthesis)
- PyPDF2 (for reading and extracting text from PDF files)

Features:
- Automatically detects the number of pages in a PDF
- Reads content starting from page 4 to the last page
- Converts extracted text to audio using the system's speech engine

Note:
- The PDF file must be named `mislead.pdf` and located in the same directory as the script.
- pyttsx3 works offline and does not require an internet connection.
