Groq Conversation Management and Classification

This repository contains my internship assignment implementation for Conversation Management & Classification using Groq API (OpenAI SDK compatible).

Objectives

Manage conversation history with summarization and truncation.

Extract structured user details from chats using JSON schema and function calling.

Task 1: Conversation Management

Maintains running history of user–assistant chats.

Supports truncation:

By number of turns.

By character length.

Periodic summarization after every k runs.

Demonstrated with sample conversations.

Task 2: JSON Schema Extraction

Defines a schema to extract: name, email, phone, location, age.

Uses Groq API with OpenAI-compatible SDK for structured extraction.

Demonstrated with multiple sample inputs.

Files

Conversation_Management (1).ipynb – Main Colab notebook with both tasks implemented.

Usage

Open the notebook in Google Colab.

Insert your Groq API key in the designated cell.

Run cells sequentially to test Task 1 and Task 2.
