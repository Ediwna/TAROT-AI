# TAROT AI(타로 아이) : Tarot Card-Interpreter
Tarot card is uesd to...

![image](https://github.com/Ediwna/TAROT-AI/blob/main/tarotcard1.jpg?raw=true)

## Contributors
- San Gu, Information System, 2014005305, goosan126@gmail.com
- YeonJu Nam, Information System, 2018007510, skaduswn0515@naver.com
- Yeol Yang, Information System, 2018057701, yeolyang77@gmail.com
- CheongRok Yoon, information System, 2011004556, dbscjdfhr@gmail.com
- Jaemin Lee, Information Systemm 2018007656, jm4984@naver.com

## Proposal
How nice would it be to know your day before it starts? It can’t always be sunny, but I hope it can be a day for you to prepare an umbrella before it rains. Our project is TAROT AI(타로 아이). Recently, apps like fortune cookies and today’s horoscope on YouTube is on trend. TAROT AI tells you a flow of your day through reading tarot cards. TAROT AI gives Nugu speaker users card options from 1 to 78. And the user selects three of them and tell the cards’ number to Nugu speaker. It is a program that Nugu speaker checks the user's voice recognition and summarizes the interpretation of the tarot cards, selected by the user. Recently, it was reluctant to visit tarot shops because of busy life and COVID-19. Also, online tarot cards which is simply about looking at tarot results can fail to give accuracy and clearness. We can easily see tarot through a simple conversation with Nugu speaker while eating lunch or cleaning the house. Why don't you start your day with TAROT AI? Don't be disappointed if you get a bad result. Your day is what you make.

## Related works & Summary
#### Tarot Time

 Tarot Time let users look tarot card with Google Assistant. When you say 'pull a card' in Google Assistant, it will select one of 78 cards and interpret the meaning and advise of the card. Also, it can select a tarot card on every day and inform the result with push alarm.
 For developing Tarot Time, Developers of Tarot Time used following developer tools.

Actions on Google : To let the developer extend the function of Google Assistant.
Dialogflow : Google's natural langauage understanding developer tool
Firebase : The developer tool that make easily mobile server. They use this tool to process the user's request, return the response, and host rich media(like images of tarot cards).

We'll refer to this blog post to develop our tarot card service. But we will use NUGU AI speaker, not Google Assistant, and select three cards, not one card.

![Reference URL](https://medium.com/@jfriedhoff/tarot-time-b149230a35d6?raw=true)

#### NUGU Play

NUGU understands the user's request for natural language (speech language or written language), understands the intention, and then provides information or related services.
The process of handling user utterances on the NUGU platform is as follows.
1. Identify intention through speech recognition
2. Performing actions that fit the identified intention
3. The generated response is transmitted as a synthesized sound
To make this process easier, NUGU developers provide the NUGU play kit.
NUGU play kit provides a GUI-based integrated development environment for developing conversation-based artificial intelligence services, so users can easily develop their own services.
In NUGU play kit, Play Builder, an integrated development environment that provides the element technologies necessary for the process of processing user speech, and enables service development, is provided.

![Reference URL](https://developers-doc.nugu.co.kr/nugu-play?raw=true)
