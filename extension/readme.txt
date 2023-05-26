First of all, install dependencies

npm install
Copy .env-example into a new file named .env and add your ChatGPT API Key.

Run the server so the extension can communicate with ChatGPT.

node server.js
This will automate interaction with ChatGPT through OpenAI's API, thanks to the chatgpt-api library.

Add the extension

Go to chrome://extensions in your Google Chrome browser
Check the Developer mode checkbox in the top right-hand corner
Click "Load Unpacked" to see a file-selection dialog
Select your local chatgpt-chrome-extension/extension directory
You'll now see "Ask ChatGPT" if you right click in any text input or content editable area.