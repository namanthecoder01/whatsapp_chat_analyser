# WhatsApp Chat Analyzer

## Overview
The WhatsApp Chat Analyzer is a Python-based tool that allows you to analyze WhatsApp chat data. It provides various insights such as the most active users, common words, emoji usage, and more. This tool leverages the power of `pandas`, `matplotlib`, `seaborn`, and `streamlit` to offer an interactive and user-friendly analysis experience.

## Features

- **Message Frequency**: Analyze the frequency of messages over time.
  
- **User Statistics**: Identify the most active users in the chat.
  
- **Emoji Analysis**: Determine the most frequently used emojis.
  
- **Word Cloud**: Generate a word cloud of the most common words in the chat.
  
- **Daily/Weekly Activity**: Visualize activity patterns over different days and times.
  
- **Interactive UI**: User-friendly interface using Streamlit for easy interaction.

Usage

Export WhatsApp Chat

Open WhatsApp on your mobile device.

Navigate to the chat you want to analyze.

Click on the three dots in the top-right corner > More > Export chat.

Choose "Without Media" and send the exported .txt file to your email or save it to your device.

Running the Analyzer

Place the exported chat .txt file in the project directory.

Rename the file to whatsapp_chat.txt or update the path in the app.py file.

Run the Streamlit app:

streamlit run app.py

Open the provided URL in your browser to access the analyzer interface.

File Structure

whatsapp-chat-analyzer/
│
├── app.py                   # Main Streamlit app script

├── helper.py                # Helper functions for processing chat data

├── requirements.txt         # Python packages required

├── whatsapp_chat.txt        # Sample WhatsApp chat file (not included in repo)

└── README.md                # Project documentation
