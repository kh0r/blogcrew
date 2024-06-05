# BlogCrew

This project can create blogposts. Inspired by [this post on medium](https://medium.com/the-ai-forum/create-a-blog-writer-multi-agent-system-using-crewai-and-ollama-f47654a5e1cd)

## Setup

### ollama

- [install ollama](https://ollama.com)

```bash
  ollama create crewai-llama3 -f ./Modelfile
```

### python

```bash
pipenv install
```

## Run

```bash
pipenv run python main.py -t "How to generate blogposts using CrewAI and Ollama"
```
