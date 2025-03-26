# TelegramBot-powered AI-FUEL as RewardStream

<img src="https://github.com/AdamAdonyi/TelegramBot/blob/main/Telegram.JPG" width="45%" height="45%"/>

Telegram Bot for Collecting Training Data
This repository contains a Python script for a Telegram bot that allows users to submit training data for your AI model. Users can upload photos or videos containing your desired data type and receive rewards for their contributions.

# Features:

Welcomes users and explains the reward system.
Handles photo and video uploads.
Saves uploaded files securely.
Provides users with an auto-reply message with additional resources after their first submission.
Validates user-submitted wallet addresses (must be 48 characters long).
Offers helpful resources like website, whitepaper, and Telegram group link.
Getting Started

# Requirements:

Python 3
Libraries: telebot, requests, os, time, threading
Replace placeholders:
Update BOT_TOKEN with your Telegram bot token (refer to https://core.telegram.org/methods).
Replace _YOUR_COMPANY_NAME_ with your company name.
Update placeholders in welcome message for the kind of data you need.
Update website and whitepaper URLs in the auto-reply message.
Run the script:
Install required libraries (pip install telebot requests).
Run the script using python TelegramBot_Final.py.

# Deployment (Optional):

Consider deploying the bot to a cloud platform like Heroku or AWS for continuous operation.
You will need to update the script to handle environment variables for the bot token and potentially file storage paths.
Additional Notes:

The script includes error handling and restarts the bot automatically in case of exceptions.
The code uses basic file naming conventions for saving uploaded data. You might want to implement a more robust storage solution for larger scale deployments.

