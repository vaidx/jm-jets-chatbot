# JETS Careers Chatbot

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

### Maintenance -
##Intents : (brief reply content)
- bad-words : 
- contact-us : Ask for Contact.
- convo-extension : Reply Emoji.
- Default Fallback : Ask user to type their question again.
- Default Welcome : First chatbot reply. Greeting and showing a menue.
- end-session : Ensure user will quit chatbot. Last chatbot reply.
- jets-app-process : List all application process: 1. Online Application (10 mins) 2. Online Tests (70 mins) 3. On-Demand Video Interview (20 mins) 4. Assessment Centre (Full Day, In person) 5. Offer
- jets-app-timeline-center : Show all Assessment Schedule.
- jets-apply-now : Link to Application Form.
- jets-faqs : Show a menu of all FAQs. To direct user to their desired FAQs.
- jets-info : About JETS, focus on the benefits of joining JETS.
- jets-salary : About the salary in JETS Programe
- jm-about : Show the menue of all "About", include Our Company, History, Business Unit
- jm-company : About Jardine and Matheson
- jm-history : About Jardine and Matheson
- jm-menue : Show the menue. To direct user to their desired 
- jokes : No response. Debug purpose.
- kb-app-rolling : Application process is NOT on a rolling basis, there is screening
- kb-app-total-time : The duration of entire recruitment processes from appling to giving offer 
- kb-astra : About Astra International
- kb-df : About Daily Farm
- kb-email-apply : Emphasis application method must be done by online application
- kb-hk-land: About Hong Kong Land
- kb-intake-num : About number of quota
- kb-jcc : About Jardine Cycle & Carriage 
- kb-jmmotors : About Jardine motors
- kb-jp : Jardine Pacific
- kb-mo : Mandarin Oriental
- kb-reapply : People can re-apply even they have failed in previous year application
- kb-when-hear-back : The duration to get the application results
- kb-work-exp : It is not a must to have work experience. Target are fresh graduates.

##Entities

1. Training Data (train users' input to correct intents)
means add more training phrase that triggers the Intent


2. Add / Change Responses (the content answered by the chatbot)
Press Intents, go to section Response and press button ADD RESPONSES 


### Suggested Improvements -
- Migrate from static to dynamic responses using Firebase database.
- Using data from other sources for training phases.
- Addition of entities for more accurate intent matching.

### Resources -

- [DialogFlow Getting Starting Guide](https://dialogflow.com/docs/getting-started)
- [Facebook Messenger Integration](https://dialogflow.com/docs/integrations/facebook)
- [Firebase](https://firebase.google.com/docs/firestore/)
- [Kommuicate](https://docs.kommunicate.io/)
- [Bot Integration](https://www.kommunicate.io/blog/how-to-integrate-bot-using-dialogflow-in-kommunicate-1ac32911a7d0/)
- [Dialogflow + Kommunicate](https://www.kommunicate.io/blog/beginners-guide-to-creating-chatbots-using-dialogflow/)

