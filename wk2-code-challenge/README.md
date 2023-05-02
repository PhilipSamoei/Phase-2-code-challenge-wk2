# Bot Battlr
Bot Battlr is a React application that displays a list of bots that you can enlist in your army. This app allows you to browse through a list of robots, view a robot's details, and enlist a bot into your army.

## Requirements
To run this application you will need to have the following installed:

## Node.js
NPM
Project Setup
Follow the instructions below to set up this project on your local machine:

Clone this repository: git clone https://github.com/your-username/bot-battlr.git
Install the dependencies: npm install
Create a new file called db.json in the root directory of the project.
Copy the contents of this data file to db.json.
Start the JSON server by running the following command: npm run server
Start the application by running the following command: npm start
Open your browser and navigate to http://localhost:3000.
Features
## Core Deliverables
See profiles of all bots rendered in BotCollection.
Add an individual bot to my army by clicking on it. The selected bot should render in the YourBotArmy component. The bot can be enlisted only once. The bot does not disappear from the BotCollection.
Release a bot from my army by clicking on it. The bot disappears from the YourBotArmy component.
Discharge a bot from their service forever, by clicking the red button marked "x", which would delete the bot both from the backend and from the YourBotArmy on the frontend.
## Advanced Deliverables
Choose if I want to enlist a bot into my army or just see their data. Clicking on the card should instead display a show view (BotSpecs) for that bot, which should replace BotsCollection. BotSpecs should have two buttons: one to go back to the list view and another to enlist that bot.
Sort bots by their health, damage or armor. For this, create a new component, SortBar.
When I enlist a bot it will be removed from the BotCollection and added to YourBotArmy.
Filter bots by their class. We can select a few filters at the same time.
Sort bots by their health, damage or armor. For this, create a new component, SortBar.
## Contributor
Philip Samoei
## License
This project is licensed under the MIT License 