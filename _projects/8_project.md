---
layout: page
title: Prompt Response Logging System
description: The GPT Prompt Logging and Analysis App uses Nest.js as backend technology and Streamlit for frontend to log prompts to GPT models, offering real-time response display, detailed statistics, and visual analytics for prompt interactions.
img: assets/img/project_8.png
importance: 8
category: Software Engineering
---

I created this project as a personal endeavor to learn Nest.js and Streamlit. Learning Nest.js and Streamlit enables efficient development of robust backend APIs and interactive frontend applications, empowering seamless data management, scalable architecture, and intuitive user interfaces for modern web applications. The backend code for this project can be found [here](https://github.com/samyakmehta28/PromptLoggingSystem-backend) and the frontend code can be found [here](https://github.com/samyakmehta28/PromptLoggingSystem-frontend).

# Prompt Response Logging System with Metrics

### Overview:

The Prompt Response Logging System is a comprehensive backend application developed using TypeScript and NestJS, designed to log and analyze interactions with OpenAI's language models. The system features a proxy layer for request routing, data logging in ClickHouse (mySQL), and a dashboard for visualizing metrics and statistics.

### Introduction:

This project addresses the need for a robust system to track and analyze prompts and responses when interacting with large language models. By creating a proxy layer, the system enables detailed logging and metrics collection without modifying existing integration points. The use of ClickHouse for data storage allows for efficient querying and analysis of large volumes of interaction data.

### Functionalities:

- Proxy Layer:

  - Forwards requests to OpenAI and returns responses to the caller
  - Logs request details to ClickHouse database
  - Captures metadata such as token count, response latency, and custom key-value pairs

- Backend Server (NestJS):

  - API for handling user queries and returning OpenAI responses
  - API for retrieving logged requests based on filters
  - API for aggregating metrics (e.g., daily request count, average latency)

- ClickHouse Database:

  - Stores detailed logs of each request and response
  - Enables efficient querying for analytics and dashboard population

- Dashboard:

  - Displays sample requests filtered by model type and metadata fields
  - Shows total counts of input tokens, output tokens, and requests
  - Graphs requests per second, latency, and failures over various time periods

- User Interface:

  - Simple interface for submitting prompts and receiving responses
  - Integrated with the dashboard for real-time updates

### Conclusion:

The Prompt Response Logging System provides a powerful tool for monitoring and analyzing interactions with AI language models. By offering detailed logging, efficient querying, and insightful visualizations, the system enables users to optimize their use of AI models and gain valuable insights into usage patterns and performance metrics.
