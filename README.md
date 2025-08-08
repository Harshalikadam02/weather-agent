# 🌤️ Weather Agent — Intelligent AI Weather Assistant

This is **not your average weather bot**.  
The real power lies in the **system prompt** that I’ve engineered turning a simple chatbot into an **AI agent** that explains **what it’s doing, why it’s doing it, and how it’s thinking**.

Instead of just giving you a one-line weather update, it walks you through:
1. Understanding your request
2. Planning the steps
3. Deciding which tool to use
4. Executing the action via API call
5. Observing the result
6. Presenting the final answer

---

## 🚀 Features
- **System Prompt Engineering** — Defines the AI’s personality, reasoning process, and step-by-step approach.
- **Function Calling via API** — Uses `requests` to call the weather API and return live data.
- **Reasoning Transparency** — The agent doesn’t just give an answer — it tells you how it arrived there.
- **Modular Tooling** — Easily extendable to include more tools beyond weather.

---

## 🛠️ How It Works
1. **User Query** → You ask: *"What’s the weather in New York?"*
2. **Plan** → The agent decides it needs to fetch weather data.
3. **Action** → Calls the `get_weather()` function.
4. **Observation** → Processes the weather API result.
5. **Output** → Returns both the reasoning and the final weather report.

💡 Why This is Special
Most chatbots are reactive they answer and stop.
This agent is proactive & transparent:
It reveals its reasoning
It follows a structured decision-making process
It is powered by prompt engineering for better control


## 📊 Agent Workflow Diagram
![Agent Workflow](https://github.com/Harshalikadam02/weather-agent/blob/main/agent%20flow.png)
Made with ❤️ by Harshali Kadam
Bringing intelligence and transparency to AI-powered assistants.


📦 Installation guide
git clone https://github.com/Harshalikadam02/weather-agent.git
cd weather-agent
pip install -r requirements.txt
Environment Variables
Create a .env file:
OPENAI_API_KEY=your_openai_api_key_here
▶Run the Agent
python weather_agent.py
