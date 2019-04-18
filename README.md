# jm-jets-chatbot

### Platforms in use - 
- _Dialogflow_ - A Google-owned platform that give users new ways to interact with your product by building engaging voice and text-based     conversational interfaces, such as voice apps and chatbots, powered by AI.
- _Facebook Messenger_ - Integration for Chat UI.
- _Kommunicate_ - Kommunicate is a live chat and chatbots powered software for real-time, proactive and efficient customer support.

### Features -
- Answers questions related to JETS recruitment.
- Answer content is currently based on the Jardines Careers website.
- A Knowledge Base has been used to answer FAQs.
- Uses Small Talk mechanism
- Integrate with Facebook Messenger or embed on website, mobile app using Kommunicate
- Uses 3rd party Chuck Norris API to tell jokes (Demo PoC, ([Link](https://api.chucknorris.io/)))

### Setup Guide - 
1. Download/Clone the **jm-jets-chatbot** git repository or download the zip file.
2. Create a new agent in Dialogflow and subsequently import the zip file via the Settings menu.
3. Setup Facebook Messenger integration and webhook. (See resources section for help).
4. Setup Kommunicate account and get embed code from bot integration menu. (See resources section for help)
4. Start chatting with Harvey on Messenger, website or mobile app.

### Style Guide -
- Smallcase naming convention has been applied throughout the project.
- Breaking down intent naming into jm-, jets-, and kb- primary classes.

### Suggested Improvements
- Migrate from static to dynamic responses using Firebase database.
- Using data from other sources for training phases.
- Addition of entities for more accurate intent matching.

### Resources -

- [DialogFlow Getting Starting Guide](https://dialogflow.com/docs/getting-started)
- [Facebook Messenger Integration](https://dialogflow.com/docs/integrations/facebook)
- [Firebase](https://firebase.google.com/docs/firestore/)
- [Kommuicate]https://docs.kommunicate.io/
- [Bot Integration](https://www.kommunicate.io/blog/how-to-integrate-bot-using-dialogflow-in-kommunicate-1ac32911a7d0/)
- [Dialogflow + Kommunicate](https://www.kommunicate.io/blog/beginners-guide-to-creating-chatbots-using-dialogflow/)

