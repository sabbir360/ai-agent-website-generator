# CrewaiWebsiteGen Crew

Welcome to the CrewaiWebsiteGen Crew project, powered by [crewAI](https://crewai.com). This template is designed to help you set up a multi-agent AI system with ease, leveraging the powerful and flexible framework provided by crewAI. Our goal is to enable your agents to collaborate effectively on complex tasks, maximizing their collective intelligence and capabilities.

## Installation

Ensure you have Python >=3.10 <=3.13 installed on your system. This project uses [UV](https://docs.astral.sh/uv/) for dependency management and package handling, offering a seamless setup and execution experience.

First, if you haven't already, install uv:

```bash
pip install uv
```

Next, navigate to your project directory and install the dependencies:

(Optional) Lock the dependencies and install them by using the CLI command:
```bash
crewai install
```
### Customizing
Rename `.env.sample` to `.env` and 
**Add your `OPENAI_API_KEY` into the `.env` file**

- Modify `src/crewai_website_gen/config/agents.yaml` to define your agents
- Modify `src/crewai_website_gen/config/tasks.yaml` to define your tasks
- Modify `src/crewai_website_gen/crew.py` to add your own logic, tools and specific args
- Modify `src/crewai_website_gen/main.py` to add custom inputs for your agents and tasks

## For Ollama
If you like to use Ollama based local model rather than OpenAI, you can use the following commands to run the project:
    ```MODEL=ollama/llama3.2:3b
    API_BASE=http://localhost:11434```

## Running the Project

To kickstart your crew of AI agents and begin task execution, run this from the root folder of your project:

```bash
$ crewai run
```

This command initializes the crewai_website_gen Crew, assembling the agents and assigning them tasks as defined in your configuration.

This example, unmodified, will run the create a `report.md` file with the output of a research on LLMs in the root folder.

## Understanding Your Crew

The crewai_website_gen Crew is composed of multiple AI agents, each with unique roles, goals, and tools. These agents collaborate on a series of tasks, defined in `config/tasks.yaml`, leveraging their collective skills to achieve complex objectives. The `config/agents.yaml` file outlines the capabilities and configurations of each agent in your crew.



### 🚀 Need Further Assistance?

I bring 10+ years of experience in AWS, Cloud Architecture, and backend development with Python, Golang or Frameworks like FastAPI, Django, and Flask.

📌 Expertise in: RAG, LLM, and AI Agents

If you need help, consulting, or want to collaborate, feel free to reach out!

📩 [Github](https://github.com/sabbir360)

