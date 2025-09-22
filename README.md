🤖 OpenDeepResearcher – Clarify\_with\_user (LangGraph)



A smart chatbot using \*\*LangGraph\*\* + \*\*Google Gemini\*\* that:

\- ✅ Remembers conversation (memory)

\- 🤔 Asks clarification when queries are unclear

\- 📝 Generates a research brief

\- 👨‍🏫 Sends it to supervisor

\- 📄 Produces final report



---



\## 🚀 Setup

1\. Clone the repo:

&nbsp;  ```bash

&nbsp;  git clone <your\_repo\_link>

&nbsp;  cd OpenDeepResearcher



2\. Install dependencies:



pip install -r requirements.txt



3\. Add your API Key:



Copy .env.example → .env



Paste your Google Gemini API key inside .env



4\. Run Chatbot:



python app.py



🧩 Workflow

flowchart TD

&nbsp;   A\[User Query] --> B{Clarify?}

&nbsp;   B -- Yes --> C\[Clarify Node]

&nbsp;   B -- No --> D\[Research Brief]

&nbsp;   D --> E\[Supervisor]

&nbsp;   E --> F\[Final Report]



📸 Example Run

You: python

Assistant: 🤔 Can you please clarify your request?



You: what is python?

Assistant: 👌 Got it! Moving to research...

Assistant: 📝 Research brief created.

Assistant: 👨‍🏫 Supervisor approved the brief.

Assistant: ✅ Final research report generated!





