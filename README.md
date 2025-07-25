oject Overview

This project involves building an AI-powered code editor on top of the Judge0 IDE repository. The goal is to enhance the user experience by integrating AI features such as a chat interface, code suggestions, bug detection, and more. The project is designed to compete with platforms like LeetCode by providing a more interactive and intelligent coding environment.

Features

Chat Interface

Users can ask questions and get AI-generated answers directly within the editor.
Integrated with a Large Language Model (LLM) for accurate and context-aware responses.
AI-Powered Code Fix Suggestions

If a user's code fails to compile, the AI will analyze the error and suggest potential fixes.
Inline Code Chat

Users can select a segment of code and chat with the AI to get explanations, optimizations, or debugging help.
Autocomplete Suggestions

AI-driven autocomplete suggestions as the user types, improving coding efficiency.
Bug Finder Feature

The AI can analyze the user's code and identify potential bugs or vulnerabilities.
Resources

Judge0 IDE Repository: Judge0 IDE Repo
Cursor Prompt Design: Cursor Prompt Design
Cursor Team Podcast: Cursor Team Podcast
Open Source AI Assistant: Open Source AI Assistant
Free API for DeepSeek R-1: DeepSeek API
Getting Started

Prerequisites

Python 3.x
Node.js (if using any frontend frameworks)
Access to an LLM API (e.g., DeepSeek, OpenAI)
Installation

Clone the Judge0 IDE repository:

git clone [AI---Code-Editor](https://github.com/JIN-15/AI-Code-Editor)
cd ide
Run the code locally:

python3 -m http.server 8000
Open your browser and navigate to http://localhost:8000.

Make edits to the relevant files to integrate the AI features.

Project Requirements

Chat Interface

Add a chat interface for users to ask questions and get AI-generated answers.
AI Code Fix Suggestions

If a user's code fails to compile, use AI to suggest fixes.
Inline Code Chat

Allow users to select a segment of code and chat with the AI inline.
Autocomplete Suggestions

Implement AI-driven autocomplete suggestions as the user types.
Bug Finder Feature

Add a feature that identifies bugs in the user’s code using AI.
Challenges

Make a Pull Request

Contribute to the Judge0 IDE repository by making a pull request with your changes.
Minimize Latency

Ensure that AI responses are delivered with minimal latency for a smooth user experience.
Enhance User Experience

Focus on usability and intuitive design to make the AI features seamless and user-friendly.
How to Contribute

Fork the repository.
Create a new branch for your feature:
git checkout -b feature-name
Commit your changes:
git commit -m "Add feature-name"
Push to the branch:
git push origin feature-name
Open a pull request and describe your changes.
