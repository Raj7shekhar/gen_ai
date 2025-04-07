This the generative ai CODE on chains.

## Summary of Python Files

* **conditional_chain.py**: This file demonstrates a conditional chain in Langchain. It classifies the sentiment of feedback text as positive or negative and then generates an appropriate response based on the sentiment. It uses `ChatOpenAI` for the main model, `PromptTemplate` for creating prompts, `PydanticOutputParser` for structured output, and `RunnableBranch` for conditional routing.

* **parallel_chain.py**: This file implements a parallel chain in Langchain. It processes a given text by simultaneously generating short notes and a question-answer quiz using different models (`ChatOpenAI` and `ChatAnthropic`). It then merges these outputs into a single document. It utilizes `RunnableParallel` for parallel execution and `StrOutputParser` for parsing string outputs.

* **sequential_chain.py**: This file showcases a sequential chain in Langchain. It generates a detailed report on a given topic and then creates a 5-point summary of the generated report. It uses `ChatOpenAI` as the language model and `StrOutputParser` for output parsing.

* **simple_chain.py**: This file presents a simple chain in Langchain. It generates 5 interesting facts about a given topic using `ChatOpenAI` and formats the output using `StrOutputParser`.
