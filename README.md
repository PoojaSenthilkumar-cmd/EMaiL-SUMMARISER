**EMail-SUMMARISER**

A Google Colab-based Python tool to fetch, summarize, and report Gmail inbox contents using NLP.

Overview
EMail-SUMMARISER connects to your Gmail inbox, fetches emails based on user queries, summarizes the plain text content of emails using Natural Language Processing, and sends a summary back to your specified email address. It is ideal for efficiently managing and reviewing large inboxes.

Features
Authenticate securely with Gmail via OAuth 2.0

Filter emails by read-status, sender, timeframe, and labels

Summarizes email content using NLP (txtai)

Sends formatted summary report to your desired inbox

Simple, customizable user input for flexible queries

Designed for use in Google Colab

Files
Email_summarizer.ipynb : Main Colab notebook containing all code

client_secret.json : OAuth credentials (not provided here—add your own)

image.jpg : Example or documentation image (add more details if relevant)

Getting Started
Clone or download this repository.

Open Email_summarizer.ipynb in Google Colab.

Upload your client_secret.json for Gmail access.

Run all cells, provide query parameters as prompted, and enter your destination email address when requested.

Installation
Required Python packages (automatically installed in Colab):

google-api-python-client

oauth2client

simplegmail

txtai[pipeline]

Install via:

python
!pip install --upgrade google-api-python-client oauth2client simplegmail
!pip -q install txtai[pipeline]
Usage
The notebook will prompt you for query parameters (read status, sender, labels, etc.).

Summarized results are sent to your specified email.


Contributing
Pull requests accepted. For major changes, please open an issue to discuss what you would like to change.
