# Nepali Health-QA System

## Overview

The Nepali Health-QA System is a question-answering system designed to provide accurate and relevant health information in the Nepali language. Leveraging state-of-the-art natural language processing techniques, this system allows users to pose health-related questions in Nepali and receive concise and informative answers in real-time.

## Features

- **Question-Answering**: Users can input health-related questions in Nepali, and the system retrieves the most relevant answers from a pre-defined database of health facts.
  
- **NLP-based Encoding**: Utilizes the Sentence Transformers library to encode Nepali text into dense embeddings, enabling efficient similarity search.

- **Fast and Scalable Retrieval**: Integration with Pinecone enables fast and scalable similarity search, ensuring real-time retrieval of relevant health information.

## How It Works

1. **Input Question**: Users input their health-related questions in Nepali.
2. **Embedding Generation**: The system encodes the question into a dense vector representation using the Sentence Transformers library.
3. **Similarity Search**: The encoded vector is compared against a database of pre-embedded health facts using Pinecone's similarity search functionality.
4. **Answer Retrieval**: The system retrieves the most relevant health facts based on vector similarity and presents them to the user as answers to their queries.

## Setup and Installation

1. **Clone the Repository**: `git clone https://github.com/chhabii/Enhancing-NepaliHealth-QA-Systems-with-RAG.git`
2. **Install Dependencies**
3. **Execute the `queryVectorDatabase.ipynb` file**

## Usage

1. **Input Questions**: Enter your health-related questions in Nepali.
2. **Receive Answers**: The system will display the most relevant health facts corresponding to your query.

## Sample Queries and Results

- **Query**: "मलाई यो निरन्तर हाछ्युँ र नाक बगिरहेको छ। के यो सामान्य चिसो हुन सक्छ, कुनै सल्लाह?	"
  
  **Result**: "चिसो लक्षणहरूमा अक्सर लगातार हाच्छ्युँ गर्नु र नाक बग्नु समावेश छ। राम्रो महसुस गर्न: पानी, सूप र तातो चियाले हाइड्रेटेड रहनुहोस्। आराम गर्नुहोस् र पर्याप्त सुत्नुहोस्। रुघाखोकीको औषधि लिनुहोस्"


## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [Sentence Transformers](https://www.sbert.net/docs/pretrained_models.html)
- [Pinecone](https://www.pinecone.io/)
- [Nepali Health Fact Dataset](https://huggingface.co/datasets/NepaliAI/Nepali-Health-Fact?row=1)
