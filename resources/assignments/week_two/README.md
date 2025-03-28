# ✨ Week 2 Assignment: Characterfile Modification + Intro Chatbot

Welcome to Week 2!

This week we’re getting hands-on with how characters are structured in code. 

You’ll explore Eliza’s characterfile logic, make your own edits, and (optionally) create a basic custom chatbot from scratch.

## 🧠 Assignment Objectives
* Understand the default character structure in Eliza’s codebase.
* Modify an existing characterfile to change behaviors, goals, or functionality.
* (Optional) Build a very basic chatbot that responds to greetings.

## 🛠️ Part 1: Modify Default Characterfile
## 1. Clone Eliza Locally
If you haven’t already:

```sh
git clone https://github.com/elizaOS/eliza
cd eliza
```
Install dependencies and explore the folder structure.

## 2. Locate the Characterfile
Navigate to:
```sh
agent/src/defaultCharacter.ts
```
This file contains the default Eliza agent template. You’ll see structure fields like:
* name, username
* system prompt
* bio, lore, topics
* messageExamples
* style, adjectives, and more

## 3. Make Your Modifications
Examples of changes you could make:
* Change its tone (funny, sarcastic, formal)
* Add new response examples
* Modify system instructions to behave differently
* Add goals like: “Keep replies short” or “Pretend to be a medieval wizard”

Be creative! You don’t need to fully understand the full codebase yet; just tinker with the file.