# Medical Assistant Chatbot

A professional, modular multi-agent medical assistant chatbot built with Python and CrewAI. This system collects user symptoms and provides actionable advice across various medical wellness categories.

## Features

- Extracts symptoms from free-text user input
- Classifies symptoms into medical categories
- Routes each category to a specialized agent
- Returns a combined treatment summary

## Architecture

The system uses a multi-agent approach with the following specialists:

- Symptom Extractor: Extracts symptoms from unstructured text
- Condition Classifier: Classifies symptoms into medical categories
- Fatigue Specialist: Provides advice for energy management, sleep, and stress
- Gut Health Specialist: Offers gut-related suggestions
- Inflammation Expert: Recommends anti-inflammatory strategies
- Supplement Advisor: Suggests helpful supplements
- Weight Loss Coach: Helps with sustainable weight loss
- Hormone Balance Expert: Addresses hormonal imbalances
- Summary Agent: Aggregates responses into a final report

## Setup

1. Clone this repository
2. Install the required dependencies:

```bash
pip install crewai langchain-openai
