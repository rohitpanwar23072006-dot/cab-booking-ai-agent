Cab Booking AI Agent

This repository contains an AI-powered cab booking assistant designed to run inside automated workflows. It allows users to book a cab through simple conversational messages.

The system uses WhatsApp Cloud API for sending and receiving messages, Google Gemini for natural language understanding, and simulated cab booking logic.

Features:

* Conversational booking flow
* Pickup and drop location extraction
* Trip estimate simulation
* Booking confirmation messages
* Session-based conversation handling
* Customizable workflow logic

How It Works:

1. User sends a message through WhatsApp.
2. The agent processes the message using Gemini.
3. It identifies the intent and extracts required details.
4. It simulates cab availability, fare estimates, and ETA.
5. The user receives a confirmation or follow-up questions.

Tech Stack:
WhatsApp Cloud API, Google Gemini, n8n workflow automation, JavaScript and JSON-based logic.

Important Notes:
This project uses simulated cab APIs and does not perform real bookings.
You must configure your WhatsApp Cloud API and Gemini API keys manually.
Screenshots, demo videos, and workflow JSON can be added in the assets folder.

Setup:

1. Import the workflow JSON file into n8n.
2. Add your Gemini API key in the HTTP Request node or credentials.
3. Set up WhatsApp Cloud API and configure the webhook.
4. Deploy and test using your WhatsApp number.

Future Improvements:
Real cab service API integration
Payment flow
User history and ride suggestions
Multi-language support

License:
This project is for educational and hackathon purposes. You may modify and use it freely.
