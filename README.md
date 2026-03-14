
# AI Browser Agent

## Project Overview
The AI Browser Agent is an automation system that allows users to perform web tasks using natural language instructions. Instead of manually searching on Google or navigating through multiple websites, users can simply type a command, and the AI agent will automatically execute the task.

The agent interacts with a browser, performs searches, collects information, and presents the most relevant and accurate results. This helps reduce manual effort and improves productivity by automating repetitive browsing tasks.

This project demonstrates how artificial intelligence and browser automation can work together to simplify information retrieval and task management.

## Features
- Natural language task input
- Automated browser navigation
- Fast and accurate search results
- Reduces manual searching effort
- Hands-free task execution
- Web-based user interface
- Supports AI-powered research tasks

## How the AI Agent Works
1. The user enters a task or search query.
2. The AI agent interprets the instruction.
3. The system opens a browser automatically.
4. The agent navigates to Google or other websites.
5. The agent performs the search and collects results.
6. The final answer is displayed in the WebUI.

Example instruction:
```

Go to google.com and search for the founder of Instagram

```

The agent will automatically open the browser, perform the search, and return the result.

## Tech Stack

### Programming Language
- Python

### Browser Automation
- Playwright
- Browser-Use

### Interface
- Web UI

### AI Integration
- Large Language Models (LLMs)

## Project Structure
```

Ai-Agent
│
├── webui.py
├── requirements.txt
├── agent/
├── config/
├── recordings/
└── README.md

```

## Installation and Setup

### Step 1: Clone the Repository
```

git clone https://github.com/HarithaNetha8/Ai-Agent.git
```

### Step 2: Navigate to the Project Folder
```

cd Ai-Agent

```

### Step 3: Create a Virtual Environment
```

python -m venv venv

```

### Step 4: Activate the Virtual Environment

Windows:
```

venv\Scripts\activate

```

Mac/Linux:
```

source venv/bin/activate

```

### Step 5: Install Dependencies
```

pip install -r requirements.txt

```

### Step 6: Run the Application
```

python webui.py

```

### Step 7: Open the Web Interface
Open your browser and go to:

```

[http://127.0.0.1:7788](http://127.0.0.1:7788)

```

You can now enter instructions and let the AI agent perform the task automatically.

## Example Tasks
- Search information on Google
- Navigate to websites automatically
- Perform research tasks
- Collect and display information

Example:
```

Search for the founder of Instagram

```

## Benefits
- Saves time during web research
- Automates repetitive browsing tasks
- Improves productivity
- Provides quick and structured results

## Future Improvements
- Support for more AI models
- Integration with APIs
- Advanced research capabilities
- Improved UI and result visualization

## Author
Haritha Netha  
B.Tech Student  
Aspiring Data Analyst  

GitHub Profile  
https://github.com/HarithaNetha8
