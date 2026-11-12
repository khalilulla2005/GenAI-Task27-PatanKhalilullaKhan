# Assignment 27: Chatbots with Conversation History

**Student Name:** Patan Khalilulla Khan  
**Course:** GenAI Training Program  

## Overview
This assignment demonstrates the implementation of stateful chatbots in LangChain by managing conversation history through message placeholders, history trimming, and structured stateful chatbot design.

## Key Features
- **Message Handling**: Utilizing System, Human, and AI messages.
- **State Management**: Using ChatMessageHistory and MessagesPlaceholder to maintain context.
- **History Trimming**: Logic for managing token limits by trimming conversation depth.
- **Stateful Chatbot**: A wrapper class for maintaining conversational state across turns.

## Setup Instructions
1. Install dependencies: `pip install langchain-openai`
2. Set your OpenAI API key: ` = "your_key"`
3. Run the Jupyter Notebook in the `notebook/` directory.
