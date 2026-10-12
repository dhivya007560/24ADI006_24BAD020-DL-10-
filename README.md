# 24ADI006_24BAD020-DL-10

# EduBot AI – Your Learning Assistant 🤖

## Project Description

EduBot AI is a Python-based chatbot developed using Gradio and a pretrained language model. It is designed to answer questions related to Artificial Intelligence, Machine Learning, and general knowledge.

## What I Implemented

- Created a `knowledge_base` dictionary containing predefined questions and answers about Artificial Intelligence, Machine Learning, Deep Learning, NLP, chatbots, LLMs, Generative AI, neural networks, and other AI concepts.
- Implemented a `generate_response()` function to process user questions and generate appropriate responses.
- Added input validation to handle empty messages.
- Used text normalization to convert questions to lowercase, remove punctuation at the end, and standardize spaces before matching them with the knowledge base.
- Implemented predefined responses for known questions.
- Integrated a pretrained language model using Hugging Face Transformers to generate answers for questions that are not available in the knowledge base.
- Used PyTorch to generate model outputs and decode them into readable text.
- Created a web interface using Gradio with a question input box, answer output box, project title, description, and example questions.
- Launched the chatbot using `demo.launch(share=True)` to provide a local interface and request a shareable demo link.

## How It Works

1. The user enters a question in the Gradio interface.
2. The chatbot checks whether the input is empty.
3. The question is normalized before matching.
4. If the question exists in the knowledge base, its predefined answer is returned.
5. If no predefined answer matches, the question is passed to the pretrained language model.
6. The generated answer is displayed in the Gradio output box.

## Technologies Used

- Python
- Gradio
- Hugging Face Transformers
- PyTorch
- Pretrained language model

## Example Questions

- What is Artificial Intelligence?
- What is Machine Learning?
- What is Deep Learning?
- What is Natural Language Processing?
- What is a chatbot?
- What is Generative AI?
- What is prompt engineering?

## Outcome

Developed a web-based chatbot that retrieves predefined answers for supported AI-related questions and uses a pretrained language model to generate responses to other questions.

## Author

**Dhivya A**  
**Roll No:** 24BAD020
