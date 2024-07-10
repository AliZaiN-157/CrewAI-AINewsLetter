# <h1 align="center">💻 CrewAI AI NewsLetter </h1>

## Installation
To get started with the CrewAI , clone the repository and install the necessary dependencies.

## 💻 Running Locally

1. Clone the repository📂
```
git clone "https://github.com/AliZaiN-157/CrewAI-AINewsLetter.git" 
```

2. Install dependencies with [Poetry](https://python-poetry.org/) and activate virtual environment🔨

```bash
poetry install
poetry shell
```

<center>
<img src="./crewAI.jpeg" >
</center>


## Usage
To run the CrewAI tutorial, execute the main script after setting up your environment variables and configuration.

``` 
python main.py
```

## Structure
main.py: The entry point script that initializes the agents and tasks, and forms the AI crew.

agents.py: Defines various agents like the editor, news fetcher, news analyzer, and newsletter compiler.

tasks.py: Contains the task definitions that are used by the agents to perform specific operations.

file_io.py: Manages file input/output operations, crucial for handling the async flow of data.

