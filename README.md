# my-oneUniAI (Unified AI Web Agent)

🚀 Overview
UniAI is a local AI-powered web agent that understands natural language commands, controls a browser, and performs tasks like searching, clicking, data extraction, and automation.  
It runs fully on your system — no cloud dependency — combining an LLM backend with browser automation.

✨ Core Features
- 🗣 *Natural Language Instructions* — Give commands like:  
  "Search for laptops under ₹50,000 and list top 5"  
- 🎤 *Voice Input Support* — via Web Speech API / Python speech recognition.  
- 🌐 *Browser Automation* — Powered by Chrome Headless / VM browser.  
- 📊 *Structured Outputs* — Results returned as clean JSON or tables.  
- 📄 *Example Workflows*  
  - Extract documentation or Stack Overflow code snippets  
  - Compare e-commerce products (Amazon/Flipkart)  
  - Collect and summarize research papers  
  - Recruiter/job posting extraction  
  - Automate form filling  

 🛠 Tech Stack
- *LLM Engine:* Ollama / GPT4All (LLaMA 2/3, Mistral, or fine-tuned models)  
- *Browser Automation:* Playwright / Puppeteer / Selenium  
- *Voice Processing:* Web Speech API / SpeechRecognition (Python)  
- *Frontend:* Simple website with search & voice command interface  
- *Backend:* Local execution — runs exactly as instructed (no forced upgrades)  

 🎯 Why UniAI?
Instead of juggling multiple tools, UniAI provides a single, unified AI platform for:  
- Students (learning, quick info lookups)  
- Developers (scraping, research assistance)  
- E-commerce users (product comparison)  
- Recruiters & professionals (job postings, applications)  

 📌 Roadmap
- [ ] MVP: Natural language → browser action → structured output  
- [ ] Voice command integration  
- [ ] Web interface with multi-topic search (e.g., songs, bus tickets, movies)  
- [ ] Extended automation (forms, registrations, comparisons)  
