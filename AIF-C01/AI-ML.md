# AI / ML Overview

`Artificial Intelligence (AI)`  
- The broader concept of machines being able to carry out tasks that would typically require human intelligence, such as recognizing speech, making decisions, or translating languages.

`Machine Learning (ML)`  
- A subset of AI that enables machines to learn from data without being explicitly programmed. The system improves over time by adjusting its algorithms based on patterns found in data.

`Deep Learning (DL)`  
- A subset of ML that uses neural networks with multiple layers (often called "deep" networks) to model complex patterns in data. It is inspired by the structure of the human brain, where neurons and synapses pass information.

## Types of AI Models

`Generative AI`  
- Models focused on creating new content (text, images, music, etc.) by learning patterns from existing data (training data). They do not merely repeat information but generate new outputs based on learned patterns.

## Key Models in AI/ML

`Transformer Model`  
- A type of neural network architecture designed for processing sequential data like natural language. It allows the model to understand the context of words by analyzing the entire sentence at once (as opposed to word-by-word). This architecture is the foundation of many recent advances in NLP (Natural Language Processing).

`Large Language Model (LLM)`  
- A type of transformer-based model specifically designed to understand and generate human-like text. LLMs are trained on vast amounts of text data, enabling them to perform tasks such as translation, summarization, and text generation. Examples of prominent models include:

  - **GPT (Generative Pre-trained Transformer)**  
    - A transformer model designed to `generate human-like text or code` based on a given prompt. GPT excels at tasks like text generation, conversation, and content creation by predicting the next word in a sequence.

  - **BERT (Bidirectional Encoder Representations from Transformers)**  
    - Unlike GPT, which predicts text from left to right, `BERT reads text bidirectionally`, meaning it considers the entire context around a word (both left and right) when making predictions. This makes BERT great for tasks like question answering and sentence classification.

  - **RNN (Recurrent Neural Network)**  
    - Although not typically classified as an LLM, RNNs are designed for sequential or `time-based data`, making them well-suited for tasks like speech recognition and time series analysis. RNNs are an older architecture compared to transformers, but they are important for understanding patterns in sequences.

  - **ResNet (Residual Network)**  
    - ResNet is a neural network architecture used primarily for `image recognition, object detection, and facial recognition`. It is not related to LLMs or natural language tasks, but it is a prominent model in computer vision. ResNet's key feature is its use of "skip connections" to avoid the vanishing gradient problem in deep networks.
   
  - **SVM (Support Vector Machine)**
    - SVM is a supervised machine learning algorithm used for `classification and regression` tasks. It works by finding a hyperplane that best separates different classes in the data. SVMs are particularly effective in high-dimensional spaces and for tasks like image classification or text categorization.
  
  - **WaveNet**
    - Developed by DeepMind, WaveNet is a deep generative model for `generating raw audio waveforms`. It has been used primarily for tasks like text-to-speech (TTS) synthesis. Unlike traditional models that rely on fixed assumptions about audio data, WaveNet generates audio at the waveform level, producing more natural-sounding speech and music.
  
  - **GAN (Generative Adversarial Network)**
    - GANs are a type of generative model that involves two neural networks: a generator and a discriminator. The generator tries to create `fake data that resembles real data` (e.g., images, text), while the discriminator attempts to distinguish between real and fake data. Through this adversarial process, the generator improves over time and can create highly realistic data, such as synthetic images or deepfake videos.
  
  - **XGBoost (Extreme Gradient Boosting)**
    - XGBoost is a powerful, efficient, and scalable implementation of `gradient boosting` for supervised learning tasks. It is widely used for both classification and regression problems, and it performs well on structured/tabular datasets. XGBoost uses an ensemble of decision trees, optimizing the model by focusing on the errors of previous trees, which leads to highly accurate predictions.

`Multi-modal Models`  
- Models that can process and generate multiple types of data, such as text, images, audio, or video. These models can have inputs and outputs of various forms, enabling them to perform tasks like captioning images or answering questions based on visual and textual data.

Your notes on training data are clear, but I've made a few adjustments for clarity and corrected some minor typos. Here's the refined version with some additional details that might be helpful for deeper understanding:

## Training Data

Having high-quality data is imperative when building an accurate and robust machine learning model. The data used in training determines how well the model will generalize to unseen data.

`Labeled Data`

- Data that contains both input features (predictors) and output labels (target variable). This type of data is essential for **supervised learning**, where the model learns to map inputs to known outputs.  
  - **Example**: A dataset where images are labeled as "cat" or "dog," allowing the model to learn the features that distinguish the two.

`Unlabeled Data`

- Data that contains only input features without corresponding output labels. This type of data is commonly used in **unsupervised learning**, where the model identifies patterns or structures within the data without predefined labels.  
  - **Example**: A dataset of customer transaction histories without labels indicating customer segments.

`Structured Data`

- Data that is highly organized and follows a predefined structure, typically in rows and columns, as seen in relational databases or spreadsheets. Structured data includes numerical, categorical, and temporal data, such as time series data.  
  - **Example**: A table with customer names, ages, and purchase amounts, or a time series of stock prices.

`Unstructured Data`

- Data that does not have a clear organizational structure. This includes text, images, audio, and video.
  - **Example**: Text from blog articles, customer reviews, images of products, or raw audio files.