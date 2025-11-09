# content-summarization-Gen-AI-App
YouTube video and website url content summarization

Content Summarization Gen Al App
This application summarizes content from YouTube videos and web articles using LangChain and Groq
LLMs.
It extracts text (or video transcripts), sends the content to the Gemma-7B-It model hosted on Groq, and
generates a clean, readable summary.

Built using Streamlit to provide a simple, user-friendly web interface.

Features
. Summarize YouTube video transcripts
. Summarize any website / blog article
. Uses Groq LLM (Gemma-7B-It) for fast inference
. Clean, minimal, one-page Streamlit UI
. Simple prompt-based summarization with LangChain

#Tech Stack

Streamlit - Web UI framework

LangChain - LLM prompt + chaining framework

ChatGroq (Groq API) - High-speed model inference

YoutubeLoader - Extracts YouTube transcript text

UnstructuredURLLoader - Extracts readable text from website pages

