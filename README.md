# WGU-951
Computer Science career finder chatbot

Jason Philpy
ID: 001467497

CS Career Chatbot Information


Functionality
The chat bot will respond to a variety of greetings to get things started. The bot will then prompt the user to type “help” in order to start the process of determining a computer science career. The first question will ask about a preference of painting a picture or solving a puzzle. The bot will respond to an either “picture” or “puzzle” keywords.  From there, the bot will ask yes or no questions and respond to many synonyms for yes/no. This will then lead the bot to a career choice with a link to more information. This will allow students in the scenario to identify a career based on their preferences.

Test Cases
For test cases, I had users interact with the bot and review the logs for improvements.  The first test case showed that users struggled responding and getting an appropriate response from the puzzle or painting question.  This was fixed by adding a catch-all pattern that would trigger with any series of responses so long as it contained the appropriate keyword. Another test case indicated that users would respond to a yes/no question with yes/no synonyms instead of the specific word. To address this issue, I added sets for affirmative and negative responses so that the bot would understand a variety of responses.

Chatbot Development Environment
On strength of the Pandorabots development environment was the instant compilation of the code.  I could make changes to an AIML file and the testing bot would immediate reflect those changes without even having to restart or clear the chat logs of the bot. One weakness of the environment was the actual code editor itself. As a developer coming from other IDEs, there were some features missing like full screen editing, find/replace, etc.

Monitoring and Maintenance
I plan to deploy the bot onto the Pandorabot platform and monitor the user interaction logs. These logs are a great way to see where users get stuck or have issues with the chatbot and provide improvements.  Additional sets for pattern answers can be created as well as further cases for existing sets when users respond with words that are missing but still appropriate for the exisiting set.
