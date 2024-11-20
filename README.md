# Projects 4 Streamlit

Explore the projects presented as Jupyter Notebooks, which I used to build my Streamlit portfolio webpage.

## Plant Disease Classifier
In this project, I applied **transfer learning** to train the **Plant Village** dataset for plant disease classification.

The model uses the **ResNetv2 CNN** architecture, with **TensorFlow** and **Keras** as the primary frameworks.

Additionally, the results are displayed not just with the highest probability prediction, but also as a bar graph showing the top 10 predicted probabilities.

### Possible Expansions:
- **Hyperparameter tuning** for the CNN, such as freezing and rebuilding layers.
- Implementing **thresholds for probabilities**: Currently, the highest probability is used for classification (e.g., if probability < 75%, then "no classification possible").
- ...

<img src="https://github.com/user-attachments/assets/aec4a1ec-d0ab-44b1-bf67-ab0e786a3cf9" width="500" />

<img src="https://github.com/user-attachments/assets/7a307aa5-1cd4-43d3-982c-cd995bed25ce" width="500" />

## RAG-based PDF Chatbot
This small project was an experiment using the **LangGraph** framework to create an Agentic RAG-based PDF Chatbot.

Multiple PDFs can be uploaded to a vector-store database. The chatbot uses the information from these PDFs to understand and interact with their content. Also the Chatbot has a memory, which can rember previous questions and tasks.

From now on, the Chatbot just works on one thread, but it could be expanded to multiple threads.

This tool can be very useful for companies looking to build their own internal chatbot.

### Possible Expansions for the Chatbot:
- Integration of threads for multiple tasks
- Internet search assistant
- Integration with databases for searching, calculations, and adding new data
- Writing assistant for documentation
- ...

<img src="https://github.com/user-attachments/assets/9a4e3611-bbd5-4364-8ed2-83c9cff67157" width="600" />
