# Question Generation Using NLP

This project focuses on Automatic Question Generation (AQG), leveraging state-of-the-art Natural Language Processing (NLP) techniques. The model generates high-quality questions from any provided PDF document in various formats, including:

- #### Fill-in-the-blanks
- #### Multiple-choice questions (MCQs)
- #### Long-answer questions
***
## Features

- Upload PDF, DOCX, or TXT files for question generation.
- Generate questions tailored to the provided context with specific user instructions.
- Supports scalable question generation using Transformer-based models and Retrieval-Augmented Generation (RAG) pipelines.

***
## Getting Started
Just run the following notebook:- https://colab.research.google.com/drive/1oF5LAHUK1kRVYxqOVLWmgif_XaXHSDO_#scrollTo=kuPehzjdGjeN
***
## Architecture
### Solution 1: Transformer Fine-Tuning
- Used a pre-trained T5-small model fine-tuned on the SQuAD dataset for short-answer question generation.
- Highlights the utility of fine-tuning to enhance task-specific expertise in models.
### Solution 2: RAG Pipeline
- Utilized Phi-3.5-mini-instruct, a 3.5-billion parameter model, combined with a FAISS vector database.
- Enables scalable, knowledge-intensive question generation by ingesting entire documents.
***
## Future Work
#### Domain-Specific Fine-Tuning:
- Fine-tune the model for academic disciplines like mathematics, engineering, or medical science to enhance domain-specific question quality.
#### Enhanced User Interface:
- Develop an intuitive and interactive front-end to improve accessibility and user experience.
#### Support for Additional Formats:

- Extend support for documents like scanned PDFs through OCR and handwritten notes for broader usability.
#### Saving and Sharing Outputs:

- Allow users to save, download, and share generated questions, enabling collaborative workflows.
#### Deployment and Scalability:

- Deploy the solution as a web or cloud-based service to support real-time, large-scale use cases in education and corporate training.
***
By addressing these future directions, the project has the potential to become a comprehensive tool for automating question generation, enhancing the learning and evaluation experience for a wide range of users.
