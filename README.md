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

#### Episode-07 | Sharpening the Brain

- A neural network contains huge collection of adjustable parameters (weights) that are learned during training. The process of training a neural network involves adjusting these weights to minimize the difference between the predicted output and the actual output (ground truth). This is typically done using optimization algorithms such as stochastic gradient descent (SGD) and backpropagation.
- `Forward Pass`: During the forward pass, the input data is passed through the network layer by layer, and the output is computed based on the current weights. The predicted output is then compared to the actual output to calculate the loss (error).
- `Loss Function`: The loss function quantifies the difference between the predicted output and the actual output. Common loss functions include mean squared error (MSE) for regression tasks and cross-entropy loss for classification tasks. The choice of loss function depends on the specific task and the nature of the data.
- `Backpropagation`: Backpropagation is the process of computing the gradients of the loss function with respect to the weights of the network. This is done by applying the chain rule of calculus to propagate the error backward through the network, layer by layer.
- `Gradient Descent`: Gradient descent is an optimization algorithm used to update the weights of the network based on the computed gradients. The weights are adjusted in the direction that minimizes the loss function, with the learning rate determining the step size of the updates.
- `Generalization`: Generalization refers to the ability of a trained neural network to perform well on unseen data. A model that generalizes well can make accurate predictions on new inputs, while a model that overfits may perform poorly on unseen data. Techniques such as regularization, dropout, and early stopping are used to improve generalization and prevent overfitting.
- `Overfitting`: Overfitting occurs when a neural network learns the training data too well, capturing noise and irrelevant patterns that do not generalize to new data. This can lead to poor performance on unseen inputs. To mitigate overfitting, techniques such as cross-validation, regularization, and data augmentation are employed.
- `Distributed Training`: Distributed training involves training a neural network across multiple devices or machines to speed up the training process and handle larger datasets. Techniques such as data parallelism and model parallelism are used to distribute the workload and synchronize updates across devices.

#### Episode-08 | From a Base Model to an AI Assistant

- _ Pre-training_ : Pre-training is the initial phase of training a large language model, where the model is exposed to a vast amount of text data to learn general language patterns and representations. During pre-training, the model learns to predict the next word in a sentence or fill in missing words, allowing it to capture syntactic and semantic information from the text.

- `Common Crawl`: Common Crawl is a non-profit organization that provides an open repository of web crawl data. It collects and stores web pages from the internet, making it available for research and analysis. The data includes raw HTML, text content, and metadata, which can be used for various applications, including training large language models.
- `Fine-Web`: Fine-Web refers to the process of fine-tuning a pre-trained language model on a specific dataset or domain to improve its performance on tasks relevant to that domain. Fine-tuning allows the model to adapt its knowledge and generate more accurate and contextually appropriate outputs for the target application.

- `Reinforcement Learning from Human Feedback (RLHF)`: RLHF is a technique used to improve the performance of language models by incorporating feedback from human evaluators. In this approach, the model generates outputs, and human evaluators provide feedback on the quality and relevance of those outputs. The model is then updated based on this feedback to align its behavior with human preferences and expectations.

- `Supervised Fine-Tuning (SFT)`: Supervised fine-tuning is a process where a pre-trained language model is further trained on a labeled dataset with specific input-output pairs. This allows the model to learn task-specific patterns and improve its performance on the target task. SFT is often used in conjunction with RLHF to enhance the model's capabilities.

#### Episode-09 | Can AI Really Think?

- _Chain of Thought (CoT)_: Chain of Thought is a reasoning technique used in large language models to improve their ability to solve complex problems. It involves breaking down a problem into smaller, manageable steps and generating intermediate reasoning steps before arriving at the final answer. This approach allows the model to reason more effectively and produce more accurate outputs.

- _Reinforcement Learning with Verified Feedback (RLVF)_: RLVF is an advanced technique that combines reinforcement learning with verified feedback to enhance the performance of language models. In this approach, the model receives feedback not only from human evaluators but also from verified sources or rules that ensure the correctness and reliability of the outputs. This helps the model learn to generate more accurate and trustworthy responses.

- `Three type of Evaluation` :
  - Deterministic Evaluation: In deterministic evaluation, the model's outputs are compared against a fixed set of reference answers or ground truth. The evaluation is based on predefined metrics, and the model's performance is assessed based on its ability to match the expected outputs.
  - Human Evaluation: Human evaluation involves assessing the quality and relevance of the model's outputs based on human judgment. Human evaluators review the generated responses and provide feedback on their accuracy, coherence, and usefulness. This type of evaluation is particularly important for tasks that require subjective interpretation or context understanding.
  - Model Evaluator Evaluation: Model evaluator evaluation involves using another model or automated system to assess the performance of the primary model. This can include metrics such as perplexity, BLEU score, or other task-specific evaluation measures. Model evaluator evaluation provides an objective assessment of the model's capabilities and can be used to compare different models or configurations.

- `LLM as Judges`: LLMs can be used as judges to evaluate the quality of outputs generated by other models or systems. By leveraging their language understanding capabilities, LLMs can assess the coherence, relevance, and accuracy of generated content. This approach can help automate the evaluation process and provide consistent feedback for model improvement.

- `Tree of Thoughts (ToT)`: Tree of Thoughts is a reasoning framework that organizes the intermediate reasoning steps generated by a language model into a tree structure. Each node in the tree represents a reasoning step, and branches represent alternative paths or solutions. This structure allows for more systematic exploration of possible solutions and can improve the model's ability to reason through complex problems.

- `Graph of Thoughts (GoT)`: Graph of Thoughts is an extension of the Tree of Thoughts framework that represents reasoning steps and their relationships in a graph structure. In this approach, nodes represent reasoning steps, and edges represent dependencies or connections between them. The graph structure allows for more flexible exploration of reasoning paths and can capture complex relationships between different reasoning steps.
