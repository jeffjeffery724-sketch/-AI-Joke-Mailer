# -AI-Joke-Mailer
This project is a simple AI automation workflow that sends a fresh, AI-generated joke to your email whenever a trigger fires.
To avoid repeating the same joke twice, the system stores each generated joke in a spreadsheet and checks it before sending a new one.

It’s a fun and basic demonstration of:

AI agents
Memory handling
Automated email delivery
Duplicate-prevention using a spreadsheet

Perfect as a starter automation project or playful use of AI tools.

⚙️ How It Works
1. Trigger

A scheduled or manual trigger starts the workflow.

2. AI Agent

The AI Agent generates a new joke using an OpenAI model.
It also interacts with a Simple Memory module that keeps track of previously used jokes.

3. Append or Update Row in Sheet

The newly generated joke is stored in a spreadsheet (Excel or Google Sheets).
This log prevents the system from repeating any joke in the future.

4. Condition Check
If the joke is new, the workflow proceeds.
If the joke is a duplicate, the workflow stops.
5. Email Sending

A Gmail module sends the joke directly to your inbox.

6. No Operation

If the joke was already used before, the workflow ends without sending anything.

🧠 Key Features
AI-generated jokes
Automatic email sending
Spreadsheet memory to avoid duplicates
Lightweight and beginner-friendly
Fully modular workflow
📁 Included Components
Automation workflow
AI Agent configuration
Spreadsheet storage logic
Email sending setup
Documentation
🚀 Getting Started
Clone the repository.
Set up your automation environment (Make, Zapier, n8n, etc.).
Configure:
OpenAI API key
Email provider (Gmail)
Spreadsheet file/location
Run the trigger and start receiving fresh jokes in your inbox.
📬 Example Output
Why don’t programmers like nature?
It has too many bugs.

This joke is then saved to the spreadsheet to prevent future repetition.

🤝 Contributing

Feel free to submit issues, ideas, or improvements via pull requests.

📜 License

MIT License.
