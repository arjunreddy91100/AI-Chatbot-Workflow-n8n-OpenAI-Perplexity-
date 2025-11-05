# AI-Chatbot-Workflow-n8n-OpenAI-Perplexity-
A simple end-to-end AI chatbot built with n8n, leveraging OpenAI GPT-4.1-mini and Perplexity API for smart conversational responses.

## Overview

This project is a lightweight n8n workflow that turns any incoming chat message into an intelligent, contextual reply using state-of-the-art language models. The system listens for chat messages, sends them to an AI agent (connected to GPT-4.1-mini and Perplexity), and returns a relevant, researched response.

## How It Works

- **Trigger:** The workflow activates when a chat message is received.
- **AI Agent:** The message is processed by an n8n AI Agent node.
- **OpenAI Chat Model:** Uses GPT-4.1-mini to generate conversational replies.
- **Perplexity Tool:** Optionally enriches responses with live information from Perplexity API.

## Key Features

- Seamless integration with OpenAI and Perplexity for high-quality answers
- Supports file uploads for extended context
- Easily expandable for more chatbot features

## Usage

1. Import the provided JSON workflow (`My-workflow-3.json`) into your n8n instance.
2. Configure your OpenAI and Perplexity credentials.
3. Activate the workflow. 
4. Send a chat message to the webhook to receive an AI-powered response.
