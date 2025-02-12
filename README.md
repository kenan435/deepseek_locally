```markdown
# 1) Install Ollama

**Quick intro to Ollama:** It's a tool for running AI models locally on your machine. Grab it here: [https://ollama.com/download](https://ollama.com/download)

> *r/macapps - Got DeepSeek R1 running locally - Full setup guide and my personal review (Free OpenAI o1 alternative that runs locally??)*

---

# 2) Pull and Run the DeepSeek R1 Model Locally

Ollama offers different model sizes - basically, bigger models = smarter AI, but they need a better GPU. Here's the lineup:

- **1.5B version (smallest):**
  ```bash
  ollama run deepseek-r1:1.5b
  ```

- **8B version:**
  ```bash
  ollama run deepseek-r1:8b
  ```

- **14B version:**
  ```bash
  ollama run deepseek-r1:14b
  ```

- **32B version:**
  ```bash
  ollama run deepseek-r1:32b
  ```

- **70B version (biggest/smartest):**
  ```bash
  ollama run deepseek-r1:70b
  ```

Maybe start with a smaller model first to test the waters. Just open your terminal and run:

```bash
ollama run deepseek-r1:8b
```

Once it's pulled, the model will run locally on your machine. Simple as that!

> **Note:** The bigger versions (like 32B and 70B) need some serious GPU power. Start small and work your way up based on your hardware!

> *r/macapps - Got DeepSeek R1 running locally - Full setup guide and my personal review (Free OpenAI o1 alternative that runs locally??)*

---

# 3) Set Up Chatbox - A Powerful Client for AI Models

**Quick intro to Chatbox:** A free, clean, and powerful desktop interface that works with most models. I started it as a side project for 2 years. It’s privacy-focused (all data stays local) and super easy to set up—no Docker or complicated steps. Download here: [https://chatboxai.app](https://chatboxai.app)

In Chatbox, go to settings and switch the model provider to Ollama. Since you're running models locally, you can ignore the built-in cloud AI options - no license key or payment is needed!

> *r/macapps - Got DeepSeek R1 running locally - Full setup guide and my personal review (Free OpenAI o1 alternative that runs locally??)*

Then set up the Ollama API host - the default setting is `http://127.0.0.1:11434`, which should work right out of the box. That's it! Just pick the model and hit save. Now you're all set and ready to chat with your locally running Deepseek R1! 🚀

> *r/macapps - Got DeepSeek R1 running locally - Full setup guide and my personal review (Free OpenAI o1 alternative that runs locally??)*

---

Hope this helps! Let me know if you run into any issues.

---

### Here are a few tests I ran on my local DeepSeek R1 setup (loving Chatbox's artifact preview feature btw!) 👇

**Explain TCP:**

> *r/macapps - Got DeepSeek R1 running locally - Full setup guide and my personal review (Free OpenAI o1 alternative that runs locally??)*

Honestly, this looks pretty good, especially considering it's just an 8B model!
```
