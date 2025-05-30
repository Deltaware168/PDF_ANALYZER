# PDF Analyzer con RAG

Esta es una aplicación web sencilla construida con Streamlit que utiliza la técnica RAG (Retrieval-Augmented Generation) para analizar el contenido de archivos PDF y responder preguntas basadas exclusivamente en su información. Los documentos son divididos en fragmentos, vectorizados con embeddings de OpenAI, almacenados en FAISS, y luego consultados mediante un LLM que responde usando únicamente el contexto relevante recuperado.  Esta herramienta resulta especialmente útil para resumir o comprender documentos extensos sin necesidad de leerlos en su totalidad, así como para realizar consultas específicas sobre su contenido. Para usarla, solo necesitas una API key de OpenAI y un archivo PDF.



![image](https://github.com/user-attachments/assets/bf221c9f-c33d-45e5-bdb1-196291c7aed7)
