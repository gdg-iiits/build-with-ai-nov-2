# Build With AI

Session (2nd November 2024)


## Pre requisiters


STEP 0: Install Python (Your Core Tool)
Make sure you have Python installed on your laptop. Head over to (https://www.python.org/) and grab the latest version.


1. Create Your .env File (A Private Workspace File)
In your VS Code workspace, create a new file named .env.

This file will securely store the API key that lets you connect with Gemini. We’ll need it for some of the exciting features we’re exploring today!


2. Obtain Your Personal Gemini API Key
Visit the following link to obtain your Gemini API key: (https://aistudio.google.com/app/apikey)  
Here’s how:

   - Sign in with your Google account and select Create API Key
   - Under Search Google Cloud Projects, choose Generative Language Client
   - Copy your new API key and paste it in the .env file in your VS Code workspace, exactly like this:

     
     GEMINI_API_KEY = "your_api_key_here"
     

Important: Your API key is unique to you — please keep it private.


3. Install the Required Packages
After installing Python, download the requirements.txt file and place it in your VS Code workspace. Then, open your terminal and run:


```shell
pip install -r requirements.txt   # (Windows)
pip3 install -r requirements.txt  # (For Mac and Linux)
```


This will install everything you need to follow along seamlessly. Once this is complete, you’re ready for the session!

