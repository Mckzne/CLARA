# CLARA: Citation Literature Analysis & Reasoning Agent

## Overview
**CLARA** is an intelligent assistant built to simplify the process of academic research. In a world where thousands of papers are published daily, CLARA acts as a reasoning partner that identifies the most important literature and maps out a logical "reading path" for any complex topic. 

This project demonstrates expertise in **Agentic AI** and **Retrieval-Augmented Generation (RAG)**, specifically applied to the "AI for Science" domain.

## Core Features
* **Autonomous Research Planning:** Instead of a static list of links, CLARA uses a "Reason-Action" (ReAct) cycle to think through a topic and decide the best order of study.
* **Trust-Based Ranking:** The system uses a specialized **Graph Neural Network (GNN)** to rank papers based on their actual influence and citation history within the scientific community.
* **Logical Sequencing:** CLARA categorizes research into **Foundational**, **Methodology**, and **Application** stages, helping researchers build knowledge from the ground up.
* **Verified Sources:** Directly integrates with live research databases like the **arXiv API** to ensure all information is current and accurate.



## How it Helps
* **For Students:** Provides a clear starting point for new research areas, reducing "information overload".
* **For Faculty:** Acts as a rapid synthesis tool to stay updated on emerging methodologies and cross-domain applications.
* **For Administrators:** Demonstrates how agentic AI can be used to organize and enhance the accessibility of academic outputs.

## Technical Stack
* **Languages:** Python
* **Libraries:** PyTorch, LangChain
* **Architectures:** Graph Convolutional Networks (GCN), ReAct Architecture

# Install the necessary AI frameworks
pip install torch langchain pandas arxiv torch-geometric

# Launch the agent for a research query
python main.py --topic "3D Gaussian Splatting"
