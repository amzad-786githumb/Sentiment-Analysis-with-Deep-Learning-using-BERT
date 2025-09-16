# Sentiment Analysis with Deep Learning using BERT

This project implements Sentiment Analysis using Deep Learning with BERT (Bidirectional Encoder Representations from Transformers). The goal is to classify text into positive, negative, or neutral sentiment by leveraging BERT’s powerful contextual embeddings. The workflow includes text preprocessing, tokenization, and fine-tuning BERT with TensorFlow/Keras to achieve state-of-the-art performance in sentiment classification tasks.

Sentiment Analysis model is built using pre-trained BERT transformer large scale language learnings and analysed smile annotations dataset using PyTorch Framework. The architecture is for multi-class classification. Exploratory data analysis(EDA) is done with loading tokenizer and  further encoding data. Data loaders are created to facilitate Batch processing followed up with setting up of Optimizer and Scheduler to control the training of model.

The Performance metrics were designed for model followed by creating a Training loop to control PyTorch fine tuning of BERT acceleration. The pre-trained fine tuned model was loaded and it's performance is evaluated achieving good accuracy.

<h2><b>Application</b></h2>
BERT can be fine-tuned for many NLP tasks such as question answering, named entity recognition, or intent detection in chatbots. However, using such a large model in production brings challenges, including high computational and memory costs, slower response times for real-time applications, and potential biases inherited from its training data. Additionally, large models often require ongoing maintenance and re-training to stay effective. While powerful, BERT must be optimized and monitored carefully for practical, fair, and efficient deployment.

<h2><b>Another task to fine-tune BERT on:</b></h2>
BERT can be fine-tuned for tasks like question answering, named entity recognition (NER), summarization, or even intent detection in chatbots. For example, fine-tuning BERT for customer support automation could help classify queries and route them to the right department.

<h3><b>Potential problems in production:</b></h3>

<ul><b>Computational cost:</b> BERT models are very large, requiring significant memory and processing power, which makes them expensive to run at scale.</ul>

<ul><b>Latency issues:</b> Real-time applications may suffer from slow response times.</ul>

<ul><b>Bias and fairness:</b> Since BERT is trained on large datasets from the internet, it may inherit and amplify social or cultural biases.<ul>

<ul><b>Maintenance challenges:</b> Continuous re-training may be required to keep the model relevant as language and user needs evolve.</ul>
