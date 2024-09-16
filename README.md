# Educational Tutor Chatbot

Welcome to the Educational Tutor Chatbot project! This notebook showcases a chatbot designed to assist with educational queries using the Llama 2 model and a QA dataset.

## Project Overview

The Educational Tutor chatbot aims to provide educational support by answering questions using a pre-defined QA dataset and, when necessary, generating responses with the Llama 2 model. The chatbot is capable of handling various questions, offering explanations, and updating its knowledge base as new questions are encountered.

### Key Features:
- **Question Answering:** Responds to user queries using a pre-existing dataset.
- **Dynamic Learning:** Utilizes the Llama 2 model to generate answers for questions not in the dataset.
- **Continuous Improvement:** Updates the QA dataset with new question-answer pairs as interactions occur.

### Google Colab Notebook Link:
[Google Colab Notebook](https://colab.research.google.com/drive/1gUsG4ZvqigVkMNOyT5XQ1xAwqw5heZJF?usp=sharing)

---

## Questions Requiring Assistance or Clarification

1. **"I'm having trouble understanding photosynthesis. Can you help?"**
2. **"Why is machine learning so complicated?"**

Feel free to ask these questions to see how the chatbot handles and responds to common educational queries.

---

### Installation and Setup

To run this notebook, ensure you have the following dependencies installed:

```bash
!pip install -q accelerate protobuf sentencepiece torch git+https://github.com/huggingface/transformers huggingface_hub gradio

