# AgentsVille Trip Planner

An intelligent travel itinerary planning system built with AI agents that creates personalized travel plans for AgentsVille, considering weather conditions, traveler interests, budget constraints, and user feedback.

> 🎓 **Project from Udacity's Agentic AI Nanodegree**  
> Part of the [Agentic AI Nanodegree](https://www.udacity.com/course/agentic-ai--nd900) program, demonstrating practical applications of AI agent development.

## 🌟 Features

- **Intelligent Itinerary Planning**: Creates day-by-day travel plans using Chain-of-Thought reasoning
- **Weather-Aware Scheduling**: Automatically adjusts activities based on weather forecasts
- **Interest Matching**: Tailors activities to individual traveler preferences
- **Budget Management**: Ensures all recommendations stay within specified budget limits
- **Iterative Refinement**: Uses ReAct (Reasoning and Acting) agents to improve plans based on feedback
- **Comprehensive Evaluation**: Multiple validation checks ensure high-quality itineraries

## 🏗️ How It Works

The system uses AI agents to create and refine travel itineraries automatically.

## 📋 Requirements

- Python 3.8+
- OpenAI API key

## 🚀 Getting Started

1. **Setup Environment**
   ```bash
   # Set your OpenAI API key
   export OPENAI_API_KEY="your-api-key-here"
   ```

2. **Run the Notebook**
   ```bash
   jupyter notebook project_starter.ipynb
   ```

3. **Follow the Workflow**
   - Define vacation information (travelers, dates, budget, destination)
   - Generate initial itinerary
   - Provide feedback for improvements
   - Get refined travel plan

## 🔍 What It Does

- Creates personalized travel itineraries
- Considers weather, budget, and interests
- Validates and improves plans automatically
- Handles feedback and refinements

## 📁 Files

- `project_starter.ipynb` - Main notebook
- `project_lib.py` - Core utilities
- `README.md` - This file
