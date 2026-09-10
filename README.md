# Agentic AI & Chatbot Projects

A collection of AI projects demonstrating the difference between a traditional **AI Chatbot** and an **Agentic AI system** capable of using specialized agents and external tools to perform tasks.

This project focuses on building practical AI applications using Python, Large Language Models (LLMs), and agent-based workflows.

---

##  Project Overview

This repository contains two major AI applications:

### 1.  AI Chatbot

The first project is a conversational AI chatbot designed to interact with users through natural language.

The chatbot accepts user questions and generates responses using an AI language model. It demonstrates the basic working principle of a conversational AI system.

### 2.  Agentic AI Multi-Agent System

The second project demonstrates an **Agentic AI architecture**.

Unlike a traditional chatbot that primarily generates responses, an agentic system can:

- Understand the user's objective
- Decide what action needs to be performed
- Select an appropriate agent or tool
- Retrieve external information
- Process the retrieved information
- Generate a final response for the user

The system contains multiple specialized agents.

---

# Agent Architecture

The Agentic AI system currently consists of two agents.


                          User
                           |
                           v
                  Agentic AI System
                           |
              +------------+------------+
              |                         |
              v                         v
      DuckDuckGo Agent        Second Agent
              |                         |
              v                         v
       Web Information            Specialized
         Retrieval                 Task/Tool
              |                         |
              +------------+------------+
                           |
                           v
                    AI Processing
                           |
                           v
                     💬 Final Answer
