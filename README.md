<!-- Namaste AI -->

# NAMASTE-AI

- Season 1
  - [Episode-01 | Welcome to Namaste AI](#episode-01--welcome-to-namaste-ai)
  - [Episode-02 | The Evolution of AI](#episode-02--the-evolution-of-ai)
  - [Episode-03 | Does ChatGPT Know or Does It Guess](#episode-03--does-chatgpt-know-or-does-it-guess)
  - [Episode-04 | The Secret Language of LLMs](#episode-04--the-secret-language-of-llms)
  - [Episode-05 | How Machines Represent Meaning](#episode-05--how-machines-represent-meaning)
  - [Episode-06 | The Computational Brain of Machines](#episode-06--the-computational-brain-of-machines)

#### Episode-01 | Welcome to Namaste AI

##### Key Takeaways

- Roadmap of the course
  - Introduction to AI and its applications
  - LLM (Large Language Models) and their capabilities
  - Prompt Engineering and its importance
  - AI for SDE's
  - Tools
  - RAG
  - AI Agents
  - MCP
  - AI Engineering
  - Projects

#### Episode-02 | The Evolution of AI

##### Key Takeaways

- What is Artificial Intelligence?
  - AI is a branch of computer science that aims to create machines that can perform tasks that typically require human intelligence. These tasks include learning, reasoning, problem-solving, perception, and language understanding.

- _History of AI_
  - The history of AI can be traced back to the 1950s when the term "Artificial Intelligence" was first coined. Early AI research focused on symbolic reasoning and problem-solving. Over the years, AI has evolved through various stages, including expert systems, machine learning, and deep learning.
  - In `1950` Alan Turing proposed the Turing Test, a method to determine if a machine can exhibit intelligent behavior indistinguishable from that of a human.
  - In `1955` John McCarthy, Marvin Minsky, Nathaniel Rochester, and Claude Shannon organized the Dartmouth Conference, which is considered the birth of AI as a field of study. He coined the term "Artificial Intelligence" and laid the foundation for future research in the field.
  - In `1986` Synthetic Intelligence (SI) was introduced, which focused on creating intelligent agents that could learn and adapt to their environment.
  - In `1997` IBM's Deep Blue defeated world chess champion Garry Kasparov, showcasing the potential of AI in complex problem-solving.
- _Machine Learning, Deep Learning, and Neural Networks_
  - `Machine Learning (ML)` is a subset of AI that focuses on developing algorithms that allow computers to learn from data and improve their performance over time. ML algorithms can be classified into supervised learning, unsupervised learning, and reinforcement learning.
  - `Deep Learning (DL)` is a subset of ML that uses artificial neural networks to model complex patterns in data. DL has been particularly successful in tasks such as image recognition, natural language processing, and speech recognition.
  - `Neural Networks` are computational models inspired by the structure and function of the human brain. They consist of interconnected layers of nodes (neurons) that process information and learn from data.
- _Computer Vision Revolution_
  - Computer Vision is a field of AI that enables machines to interpret and understand visual information from the world. It has applications in image and video analysis, object detection, facial recognition, and autonomous vehicles.
  - The revolution in computer vision has been driven by advancements in deep learning, particularly convolutional neural networks (CNNs), which have significantly improved the accuracy of image classification and object detection tasks.
- _Natural Language Processing (NLP)_
  - Natural Language Processing is a subfield of AI that focuses on the interaction between computers and human language. NLP enables machines to understand, interpret, and generate human language in a way that is both meaningful and useful.
  - NLP has applications in machine translation, sentiment analysis, chatbots, and virtual assistants. Recent advancements in NLP have been driven by the development of large language models (LLMs) such as GPT-3 and BERT, which have demonstrated remarkable capabilities in understanding and generating human-like text.
- _Transformers_ (Vaswani et al., 2017)
  - `Attention is All You Need` is a seminal paper that introduced the transformer architecture, which has become the foundation for many state-of-the-art NLP models. Transformers use self-attention mechanisms to process input data in parallel, allowing for more efficient training and better performance on a wide range of NLP tasks.
  - Transformers are a type of neural network architecture that has revolutionized the field of NLP. They use self-attention mechanisms to process input data in parallel, allowing for more efficient training and better performance on a wide range of NLP tasks.
  - The introduction of transformer models, such as BERT and GPT, has led to significant improvements in language understanding and generation, enabling applications like question answering, text summarization, and conversational AI.
- _Large Language Models (LLMs)_
  - Large Language Models are a class of AI models that are trained on vast amounts of text data to understand and generate human language. LLMs, such as GPT-3 and BERT, have demonstrated remarkable capabilities in natural language understanding and generation, enabling applications like chatbots, virtual assistants, and content creation.
  - LLMs leverage the transformer architecture to process and generate text, allowing them to capture complex patterns and relationships in language. They can perform a wide range of tasks, including text completion, translation, summarization, and question answering.
- _Generative AI_
  - Generative AI refers to a class of AI models that can generate new content, such as text, images, or music, based on the patterns learned from existing data. Generative models, such as Generative Adversarial Networks (GANs) and Variational Autoencoders (VAEs), have been used to create realistic images, videos, and audio.
  - Generative AI has applications in creative industries, content generation, and data augmentation. It has the potential to revolutionize fields such as art, design, and entertainment by enabling the creation of novel and diverse content.

#### Episode-03 | Does ChatGPT Know or Does It Guess

- _Inference_
  - Inference is the process of drawing conclusions or making predictions based on available information or evidence. In the context of AI and machine learning, inference refers to the process of using a trained model to make predictions or generate outputs based on new input data.
  - Inference can be performed in various ways, depending on the type of model and the task at hand. For example, in supervised learning, inference involves using a trained model to predict the output for new input data. In unsupervised learning, inference may involve clustering or dimensionality reduction to uncover patterns in the data.
  - Inference is a critical step in the deployment of AI models, as it allows them to be used in real-world applications. The efficiency and accuracy of inference can significantly impact the performance and usability of AI systems.
- _Hallucination_
  - Hallucination in AI refers to the phenomenon where a model generates outputs that are not grounded in reality or factual information. This can occur when a model produces responses that are plausible-sounding but factually incorrect or misleading.
  - Hallucination can be a significant challenge in natural language processing and generative AI, as it can lead to the dissemination of false information and reduce the trustworthiness of AI systems. Researchers are actively working on methods to mitigate hallucination and improve the reliability of AI-generated content.
- _Retrieval-Augmented Generation (RAG)_
  - Retrieval-Augmented Generation is a technique that combines the strengths of retrieval-based methods and generative models to improve the quality and accuracy of AI-generated content. RAG involves retrieving relevant information from external sources and using it to inform the generation process, allowing for more contextually accurate and factually grounded outputs.
  - RAG has applications in various domains, including question answering, summarization, and conversational AI. By leveraging external knowledge sources, RAG can help mitigate hallucination and enhance the reliability of AI-generated responses.

#### Episode-04 | The Secret Language of LLMs

- _Tokens_:
  - Tokens are the basic units of text that are processed by language models. In natural language processing, a token can be a word, subword, or character, depending on the tokenization method used. Tokenization is the process of breaking down text into these smaller units for analysis and modeling.
  - The choice of tokenization method can significantly impact the performance of language models, as it affects how the model represents and understands text. Common tokenization methods include word-level tokenization, subword tokenization (e.g., Byte Pair Encoding), and character-level tokenization.

- _Context Window_:
  - The context window refers to the span of text that a language model can consider when generating predictions or outputs. It defines the amount of preceding text that the model can use to inform its understanding of the current input.
  - The size of the context window can affect the model's ability to capture long-range dependencies and maintain coherence in generated text. Larger context windows allow models to consider more information, while smaller windows may limit their understanding of context.

  #### Episode-05 | How Machines Represent Meaning
  - _Vectorisation_:
    - Vectorization is the process of converting text or other data into numerical representations (vectors) that can be processed by machine learning models. In natural language processing, vectorization allows models to capture semantic meaning and relationships between words or phrases.
    - Common vectorization techniques include one-hot encoding, term frequency-inverse document frequency (TF-IDF), and word embeddings (e.g., Word2Vec, GloVe). More advanced methods, such as contextual embeddings from transformer models (e.g., BERT), capture richer semantic information by considering the context in which words appear.
  - _Embeddings_:
    - Embeddings are dense vector representations of data that capture semantic meaning and relationships between entities. In natural language processing, word embeddings represent words in a continuous vector space, where semantically similar words are located closer together.
    - Embeddings can be learned from large corpora of text using techniques such as Word2Vec, GloVe, or transformer-based models like BERT. They enable models to understand the meaning of words and phrases in context, facilitating tasks such as text classification, sentiment analysis, and information retrieval.

    #### Episode-06 | The Computational Brain of Machines
    - _GPT_
      - GPT (Generative Pre-trained Transformer) is a type of large language model developed by OpenAI. It is based on the transformer architecture and is pre-trained on vast amounts of text data to learn patterns and relationships in language. GPT can generate coherent and contextually relevant text, making it suitable for various natural language processing tasks.
      - The GPT model consists of multiple layers of transformer blocks, each containing self-attention mechanisms and feedforward neural networks. During pre-training, the model learns to predict the next word in a sentence, allowing it to capture syntactic and semantic information.
      - GPT has been used in applications such as chatbots, content generation, translation, and summarization. Its ability to generate human-like text has made it a powerful tool for natural language understanding and generation.

  - _Transformers_
    - Transformers are a type of neural network architecture that has revolutionized the field of natural language processing. They use self-attention mechanisms to process input data in parallel, allowing for more efficient training and better performance on a wide range of NLP tasks.
    - The transformer architecture consists of an encoder-decoder structure, where the encoder processes the input sequence and generates a context-aware representation, while the decoder generates the output sequence based on this representation. This architecture enables transformers to capture long-range dependencies and relationships in text.
    - Transformers have been used in various state-of-the-art models, including BERT, GPT, and T5, enabling applications such as question answering, text summarization, and machine translation.
