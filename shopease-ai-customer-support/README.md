# ShopEase – AI Customer Support Chatbot

## Overview

ShopEase is a simple e-commerce website integrated with an AI-powered customer support chatbot. The chatbot uses Google Gemini through n8n to understand customer queries and generate helpful responses.

The project demonstrates how generative AI, workflow automation, conversational memory, and spreadsheet integration can be combined to automate customer support tasks.

## Features

- Simple e-commerce website with product listings
- AI-powered customer support chat
- Natural-language responses using Google Gemini
- Conversation memory using n8n Simple Memory
- Google Sheets integration for support records
- Automated workflow orchestration using n8n

## Technologies Used

- HTML, CSS and JavaScript
- n8n Cloud
- Google Gemini
- Google Sheets
- AI Agent and Simple Memory

## Workflow

1. A customer interacts with the chatbot on the website.
2. The Chat Message Trigger receives the message.
3. The AI Agent processes the message using Google Gemini.
4. Simple Memory provides conversational context.
5. The connected Google Sheets tool handles support-record operations as configured.
6. The AI-generated response is returned to the customer.

## Project Structure

- `index.html` – E-commerce website
- `n8n-workflow.json` – Exported n8n workflow
- `screenshots/` – Project screenshots

## Setup

1. Download or clone this repository.
2. Open `index.html` in a browser to view the demo website.
3. Import `n8n-workflow.json` into your n8n instance.
4. Configure your own Google Gemini credentials.
5. Connect your own Google Sheets account and select the appropriate spreadsheet.
6. Verify the chatbot trigger and website integration settings.
7. Test the chatbot with sample customer queries.

## Security

Never commit API keys, OAuth tokens, passwords, or private customer information. Configure your own credentials in n8n.

## Limitations

This is an educational project. The website and chatbot should not be treated as a production-ready customer support or payment system without additional security, testing, and backend integration.

## Author

MCA Student | Aspiring AI and Automation Professional