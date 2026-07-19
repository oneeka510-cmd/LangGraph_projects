# LangGraph Practice

<img width="292" height="372" alt="image" src="https://github.com/user-attachments/assets/97eb0809-3287-4693-8178-d61bd13b872c" />

<img width="390" height="432" alt="image" src="https://github.com/user-attachments/assets/bc877841-c139-4e65-b3b0-5e2545942f42" />

<img width="591" height="333" alt="image" src="https://github.com/user-attachments/assets/30f7b3cd-b5f0-4084-bd44-3fe1f155da91" />

These are basic examples to understand and practice LangChain (and LangGraph).

Each notebook focuses on a small concept — things like structured outputs, conditional routing, and building simple agent workflows — as I learn.

## Contents

- `8_iterative.ipynb`  Iterative Tweet Generator : This notebook demonstrates iterative generation, evaluation, and optimization of tweets using langgraph and langchain LLMs.

- `7_conditional.ipynb`  Conditional routing with LangGraph: classifies a review's sentiment and routes it to either a thank-you response or a diagnosis + support response.

- `5_parallel2.ipynb`  Parallel Workflow: This notebook demonstrates a parallel workflow. We are evaluating an essay on different parameters.


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
