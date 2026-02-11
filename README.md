# AI News Summarizer (Agentic AI)

An end-to-end agentic AI application that fetches, summarizes, and persists AI-related news using a multi-node LangGraph workflow.

The system decomposes the task into specialized agents for news retrieval, structured LLM-based summarization, and report generation, enabling higher-quality outputs than single-pass LLM pipelines. It integrates tool-based web search (Tavily API), prompt-engineered summarization, and stateful execution, exposed through an interactive Streamlit UI.

Tech stack: LangGraph, LLMs, Tavily API, Streamlit, Python
Output: Structured Markdown summaries (daily / weekly / monthly)
