```
Last updated 02/20/26
```

# UVA Library Workshop on Python Programming with Local LLMs and Agentic AI

## About Me
* Erich Purpur: I am a Research Librarian for Science & Engineering in the Brown Science & Engineering Library. I've been at UVA since 2017.
* epurpur@virginia.edu

## Data Resources in the UVA Library
* [Research Data Services](https://data.library.virginia.edu/)
* [Workshop Series](https://data.library.virginia.edu/training/)

## Workshop Calendar

| Workshop | Date | Time |
| ---- | ---- | ---- |
| Intro to Python pt 1                                                |       Tuesday 1/20   |  3:00 - 4:30pm
| Intro to Python pt 2                                                |       Tuesday 1/27   |  3:00 - 4:30pm
| Python & APIs                                                       |       Tuesday 2/3    |  3:00 - 4:30pm
| Using Large Lanugage Models Locally                                 |       Tuesday 2/17   |  3:00 - 4:30pm
| Python & Local LLMs                                                 |       Tuesday 2/24   |  3:00 - 4:30pm

## Disclaimer
I am not an AI expert! We are all learning and navigating this confusing landscape together. 


# Background Information 
## Large Language Models
A Large Language Model (LLM) is an artificial intelligence algorithm that uses deep learning techniques and massive data sets to understand and create human-like content across various media types including text, images, video, etc. These models are trained on extensive datasets of diverse information. Using deep learning techniques, they recognize patterns and relationships within and between different forms of media.

In simpler terms, an LLM is a computer program that has been fed enough examples of human language that it can recognize and interpret human language and other forms of complex data. Many LLMs are trained on data that has been gathered from the internet and the quality of the samples impacts how well the LLM will learn natural language. 

There are many LLMs in existence such as OpenAI's high profile GPT (Generative Pre-Trained Transformer). Some are optimized for specific purposes, as we will learn more about today, while others are more general use. 

LLMs are composed of large files that contain the parameters and architecture defining the model. These can be several gigabytes in size. Once the model is downloaded, it may need to be configured for a specific task. 


## Why?

With services available like ChatGPT and Copilot, you might be wondering why would you want to run an LLM directly on your own machine? Well, there are many reasons but basically, using local LLMs gives you a level of control and customizability that you don't have otherwise. On top of that, one major use case is for privacy concerns. If you are working with sensitive data, interacting with it locally eliminates the worry it will be exposed to the internet. Other reasons to use local LLMs include (but are not limited to) free cost, offline use, and environmental reasons.


### Ollama

[Ollama](https://ollama.com/) is an open source project that serves as a powerful and user-friendly platform for running LLMs on your local computer. Ollama simplifies the process of downloading, installing, and interacting with a wide range of LLMs. See available models [here](https://github.com/ollama/ollama?tab=readme-ov-file#model-library). Ollama runs as a service on your local computer which you can interact with just like any other.


### Install Ollama LLMs
`ollama pull llama3.2`

`ollama pull phi3:3.8b`

`ollama pull gemma3:270m`
