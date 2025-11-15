# Anime Recommendation Agent

This repository contains the Kaggle Capstone Project for the **AI Agents Intensive** by Google. The **Anime Recommendation Agent** is a multi-agent system that recommends anime based on genres, preferences, and trending lists. The project leverages the Google Agent Development Kit (ADK) to build intelligent agents that can autonomously recommend anime to users.

## Project Overview

The Anime Recommendation Agent is built using a multi-agent system to suggest anime from various genres like action, adventure, comedy, fantasy, etc. It includes:
- **Data collection**: Collects and filters anime based on genre preferences.
- **Recommendation system**: Suggests anime based on user inputs.
- **Learning capability**: Agents can adapt and suggest based on current trends.

## Problem Statement

Finding good anime to watch can be overwhelming for users due to the sheer number of anime titles available across platforms. With ever-increasing choices, users often struggle to find anime that fits their preferences or genres of interest. A recommendation system can help automate and personalize the anime discovery process, saving time and effort for users.

## Solution

The **Anime Recommendation Agent** utilizes AI agents to automate the process of recommending anime. By leveraging a multi-agent architecture, the agent collects relevant data from different sources, processes it, and delivers suggestions to the user. This can improve user experience and streamline the anime discovery process.

## Key Concepts Demonstrated

1. **Multi-agent system**: The project employs a network of agents to gather data, process it, and return recommendations.
2. **Agent communication**: Agents work together to collect data and determine the best recommendations.
3. **Tool usage**: The agents are equipped with tools such as the Google Search tool to fetch trending anime and generate recommendations.
4. **Sequential agents**: Multiple agents execute tasks in sequence, such as fetching data, processing it, and delivering the output to the user.
5. **Long-term memory**: Agents can store user preferences and adapt to their needs over time.

## Architecture

The project is based on a modular architecture, with agents responsible for different stages of the recommendation process. Below is the overview of the agents involved:

- **Data Collector Agent**: Gathers data about anime from external APIs and databases.
- **Recommendation Agent**: Uses the data to provide recommendations based on user preferences.
- **User Preference Agent**: Tracks user inputs and modifies recommendations accordingly.

## How to Run the Code

1. Open the notebook on **Kaggle** or **Google Colab**.
2. Execute all the code cells in the notebook.

Alternatively, if you're running the project locally, install the required dependencies using:

```bash
pip install -r requirements.txt
 and then run python anime_recommendation_agent.py
