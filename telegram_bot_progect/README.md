MustiCanvasBot (ImageBot):

Functionality: Receives user prompts and leverages the CoHere API to transform text inputs into visually captivating images.
Telegram Commands:
/start: Extends a warm welcome and invites users to specify their desired content for image generation.
/help: Offers a concise overview of the bot's capabilities.
Message Handling:
Listens for user text inputs and initiates the image generation process.
Sends the generated images back to users for review.
InsightIQBot (AnswerBot):

Functionality: Utilizes the CoHere API to provide intelligent responses to user queries, contributing valuable insights.
Telegram Commands:
/start: Greets users and encourages them to pose questions.
/help: Provides information on the bot's ability to deliver answers to user inquiries.
Message Handling:
Listens for user questions and employs the CoHere API to generate and transmit responses.
Technical Details:

Technologies Used:
Python programming language.
CoHere API for both text-to-image generation (MustiCanvasBot) and question answering (InsightIQBot).
Telebot library for Telegram bot development.
Threading for concurrent execution of both bots.
User Interaction:
Users can seamlessly engage with MustiCanvasBot to create unique images by submitting text prompts.
InsightIQBot facilitates interactive conversations by providing detailed answers to user queries.