## Table of Contents

| Section | File |
|---------|------|
| Agents, Structured Output, Tools | [agents.ipynb](agents.ipynb) |
| Handoffs | [handoffs.ipynb](handoffs.ipynb) |
| Traces | [traces.ipynb](traces.ipynb) |
| Streaming | [streaming.ipynb](streaming.ipynb) |
| Streaming Demo | [streaming_demo.ipynb](apps/streaming_demo.ipynb) |
| Guardrails | [guardrails.ipynb](guardrails.ipynb) |
| Multi-turn Conversations | [multiturn_convo.ipynb](multiturn_convo.ipynb) |
| Context Management | [context.ipynb](context.ipynb) |
| Visualizing | [visualizing.ipynb](visualizing.ipynb) |
| Deep Research Project | [Deep Research Project](projects/deep_research/) |


## Setup Instructions

### 1. Prerequisites
- Python 3.11 or higher
- pip (Python package installer)

### 2. Create a Virtual Environment
First, create a new virtual environment in the project directory:
```bash
python -m venv venv
```

### 3. Activate the Virtual Environment
on Linux/Mac:
```bash
source venv/bin/activate
```

on Windows:
```bash
venv\Scripts\activate
```

### 4. Installing new packages
```bash
pip install package_name
```

if you want to install all the packages in the requirements.txt file, you can use the following command:
```bash
pip install -r requirements.txt
```

### 5. Saving the requirements.txt file
```bash
pip freeze > requirements.txt
```