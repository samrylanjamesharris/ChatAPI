# ChatAPI - V1.3
A standalone HTML chat interface for interacting with AI models via API. No installation, no backend, just a single file hosted

**Try it live:** [Live Website!](https://samrylanjamesharris.github.io/ChatAPI/chatapi.html)

---

<img width="1366" height="768" alt="Screenshot 2025-08-12 12 20 54 AM" src="https://github.com/user-attachments/assets/4f913bdb-e82c-43e9-8602-46972c8abf1a" />

---

## Features:
- **Zero Dependencies**: Just one HTML file. Easy to host and share.
- **Fully Configurable**: Set your API key, model, endpoint, and system prompt if you want to.
- **UI**: Dark mode design with animations and responsive layout.
- **Markdown Support**: AI responses are rendered with full Markdown (code blocks, tables, lists, etc.).
- **Local Storage**: Remembers your settings between sessions.
- **Works with Any API**: Compatible with OpenAI, Anthropic, Mistral, Ollama, OpenRouter, Gemini, etc.
- **Edit Prompts**: You can now edit your own prompt if you did a typo or worded it incorrectly.
- **Export Chat**: You also can download your AI chat in .json for all your needs incase it's for training a model or saving it for later.
- **Chat Storage**: When you exit the website or reload the page, it'll still be saved for later.

---

## How to Use:
1. **Open the App**  
   Visit the hosted page: [Live Website!](https://samrylanjamesharris.github.io/ChatAPI/chatapi.html)
2. **Open Settings**  
   Click the **Settings** button in the top-right.
3. **Enter Your API Details**
   - **API Key**: Your secret key (e.g., `sk-...`)
   - **Model**: Model name (e.g., `gpt-3.5-turbo`, `claude-3-haiku`, `llama3`)
   - **API Endpoint**: Full URL (e.g., `https://api.openai.com/v1/chat/completions`)
   - **System Prompt**: Set behavior (e.g., "You are a helpful assistant.")
4. **Start Chatting**  
   Type a message and press **Send** or **Enter**.

---

## Security:
- All processing happens **in your browser**, no data is sent to any server.
- Your API key is stored **only in localStorage** and never shared.
- Ideal for private, AI interactions. *(Based on what your API service allows.)*

> **Note**: Don't expose your API key. This app runs client-side, so your key stays with you.

---

## Feedback & Contributions:

Found a bug or want a new feature?  
Feel free to open an issue or pull request and I'll respond as soon as I can.

---

## Updates:

Version History:
| Version | Features and Improvements |
|---------|----------------------------|
| **V1.0** | - Initial release allowing users to interact with any AI model using an **API key**.<br>- Responses are formatted in **Markdown** for more readability, supporting headers, code blocks, tables, and etc. |
| **V1.1** | - Added a **Clear Chat** button to easily erase conversation history without reloading the page.<br>- Introduced **Retry** functionality if the AI fails to generate a response.<br>- Enabled **Copy Code** button for code blocks, allowing easy copying without manual selection.<br>- Improved UI design for a cleaner, more modern appearance. |
| **V1.2** | - Added a **Stop Generating** button to abort ongoing AI responses.<br>- Enhanced error handling for more reliable performance.<br>- Improved local storage to **persist chat history** across page reloads and browser sessions.<br>- Refactored codebase for better structure and readability, making it easier for developers to customize. |
| **V1.3** | - Added the ability to **download chat history** in `.json` format for backup or sharing.<br>- Introduced **editable prompts**, allowing users to correct typos or rephrase their input after sending. |
