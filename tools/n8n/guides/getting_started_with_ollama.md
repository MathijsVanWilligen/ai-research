# 📥 How to Pull Ollama Models

Before you can use an AI model like `llama3`, you need to **download ("pull")** it.

> [!NOTE]
> This guide assumes you've read the n8n starting guide and have ollama already up and running.

---

## 🖥️ Step 1 – Open a Terminal Inside the Ollama Container

If you're using Docker:

1. Open **Docker Desktop**.
2. Find the container named `ollama`.
3. Click on it.
4. Click on 'Exec'.
5. You are now inside the container.

---

## 📥 Step 2 – Pull a Model

In the terminal, run:

```bash
ollama pull llama3.1:8b
```
This downloads the model to your local machine. It may take several minutes and use several GB of space.

> [!NOTE]
> This is a small model that i capable of running on limited hardware, therefore the reasoning / feedback of the model could be a lot less than for example chatgpt.

---------------

## 🧪 Step 3 – Test the Model
You can test the model directly from the terminal:

```
ollama run llama3.1:8b
```

You’ll get an interactive prompt. Try asking a question like:

```
What is the capital of Japan?
```