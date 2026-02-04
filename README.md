
# CrewAI Blog Generator with Google Gemini

An AI-powered content creation system using CrewAI framework and Google's Gemini 3 Flash model. This project demonstrates multi-agent collaboration where AI agents work together to research and write blog posts.

## What This Does

This project uses two AI agents that work sequentially:
1. **Senior Research Analyst** - Conducts comprehensive research on AI advancements
2. **Tech Content Strategist** - Transforms research into engaging blog posts

## Prerequisites

- Python 3.8+
- Google AI Studio API Key ([Get one here](https://aistudio.google.com/app/apikey))

## Installation

1. **Clone the repository**
```bash
cd CrewAI_Gemini-AI-Agent
```

2. **Create a `.env` file** in the project root directory:
```
GOOGLE_API_KEY=your_google_api_key_here
```
Replace `your_google_api_key_here` with your actual API key from Google AI Studio

3. **Run the script**:
```bash
python CrewAI_Gemini-AI-Agent/agent_crewai.py
```

The agents will:
1. Research latest AI advancements in 2024
2. Generate a comprehensive analysis report
3. Write an engaging blog post based on the research
4. Output the final blog post to the console

### Task Flow

```
Task 1 (Researcher) → Comprehensive AI Analysis Report
                              ↓
Task 2 (Writer) → Engaging Blog Post (4+ paragraphs)
```

### Technologies Used

- **CrewAI** - Multi-agent orchestration framework
- **Google Gemini 3 Flash** - LLM for agent intelligence
- **LangChain** - Integration layer
- **Python-dotenv** - Environment variable management
