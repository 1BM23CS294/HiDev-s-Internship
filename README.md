
Project: Self-Managed Logging Aggregator
Hi, welcome to my logging project!

1. What is this?
I built this website, the Self-Managed Logging Aggregator, because I wanted a free way to check my server logs.
Usually, companies charge a lot of money for tools like Splunk or Datadog, but as a beginner developer, I don't have that kind of budget!

This is a self-managed dashboard. It takes logs from my backend (Node.js & Python scripts), stores them in a database (MongoDB/SQL), and shows them here. 
I also added some AI magic using Google's Gemini API to tell me if someone is trying to hack me.

2. Tech Stack Used
I used a bunch of different technologies to learn how they work together:

HTML & CSS: The skeleton and styling of this site.
JavaScript (React): To make the buttons work and fetch data.
Node.js: Runs the server that collects the logs.
Python: I use Python scripts to parse heavy text files.
MongoDB: Stores the messy JSON logs.
Gemini API: The brain that reads logs for me.
3. How to run this code
If you want to run this on your computer, grab the code from GitHub and follow these steps.

⚠️ IMPORTANT NOTE

Please use Command Prompt (cmd) to run these commands. Do NOT use PowerShell, as the instructions may not work correctly there.

// Step 1: Download

Download the file from GitHub in ZIP file mode.

// Step 2: Extract

Extract the ZIP file you just downloaded.

// Step 3: Open VS Code

Open the terminal and type code . to open all files in VS Code.

// Step 4: Select Command Prompt

Go to the VS Code terminal and select Command Prompt.

// Step 5: Install

npm i

// Step 6: Start Server

npm run dev

// Step 7: Run Website

Ctrl + Click (or Ctrl+Enter) the localhost link to run the website.

4. About the API Keys
To make the AI analysis work, you need a key from Google. It's basically a password that lets my code talk to their brain.

I have already created a .env file for you in this project folder.

API_KEY=AIzaSyDF6...
(I've set it up so it works right now, but remember: never upload your .env file to a public GitHub repo! It contains your secret key.)
