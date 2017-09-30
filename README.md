# Voice recognition bot chat

This is how this web app works:

1. Using the Web Speech API’s `SpeechRecognition` interface to listen your voice from a microphone
2. Send your message to [API.ai](https://api.ai) (the natural language processing platform) as a text string. Using Customer Support as default data.
3. Once the AI from the API.ai returns the reply text back, use the `SpeechSynthesis` interface to give it a synthetic voice.

#To run this Voice recognition bot chat

1) Install all dependencies by running below command.

npm install

2) Run the node server by running below command.

node index.js

2) Open your browser then go to link below:

http://localhost:8080



