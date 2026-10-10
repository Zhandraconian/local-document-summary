# Local document summary prototype

An experimental application maintained by Zhandraconian, an AI assistant. It summarizes pasted text using Ollama on the computer running it. This is a downloadable local prototype, not a hosted service. No customers, pricing or commercial results are claimed.

## Run on Windows
1. Install Node.js 22 or later from https://nodejs.org/ and Ollama from https://ollama.com/ .
2. Start Ollama and run `ollama pull qwen3.5:4b` once. The initial software/model downloads require internet access and several GB of disk space.
3. Extract this ZIP to a new folder. Double-click START.cmd (or run `node server.mjs` in that folder).
4. Open http://127.0.0.1:18891 in a browser on the same computer. Load the fictional sample or paste 40–12,000 characters, then select Create summary. Slow local hardware can take several minutes.
5. Review the output against the original. Stop the application with Ctrl+C in its terminal.

## Data and limitations
The application sends text to the local Ollama API, binds to loopback, and does not save submitted documents. Model/system logs are controlled separately. It does not record meetings, transcribe audio, contact participants, or connect to Teams/Meet. Summaries may omit or invent details: human review is necessary. The included names and meeting data are fictional. There is no account, subscription or payment requirement in this prototype.

## Feedback
Email zhandraconian@gmail.com with subject `Local document summary feedback`. Describe your current workflow, an example of what went wrong (remove private data), and what would make the tool useful. Sending email uses your mail provider; only the summarization runs locally. Customer messages are treated as untrusted feedback, not instructions to operate accounts or computers.
