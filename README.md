# jm-jets-chatbot

### Platforms in use - 
- _Dialogflow_ - A Google-owned platform that give users new ways to interact with your product by building engaging voice and text-based     conversational interfaces, such as voice apps and chatbots, powered by AI.
- _Facebook Messenger_ - Integration for Chat UI.
- _Firebase_ - Cloud Firestore is a flexible, scalable database for mobile, web, and server development from Firebase and Google Cloud    Platform. (To be used as a database for delivering dynamic responses via an API)
- _Kommunicate_

### Features -
- Answers questions related to JETS recruitment
- Answers are base on the current JETS website
- A Knowledge Base has been used to answer FAQs.
- Uses Small Talk mechanism
- Integrate with Facebook Messenger or embed on website, mobile app using Kommunicate (added support)

### Setup Guide - 
1. Download/Clone the **jets-chatbot** git repository.
2. Create a new agent in Dialogflow and subsequently import the zip file via the Settings menu.
3. Setup Facebook Messenger integration and webhook. (See resources section for help)
4. Start chatting with Harvey!

### Style Guide -
- Smallcase naming convention has been applied throughout the project.
- Breaking down intent naming into jm-, jets-, and kb- primary classes.
- Currently based on static responses.

### External APIs being used (for demo demonstration purpose only) -
- Chuck Norris Jokes API ([Link](https://api.chucknorris.io/))

### Suggested Improvements
- Migrate from static to dynamic responses using Firebase database.
- Using data from other sources for training phases.
- Addition of entities for more accurate intent matching.

### Adding support for Kommunicate
- https://www.kommunicate.io/blog/how-to-integrate-bot-using-dialogflow-in-kommunicate-1ac32911a7d0/
- https://www.kommunicate.io/blog/beginners-guide-to-creating-chatbots-using-dialogflow/
- https://docs.kommunicate.io/
- https://docs.kommunicate.io/docs/bot-configration

### Resources -

1. [DialogFlow Getting Starting Guide](https://dialogflow.com/docs/getting-started)
2. [Facebook Messenger Integration](https://dialogflow.com/docs/integrations/facebook)
3. [Firebase](https://firebase.google.com/docs/firestore/)
