# Weather-AI-Agent-and-The-Daily-Dish-customer-service-chatbot
 Weather AI Agent and The Daily Dish customer-service chatbot. In this hands-on project, you’ll apply core agentic AI principles to solve practical problems, design and orchestrate multi-agent systems, integrate external tools, memory, and document-based knowledge sources, and implement intelligent routing between specialized agents.
This lab is ideal for software engineers and machine learning engineers who want to understand how AI agents work under the hood and learn how to build agent-based systems from first principles using Python.

Objectives
By the end of this lab, learners will be able to:

Understand the core concepts of AI Agents and Multi-Agent Systems (MAS).

Build a Weather AI Agent from scratch to retrieve and process external data using an API.

Develop a customer-service chatbot for The Daily Dish using a PDF-based knowledge source.

Implement agent memory to retain context and enable more personalized interactions.

Design and integrate a multi-agent architecture where specialized agents collaborate to solve real-world problems.

Table of Content
Setup and Prerequisites
AI Agents
MemoryAgent
Weather Agent
The Daily Dish Agent
Routing Queries
Chatbot Function: Process User Queries
Project Overview:
In this hands-on project, you will build AI agents from scratch and use them to power real-world applications such as:

A Weather AI Agent that retrieves and reports real-time weather data.

A Daily Dish customer-service chatbot that answers questions about reservations, location, and menu from a PDF knowledge source.

Explanation of Flow

User Question: The user sends a query.

QueryRouter: Determines the correct agent to handle the question.

WeatherAgent / DailyDishAgent: Process the question:

    - WeatherAgent fetches live API data.

    - DailyDishAgent searches the PDF knowledge base.
MemoryAgent: Both agents can store new info or recall previous context for smarter answers.

Response to User: The chosen agent sends back the final answer, optionally using context from MemoryAgent.
