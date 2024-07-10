# CrewAI AI NewsLetter

## Installation
To get started with the CrewAI Hierarchical Tutorial, clone the repository and install the necessary dependencies.

```
git clone "https://github.com/AliZaiN-157/CrewAI-AINewsLetter.git"
cd into the folder
pip install -r requirements.txt
```

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

