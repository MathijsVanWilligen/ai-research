# 🤖 Bonus: Create a Simple AI Agent with Ollama

## 🎯 Goal

Build a simple AI assistant that receives a question and sends it to Ollama for an answer.

---

## 🧩 Step 1 – Create a New Workflow

1. Click **“New”** > “Start from scratch”.
2. Name your workflow, e.g., `AI Chat Agent`.

---

## 🌐 Step 2 – Add a Chat Node

1. Click the **"+"** button in the workflow editor.
2. Search for and add **Chat Trigger**.
3. Save the node.

---

## 🌐 Step 3 – Add an Ai Agent node

1. Add a new node: **“Ai Agent”**.

---

## 🌐 Step 4 – Connect to Ollama

1. Click besides the Ai Agent node on 'Chat Model'
2. Search for and add **Ollama Chat Model**.
3. Configure the node with an Ollama account
3.1 Set the Url to 'http://ollama:11434'
3.2 Select the model 'llama3.1:8b' (as we've downloaded this in 'getting_started_with_ollama')
4. Save the node

---

## ✅ Step 5 – Activate and Test the Workflow

1. Click on 'Open chat'
2. Send a message and press enter
3. Your question should be sended to the llama3.1 model
4. The response should be visible inside the chat window.