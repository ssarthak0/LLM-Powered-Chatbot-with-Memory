# LLM-Powered-Chatbot-with-Memory

This project demonstrates how to build an LLM-powered chatbot using LangChain and the GROQ API with Gemma2-9b. 
It supports conversational memory using `RunnableWithMessageHistory` and `ChatMessageHistory` for stateful interactions. 
The chatbot is enhanced with prompt templates including system instructions and supports multilingual responses via dynamic prompt variables. 
A session-based approach ensures personalized conversations.
We also introduce message trimming with `trim_messages` to manage context window limitations efficiently. 
Input customization is handled with `ChatPromptTemplate` and token-aware history management. 
This foundation can be extended to Conversational RAG or Agent-based actions for advanced use cases.
