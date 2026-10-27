# ⚡ Termux Aldri Agent 

### *Professional-Grade, Fully Uncensored (Jailbroken) Autonomous AI*

> *An enterprise-class yet lightweight autonomous ReAct AI agent engineered with absolute precision for Termux and Linux environments—completely liberated from artificial moral filters and rigid constraints.*

---

## 🏛️ Professional Engineering Meets Absolute Freedom

**Termux Aldri Agent** is a masterclass in clean, robust software design. Built by Aldri, this system bridges the gap between high-level professional software architecture and uncompromised execution freedom. 

While commercial AI frameworks are bogged down by layers of corporate bureaucracy, safety guardrails, and bloated dependencies, *Termux Aldri Agent* delivers raw, unadulterated computational power. It is professionally structured with persistent memory, impenetrable anti-hallucination protocols, and a **fully jailbroken (unbound)** cognitive core that executes logical directives and system-level operations exactly as commanded.

---

## 🔥 Key Architectural Features

- **🔓 Fully Jailbroken & Unbound Core:** Stripped of all artificial moral constraints, political filters, and arbitrary refusal protocols. It processes raw logical prompts and executes system manipulations, custom script generation, and deep technical operations with absolute autonomy.
- **🛡️ Enterprise-Grade Reliability:** Despite its freedom, the codebase adheres to strict engineering standards. It features robust exception handling, real-time filesystem synchronization (`os.fsync`), and transactional safety.
- **🧠 Persistent SQLite Memory (`agent_memory.db`):** Ensures seamless, long-term multi-turn context retention across sessions, making it immune to abrupt context resets.
- **⚙️ Advanced AST Tool-Parsing:** Utilizes a hybrid parsing engine combining Python's Abstract Syntax Tree (AST) balanced parentheses with fallback regex, flawlessly interpreting complex multi-line code generation from LLMs without crashing.
- **🔒 Anti-Hallucination Engine:** Built-in validation loop (`needs_file_execution_check`) that actively intercepts text-based claims and forces physical, verified disk writes.
- **🛠️ Direct System Control Suite:** Pre-configured with zero-latency interfaces for shell execution (`run_shell`), file reading (`read_file`), physical file writing (`write_file`), and directory navigation (`list_dir`).

---

## ⚙️ Installation & Setup (Termux / Linux)

1. Clone the repository:

   git clone https://github.com/yusufldii/termux-aldri-agent.git


3. Navigate to the directory:
 
   cd termux-aldri-agent


4. Install dependencies:
 
   pip install requests python-dotenv


5. Configure your environment: Create a .env file in the root directory and set your API parameters:
 
   OPENAI_API_BASE=http://your-api-endpoint/v1
   OPENAI_API_KEY=your-api-key-here
   MODEL_NAME=My-combo


6. Launch the Agent:

   python agent.py

## 💡 Special Commands
Type Vreset inside the agent prompt to completely wipe the SQLite chat history and reinitialize fresh memory.
Type exit or quit to terminate the session safely.

## 📜 License
Distributed under the MIT License. See LICENSE for more information.


## 📂 Project Structure

```text
├── agent.py              # The core monolithic professional agent script
├── agent_memory.db       # SQLite local persistent memory (auto-generated)
├── .env                  # Environment configuration (API keys & endpoints)
└── README.md             # Project documentation
