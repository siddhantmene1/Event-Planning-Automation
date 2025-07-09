# Event-Planning-Automation
Using AI Agents to automate Event planning tasks

# Event Management Crew using CrewAI

This repository demonstrates the implementation of an **AI-driven multi-agent system** to coordinate all aspects of event planning, from venue scouting to logistics to marketing using the [CrewAI](https://github.com/joaomdmoura/crewAI) framework.

## Project Overview

This project demos automating key components of event management through specialized AI agents. Each agent performs a distinct task using web search and scraping tools, driven by natural language task descriptions and structured outputs.

### Agents:
- **Venue Coordinator** – Identifies and recommends suitable venues.
- **Logistics Manager** – Arranges catering and equipment setup.
- **Marketing & Communications Agent** – Promotes the event and drives attendee engagement.

## Technologies & Tools

- **Python**
- **CrewAI** (multi-agent orchestration)
- **Pydantic** (data validation)
- **SerperDevTool** – Web search API
- **ScrapeWebsiteTool** – Website content extraction


## How It Works

1. **Initialize Tools:** Load web search and scraping tools.
2. **Define Agents:** Set roles, goals, and backstories for each agent.
3. **Create Tasks:** Assign tasks with input placeholders and expected outputs (JSON/Markdown).
4. **Run Crew:** Execute all tasks with human feedback enabled where needed.
5. **Review Outputs:** Outputs are saved as files (`venue_details.json`, `marketing_report.md`).





