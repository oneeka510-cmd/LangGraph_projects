# LangChain Practice

These are basic examples to understand and practice LangChain (and LangGraph).

Each notebook focuses on a small concept — things like structured outputs, conditional routing, and building simple agent workflows — as I learn.

## Contents

- `7_conditional.ipynb` - Conditional routing with LangGraph: classifies a review's sentiment and routes it to either a thank-you response or a diagnosis + support response.

- `8_iterative.ipynb` Iterative Tweet Generator - This notebook demonstrates iterative generation, evaluation, and optimization of tweets using langgraph and langchain LLMs.

## Setup

1. Clone the repo
2. Create a virtual environment and activate it
3. Install dependencies:
   ```
   pip install langchain langchain-openai langgraph python-dotenv pydantic
   ```
4. Create a `.env` file with your OpenAI API key:
   ```
   OPENAI_API_KEY=your_key_here
   ```
5. Open the notebook in Jupyter and run the cells

## Note

This is a learning repo — code here is meant to be simple and explored step by step, not production-ready.
