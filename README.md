# Dialog-Summarization-along-with-Fine-Tuning-

Project Overview:

The primary objective was to develop a dialog summarization system capable of efficiently summarizing conversations.
Utilized Python as the programming language, PyTorch as the deep learning framework, and Hugging Face Transformers for leveraging pre-trained language models.
Model Selection:

Chose the Flan-T5 model from Hugging Face Transformers as the basis for the dialog summarization task. This model is specifically designed for text summarization and is based on the T5 architecture.
Implementation Details:

Implemented the Flan-T5 model within the project framework to generate concise summaries of dialogues.
Addressed various limitations of the baseline model to improve its overall performance.
In-Context Learning:

Introduced a novel approach to in-context learning for dialog summarization.
Utilized one and two-shot inference techniques to enhance the model's ability to summarize conversations in a more contextually aware manner.
Advanced Fine-Tuning Techniques:

Explored advanced fine-tuning techniques, including Parameter-Efficient Fine-Tuning (PEFT) with LoRA (Learnable Ranking), to further boost the summarization capabilities.
Achieved a notable 20% improvement in the model's ability to generate accurate and meaningful summaries.
Dataset:

Acquired the dataset from the "knkarthick/dialogsum" repository, ensuring a diverse and representative collection of dialogues for training and evaluation.
Summary Generation Process:

Developed a comprehensive pipeline for the generation of dialogue summaries using the pre-trained Large Language Model (LLM) FLAN-T5.
Integrated the model seamlessly into the process to efficiently generate concise and contextually relevant summaries.
Performance Evaluation:

Conducted rigorous evaluations to assess the performance of the developed dialog summarization system.
Utilized standard metrics such as ROUGE scores to quantify the quality of generated summaries.
Results:

The project demonstrated significant advancements in dialog summarization capabilities, showcasing the effectiveness of the implemented Flan-T5 model and the fine-tuning techniques applied.
Future Work:

Identified areas for future improvements, such as exploring additional pre-training strategies, experimenting with different architectures, and expanding the dataset to further enhance the model's generalization capabilities.
