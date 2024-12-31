**Multi AI Agent Framework**

This repository provides a Python implementation of a multi-agent framework using the Phi framework. The code integrates two specialized AI agents:

**Web Search Agent**: Utilizes DuckDuckGo for fetching information from the web.

**Finance AI Agent:** Leverages YFinanceTools to provide detailed financial data and insights.

A combined multi-agent, multi_ai_agent, coordinates these agents to offer comprehensive responses, blending web search and financial analysis capabilities.

# Code Overview

**Web Search Agent**
The Web Search Agent is designed to search the web for information using DuckDuckGo. It is configured with the following:

**Name:** Web Search Agent

**Role:** Fetches information from the web.

**Model:** llama3-groq-70b-8192-tool-use-preview

**Tools:** DuckDuckGo for web searches.

Instructions: Always include sources and display output in Markdown.


**Finance AI Agent**

The Finance AI Agent is configured to provide financial insights, including stock prices, analyst recommendations, fundamentals, and news.

**Name:** Finance AI Agent

**Model:** llama3-groq-70b-8192-tool-use-preview

**Tools:** YFinanceTools with features such as:

Stock prices

Analyst recommendations

Stock fundamentals

Company news

Instructions: Use tables to display data.

**Multi AI Agent**

The Multi AI Agent combines the functionality of the Web Search Agent and Finance AI Agent. It ensures seamless coordination for complex queries, with results presented in Markdown format.

# Features
Web Search: Fetch real-time information using DuckDuckGo.

Financial Insights: Retrieve and display stock data, analyst opinions, and company news in tabular format.

Seamless Coordination: Combines multiple agents for a comprehensive response.

User-Friendly Output: Results are presented in Markdown with tables and proper formatting.

# How It Works
Initialization: Each agent is initialized with a specific role, tools, and instructions.

Tool Utilization: The agents leverage their tools (e.g., DuckDuckGo for web search, YFinanceTools for financial data).

Multi-Agent Coordination: The multi_ai_agent delegates tasks to the appropriate agent based on the query.

Response Generation: Responses are formatted and displayed with Markdown, ensuring clarity and professional presentation.
