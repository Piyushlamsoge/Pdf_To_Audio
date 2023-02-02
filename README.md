# PDF TO AUDIO APP

This is a Streamlit app that allows users to upload a PDF file, extract the text, and convert it into an audio file. The app is built using Python and several libraries, including PyPDF2 and gtts.

## Features
* Upload a PDF file
* Extract the text from the PDF file
* Convert the extracted text into an audio file
* Download the extracted text and the audio file

## Requirements
* Python 3.x
* Streamlit
* PyPDF2
* gtts
* re (regular expressions)

## How to run the app
1. Clone the repository to your local machine.
2. Install the required packages by running `pip install -r requirements.txt`.
3. Run the app by executing `streamlit run Text_Extractor.py` in your terminal or command prompt.
4. The app will be available in your browser at `http://localhost:8501/`.

## How to use the app
1. Upload a PDF file by clicking the `"Upload a file"` button.
2. The app will extract the text from the PDF file and display it on the screen.
3. To convert the text into an audio file, click the `"Convert to audio"` button.
4. To download the extracted text, click the "Download text" button.
5. To download the audio file, click the "Download audio" button.

## Limitations
* The app currently only supports PDF files.
* The audio file is generated using Google's text-to-speech API and may not sound natural.
* The app may not work correctly with PDF files that are scanned or contain images.

## Contributions
This app is open-source, and contributions are welcome. If you have any ideas for improvement, please submit a pull request.
