## ScholarsDock
A local-only, privacy-focused RAG (Retrieval-Augmented Generation) assistant that enables secure interaction with documents using Streamlit, Ollama, and FAISS.

## About
ScholarsDock is designed to provide a secure and efficient way to query and interact with various document formats completely offline. By leveraging the power of local LLMs via Ollama and efficient vector search with FAISS, it ensures that your sensitive data never leaves your machine. Users can upload PDFs, DOCX, or TXT files and ask questions to get accurate, context-aware responses, making it an ideal tool for researchers, students, and professionals handling private documents.

## Features
- *Local Execution*: Runs entirely on your local machine with no external API calls, ensuring maximum privacy.
- *Document Support*: Seamlessly processes PDF, DOCX, and TXT files.
- *Context-Aware Answers*: Uses RAG (Retrieval-Augmented Generation) to provide accurate answers based on document content.
- *Source Citations*: Every response includes references to the specific source documents and text chunks.
- *Strict Mode*: Toggleable option to force the AI to answer only based on the provided documents.
- *Persistent Storage*: Vector embeddings are saved locally, so you don't have to re-process documents every time.

## Requirements
To run this project, you need the following:

- Python 3.10+ installed on your system.
- Ollama: You must have Ollama installed and running.
- LLM Model: Pull the required model using the command: ollama pull qwen2.5
- Python Dependencies:
    streamlit
    ollama
    faiss-cpu
    sentence-transformers
    langchain-text-splitters
    pypdf
    python-docx

## System Architecture
<!--Embed the system architecture diagram as shown below-->

![Screenshot 2023-11-25 133637](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/a60c11f3-0a11-47fb-ac89-755d5f45c995)


## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Name of the output

![Screenshot 2023-11-25 134037](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/8c2b6b5c-5ed2-4ec4-b18e-5b6625402c16)

#### Output2 - Name of the output
![Screenshot 2023-11-25 134253](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/5e05c981-05ca-4aaa-aea2-d918dcf25cb7)

Detection Accuracy: 96.7%
Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact
<!--Give the results and impact as shown below-->
The Sign Language Detection System enhances accessibility for individuals with hearing and speech impairments, providing a valuable tool for inclusive communication. The project's integration of computer vision and deep learning showcases its potential for intuitive and interactive human-computer interaction.

This project serves as a foundation for future developments in assistive technologies and contributes to creating a more inclusive and accessible digital environment.

## Articles published / References
1. N. S. Gupta, S. K. Rout, S. Barik, R. R. Kalangi, and B. Swampa, “Enhancing Heart Disease Prediction Accuracy Through Hybrid Machine Learning Methods ”, EAI Endorsed Trans IoT, vol. 10, Mar. 2024.
2. A. A. BIN ZAINUDDIN, “Enhancing IoT Security: A Synergy of Machine Learning, Artificial Intelligence, and Blockchain”, Data Science Insights, vol. 2, no. 1, Feb. 2024.




