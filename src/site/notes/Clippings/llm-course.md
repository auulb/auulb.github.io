---
{"dg-publish":true,"permalink":"/Clippings/llm-course/","title":"llm-course","tags":["clippings"],"dg-note-properties":{"title":"llm-course","source":"https://github.com/mlabonne/llm-course","author":null,"published":null,"created":"2026-10-12","description":null,"tags":["clippings"]}}
---

The LLM course is divided into three parts:  
法学硕士课程分为三个部分：

1. 🧩 **LLM Fundamentals** is optional and covers fundamental knowledge about mathematics, Python, and neural networks.  
	🧩 **LLM 基础课程** 为选修课，涵盖数学、Python 和神经网络方面的基础知识。
2. 🧑🔬 **The LLM Scientist** focuses on building the best possible LLMs using the latest techniques.  
	🧑🔬 **LLM 科学家** 致力于运用最新技术构建最佳的 LLM。
3. 👷 **The LLM Engineer** focuses on creating LLM-based applications and deploying them.  
	👷 **LLM 工程师** 专注于创建基于 LLM 的应用程序并进行部署。

> [!note] Note
> Based on this course, I co-wrote the [LLM Engineer's Handbook](https://packt.link/a/9781836200079), a hands-on book that covers an end-to-end LLM application from design to deployment. The LLM course will always stay free, but you can support my work by purchasing this book.  
> 基于这门课程，我与人合著了 [《LLM 工程师手册》](https://packt.link/a/9781836200079) ，这是一本实战指南，涵盖了从设计到部署的端到端 LLM 应用开发流程。LLM 课程将始终免费，但您可以通过购买本书来支持我的工作。

For a more comprehensive version of this course, check out the [DeepWiki](https://deepwiki.com/mlabonne/llm-course/).  
想要了解更全面的课程内容，请查看 [DeepWiki](https://deepwiki.com/mlabonne/llm-course/) 。

## 📝 Notebooks📝 笔记本

A list of notebooks and articles I wrote about LLMs.  
我撰写的关于法学硕士（LLM）的笔记和文章列表。

Toggle section (optional)  
切换部分（可选）

### Tools

| Notebook | Description | Notebook |
| --- | --- | --- |
| 🧐 [LLM AutoEval](https://github.com/mlabonne/llm-autoeval) | Automatically evaluate your LLMs using RunPod |  |
| 🥱 LazyMergekit | Easily merge models using MergeKit in one click. |  |
| 🦎 LazyAxolotl | Fine-tune models in the cloud using Axolotl in one click. |  |
| ⚡ AutoQuant | Quantize LLMs in GGUF, GPTQ, EXL2, AWQ, and HQQ formats in one click. |  |
| 🌳 Model Family Tree | Visualize the family tree of merged models. |  |
| 🚀 ZeroSpace | Automatically create a Gradio chat interface using a free ZeroGPU. |  |
| ✂️ AutoAbliteration | Automatically abliteration models with custom datasets. |  |
| 🧼 AutoDedup | Automatically deduplicate datasets using the Rensa library. |  |

### Fine-tuning

| Notebook | Description | Article | Notebook |
| --- | --- | --- | --- |
| Fine-tune Llama 3.1 with Unsloth | Ultra-efficient supervised fine-tuning in Google Colab. | [Article](https://mlabonne.github.io/blog/posts/2024-07-29_Finetune_Llama31.html) |  |
| Fine-tune Llama 3 with ORPO | Cheaper and faster fine-tuning in a single stage with ORPO. | [Article](https://mlabonne.github.io/blog/posts/2024-04-19_Fine_tune_Llama_3_with_ORPO.html) |  |
| Fine-tune Mistral-7b with DPO | Boost the performance of supervised fine-tuned models with DPO. | [Article](https://mlabonne.github.io/blog/posts/Fine_tune_Mistral_7b_with_DPO.html) |  |
| Fine-tune Mistral-7b with QLoRA | Supervised fine-tune Mistral-7b in a free-tier Google Colab with TRL. |  |  |
| Fine-tune CodeLlama using Axolotl | End-to-end guide to the state-of-the-art tool for fine-tuning. | [Article](https://mlabonne.github.io/blog/posts/A_Beginners_Guide_to_LLM_Finetuning.html) |  |
| Fine-tune Llama 2 with QLoRA | Step-by-step guide to supervised fine-tune Llama 2 in Google Colab. | [Article](https://mlabonne.github.io/blog/posts/Fine_Tune_Your_Own_Llama_2_Model_in_a_Colab_Notebook.html) |  |

### Quantization

| Notebook | Description | Article | Notebook |
| --- | --- | --- | --- |
| Introduction to Quantization | Large language model optimization using 8-bit quantization. | [Article](https://mlabonne.github.io/blog/posts/Introduction_to_Weight_Quantization.html) |  |
| 4-bit Quantization using GPTQ | Quantize your own open-source LLMs to run them on consumer hardware. | [Article](https://mlabonne.github.io/blog/4bit_quantization/) |  |
| Quantization with GGUF and llama.cpp | Quantize Llama 2 models with llama.cpp and upload GGUF versions to the HF Hub. | [Article](https://mlabonne.github.io/blog/posts/Quantize_Llama_2_models_using_ggml.html) |  |
| ExLlamaV2: The Fastest Library to Run LLMs | Quantize and run EXL2 models and upload them to the HF Hub. | [Article](https://mlabonne.github.io/blog/posts/ExLlamaV2_The_Fastest_Library_to_Run%C2%A0LLMs.html) |  |

### Other

| Notebook | Description | Article | Notebook |
| --- | --- | --- | --- |
| Merge LLMs with MergeKit | Create your own models easily, no GPU required! | [Article](https://mlabonne.github.io/blog/posts/2024-01-08_Merge_LLMs_with_mergekit%20copy.html) |  |
| Create MoEs with MergeKit | Combine multiple experts into a single frankenMoE | [Article](https://mlabonne.github.io/blog/posts/2024-03-28_Create_Mixture_of_Experts_with_MergeKit.html) |  |
| Uncensor any LLM with abliteration | Fine-tuning without retraining | [Article](https://mlabonne.github.io/blog/posts/2024-06-04_Uncensor_any_LLM_with_abliteration.html) |  |
| Improve ChatGPT with Knowledge Graphs | Augment ChatGPT's answers with knowledge graphs. | [Article](https://mlabonne.github.io/blog/posts/Article_Improve_ChatGPT_with_Knowledge_Graphs.html) |  |
| Decoding Strategies in Large Language Models | A guide to text generation from beam search to nucleus sampling | [Article](https://mlabonne.github.io/blog/posts/2022-06-07-Decoding_strategies.html) |  |

## 🧩 LLM Fundamentals🧩 法学硕士基础知识

This section introduces essential knowledge about mathematics, Python, and neural networks. You might not want to start here but refer to it as needed.  
本节介绍数学、Python 和神经网络方面的基础知识。您可能不需要从这里开始学习，但可以根据需要参考本节内容。

Toggle section (optional)  
切换部分（可选）

[![](https://github.com/mlabonne/llm-course/raw/main/img/roadmap_fundamentals.png)](https://github.com/mlabonne/llm-course/blob/main/img/roadmap_fundamentals.png)

### 1\. Mathematics for Machine Learning

Before mastering machine learning, it is important to understand the fundamental mathematical concepts that power these algorithms.

- **Linear Algebra**: This is crucial for understanding many algorithms, especially those used in deep learning. Key concepts include vectors, matrices, determinants, eigenvalues and eigenvectors, vector spaces, and linear transformations.
- **Calculus**: Many machine learning algorithms involve the optimization of continuous functions, which requires an understanding of derivatives, integrals, limits, and series. Multivariable calculus and the concept of gradients are also important.

---

- **Probability and Statistics**: These are crucial for understanding how models learn from data and make predictions.  
	Key concepts include probability theory, random variables, probability distributions, expectations, variance, covariance, correlation, hypothesis testing, confidence intervals, maximum likelihood estimation, and Bayesian inference.

---

📚 Resources:

- [3Blue1Brown - The Essence of Linear Algebra](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab): Series of videos that give a geometric intuition to these concepts.
- [StatQuest with Josh Starmer - Statistics Fundamentals](https://www.youtube.com/watch?v=qBigTkBLU6g&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9): Offers simple and clear explanations for many statistical concepts.
- [Seeing Theory](https://seeing-theory.brown.edu/): A visual introduction to probability and statistics from Brown University.
- [Immersive Linear Algebra](https://immersivemath.com/ila/learnmore.html): Another visual interpretation of linear algebra.
- [Khan Academy - Linear Algebra](https://www.khanacademy.org/math/linear-algebra): Great for beginners as it explains the concepts in a very intuitive way.
- [Khan Academy - Calculus](https://www.khanacademy.org/math/calculus-1): An interactive course that covers all the basics of calculus.
- [Khan Academy - Probability and Statistics](https://www.khanacademy.org/math/statistics-probability): Delivers the material in an easy-to-understand format.

---

### 2\. Python for Machine Learning

Python is a powerful and flexible programming language that's particularly good for machine learning, thanks to its readability, consistency, and robust ecosystem of data science libraries.

- **Python Basics**: Python programming requires a good understanding of the basic syntax, data types, error handling, and object-oriented programming.
- **Data Science Libraries**: It includes familiarity with NumPy for numerical operations, Pandas for data manipulation and analysis, Matplotlib and Seaborn for data visualization.
- **Data Preprocessing**: This involves feature scaling and normalization, handling missing data, outlier detection, categorical data encoding, and splitting data into training, validation, and test sets.

---

- **Machine Learning Libraries**: Proficiency with Scikit-learn, a library providing a wide selection of supervised and unsupervised learning algorithms, is vital.  
	Understanding how to implement algorithms like linear regression, logistic regression, decision trees, random forests, k-nearest neighbors (K-NN), and K-means clustering is important.  
	Dimensionality reduction techniques like PCA and t-SNE are also helpful for visualizing high-dimensional data.

---

📚 Resources:

- [Real Python](https://realpython.com/): A comprehensive resource with articles and tutorials for both beginner and advanced Python concepts.
- [freeCodeCamp - Learn Python](https://www.youtube.com/watch?v=rfscVS0vtbw): Long video that provides a full introduction into all of the core concepts in Python.
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/): Free digital book that is a great resource for learning pandas, NumPy, Matplotlib, and Seaborn.
- [freeCodeCamp - Machine Learning for Everybody](https://youtu.be/i_LwzRVP7bg): Practical introduction to different machine learning algorithms for beginners.
- [Udacity - Intro to Machine Learning](https://www.udacity.com/course/intro-to-machine-learning--ud120): Free course that covers PCA and several other machine learning concepts.

---

### 3\. Neural Networks

Neural networks are a fundamental part of many machine learning models, particularly in the realm of deep learning. To utilize them effectively, a comprehensive understanding of their design and mechanics is essential.

- **Fundamentals**: This includes understanding the structure of a neural network, such as layers, weights, biases, and activation functions (sigmoid, tanh, ReLU, etc.)
- **Training and Optimization**: Familiarize yourself with backpropagation and different types of loss functions, like Mean Squared Error (MSE) and Cross-Entropy. Understand various optimization algorithms like Gradient Descent, Stochastic Gradient Descent, RMSprop, and Adam.
- **Overfitting**: Understand the concept of overfitting (where a model performs well on training data but poorly on unseen data) and learn various regularization techniques (dropout, L1/L2 regularization, early stopping, data augmentation) to prevent it.
- **Implement a Multilayer Perceptron (MLP)**: Build an MLP, also known as a fully connected network, using PyTorch.

📚 Resources:

- [3Blue1Brown - But what is a Neural Network?](https://www.youtube.com/watch?v=aircAruvnKk): This video gives an intuitive explanation of neural networks and their inner workings.
- [freeCodeCamp - Deep Learning Crash Course](https://www.youtube.com/watch?v=VyWAvY2CF9c): This video efficiently introduces all the most important concepts in deep learning.
- [Fast.ai - Practical Deep Learning](https://course.fast.ai/): Free course designed for people with coding experience who want to learn about deep learning.
- [Patrick Loeber - PyTorch Tutorials](https://www.youtube.com/playlist?list=PLqnslRFeH2UrcDBWF5mfPGpqQDSta6VK4): Series of videos for complete beginners to learn about PyTorch.

---

### 4\. Natural Language Processing (NLP)

---

NLP is a fascinating branch of artificial intelligence that bridges the gap between human language and machine understanding.  
From simple text processing to understanding linguistic nuances, NLP plays a crucial role in many applications like translation, sentiment analysis, chatbots, and much more.

---

- **Text Preprocessing**: Learn various text preprocessing steps like tokenization (splitting text into words or sentences), stemming (reducing words to their root form), lemmatization (similar to stemming but considers the context), stop word removal, etc.
- **Feature Extraction Techniques**: Become familiar with techniques to convert text data into a format that can be understood by machine learning algorithms. Key methods include Bag-of-words (BoW), Term Frequency-Inverse Document Frequency (TF-IDF), and n-grams.
- **Word Embeddings**: Word embeddings are a type of word representation that allows words with similar meanings to have similar representations. Key methods include Word2Vec, GloVe, and FastText.
- **Recurrent Neural Networks (RNNs)**: Understand the working of RNNs, a type of neural network designed to work with sequence data. Explore LSTMs and GRUs, two RNN variants that are capable of learning long-term dependencies.

📚 Resources:

- [Lena Voita - Word Embeddings](https://lena-voita.github.io/nlp_course/word_embeddings.html): Beginner-friendly course about concepts related to word embeddings.
- [RealPython - NLP with spaCy in Python](https://realpython.com/natural-language-processing-spacy-python/): Exhaustive guide about the spaCy library for NLP tasks in Python.
- [Kaggle - NLP Guide](https://www.kaggle.com/learn-guide/natural-language-processing): A few notebooks and resources for a hands-on explanation of NLP in Python.
- [Jay Alammar - The Illustration Word2Vec](https://jalammar.github.io/illustrated-word2vec/): A good reference to understand the famous Word2Vec architecture.
- [Jake Tae - PyTorch RNN from Scratch](https://jaketae.github.io/study/pytorch-rnn/): Practical and simple implementation of RNN, LSTM, and GRU models in PyTorch.
- [colah's blog - Understanding LSTM Networks](https://colah.github.io/posts/2015-08-Understanding-LSTMs/): A more theoretical article about the LSTM network.

## 🧑🔬 The LLM Scientist🧑🔬 法学硕士科学家

This section of the course focuses on learning how to build the best possible LLMs using the latest techniques.  
本课程的这一部分重点学习如何使用最新技术构建最佳的 LLM（学习领导力模型）。

[![](https://github.com/mlabonne/llm-course/raw/main/img/roadmap_scientist.png)](https://github.com/mlabonne/llm-course/blob/main/img/roadmap_scientist.png)

### 1\. The LLM Architecture1. LLM 架构

An in-depth knowledge of the Transformer architecture is not required, but it's important to understand the main steps of modern LLMs: converting text into numbers through tokenization, processing these tokens through layers including attention mechanisms, and finally generating new text through various sampling strategies.  
无需深入了解 Transformer 架构，但了解现代 LLM 的主要步骤很重要：通过分词将文本转换为数字，通过包括注意力机制在内的层处理这些标记，最后通过各种采样策略生成新文本。

- **Architectural overview**: Understand the evolution from encoder-decoder Transformers to decoder-only architectures like GPT, which form the basis of modern LLMs. Focus on how these models process and generate text at a high level.  
	**架构概述** ：了解从编码器-解码器架构（如 Transformer）到仅解码器架构（如 GPT）的演变过程，这些架构构成了现代语言模型的基础。重点关注这些模型如何处理和生成文本。
- **Tokenization**: Learn the principles of tokenization - how text is converted into numerical representations that LLMs can process. Explore different tokenization strategies and their impact on model performance and output quality.  
	**分词** ：学习分词原理——如何将文本转换为语言学习模型（LLM）可以处理的数值表示。探索不同的分词策略及其对模型性能和输出质量的影响。
- **Attention mechanisms**: Master the core concepts of attention mechanisms, particularly self-attention and its variants. Understand how these mechanisms enable LLMs to process long-range dependencies and maintain context throughout sequences.  
	**注意力机制** ：掌握注意力机制的核心概念，特别是自我注意力及其变体。理解这些机制如何使逻辑学习模型（LLM）能够处理长程依赖关系并在整个序列中保持上下文关联。
- **Sampling techniques**: Explore various text generation approaches and their tradeoffs. Compare deterministic methods like greedy search and beam search with probabilistic approaches like temperature sampling and nucleus sampling.  
	**采样技术** ：探索各种文本生成方法及其优缺点。比较确定性方法（如贪婪搜索和束搜索）与概率性方法（如温度采样和原子核采样）。

📚 **References**:  
📚 **参考文献** ：

- [Visual intro to Transformers](https://www.youtube.com/watch?v=wjZofJX0v4M) by 3Blue1Brown: Visual introduction to Transformers for complete beginners.  
	3Blue1Brown 制作的 [《变形金刚》视觉入门](https://www.youtube.com/watch?v=wjZofJX0v4M) ：面向完全初学者的《变形金刚》视觉入门。
- [LLM Visualization](https://bbycroft.net/llm) by Brendan Bycroft: Interactive 3D visualization of LLM internals.  
	Brendan Bycroft 的 [LLM 可视化](https://bbycroft.net/llm) ：LLM 内部结构的交互式 3D 可视化。
- [nanoGPT](https://www.youtube.com/watch?v=kCc8FmEb1nY) by Andrej Karpathy: A 2h-long YouTube video to reimplement GPT from scratch (for programmers). He also made a video about [tokenization](https://www.youtube.com/watch?v=zduSFxRajkE).  
	Andrej Karpathy 的 [nanoGPT](https://www.youtube.com/watch?v=kCc8FmEb1nY) ：一段长达 2 小时的 YouTube 视频，讲解如何从零开始重新实现 GPT（面向程序员）。他还制作了一段关于 [分词的](https://www.youtube.com/watch?v=zduSFxRajkE) 视频。
- [Attention? Attention!](https://lilianweng.github.io/posts/2018-06-24-attention/) by Lilian Weng: Historical overview to introduce the need for attention mechanisms.  
	[注意？注意！](https://lilianweng.github.io/posts/2018-06-24-attention/) 作者：Lilian Weng：历史概述，介绍注意机制的必要性。
- [Decoding Strategies in LLMs](https://mlabonne.github.io/blog/posts/2023-06-07-Decoding_strategies.html) by Maxime Labonne: Provide code and a visual introduction to the different decoding strategies to generate text.  
	Maxime Labonne 的 [LLM 解码策略](https://mlabonne.github.io/blog/posts/2023-06-07-Decoding_strategies.html) ：提供代码和视觉介绍，介绍用于生成文本的不同解码策略。

---

### 2\. Pre-Training Models2. 预训练模型

---

Pre-training is a computationally intensive and expensive process. While it's not the focus of this course, it's important to have a solid understanding of how models are pre-trained, especially in terms of data and parameters.  
预训练是一个计算密集型且成本高昂的过程。虽然这不是本课程的重点，但深入了解模型的预训练方式，尤其是在数据和参数方面，至关重要。  
Pre-training can also be performed by hobbyists at a small scale with <1B models.  
业余爱好者也可以小规模地进行预训练，模型数量少于 10 亿。

---

- **Data preparation**: Pre-training requires massive datasets (e.g., [Llama 3.1](https://arxiv.org/abs/2307.09288) was trained on 15 trillion tokens) that need careful curation, cleaning, deduplication, and tokenization. Modern pre-training pipelines implement sophisticated filtering to remove low-quality or problematic content.  
	**数据准备** ：预训练需要海量数据集（例如， [Llama 3.1](https://arxiv.org/abs/2307.09288) 使用 15 万亿个词元进行训练），这些数据集需要经过精心整理、清洗、去重和分词。现代预训练流程采用复杂的过滤机制来去除低质量或有问题的内容。
- **Distributed training**: Combine different parallelization strategies: data parallel (batch distribution), pipeline parallel (layer distribution), and tensor parallel (operation splitting). These strategies require optimized network communication and memory management across GPU clusters.  
	**分布式训练** ：结合不同的并行化策略：数据并行（批处理分布）、流水线并行（层分布）和张量并行（运算拆分）。这些策略需要优化跨 GPU 集群的网络通信和内存管理。
- **Training optimization**: Use adaptive learning rates with warm-up, gradient clipping, and normalization to prevent explosions, mixed-precision training for memory efficiency, and modern optimizers (AdamW, Lion) with tuned hyperparameters.  
	**训练优化** ：使用自适应学习率进行预热、梯度裁剪和归一化以防止爆炸，混合精度训练以提高内存效率，以及使用经过调整的超参数的现代优化器（AdamW、Lion）。
- **Monitoring**: Track key metrics (loss, gradients, GPU stats) using dashboards, implement targeted logging for distributed training issues, and set up performance profiling to identify bottlenecks in computation and communication across devices.  
	**监控** ：使用仪表板跟踪关键指标（损失、梯度、GPU 统计信息），针对分布式训练问题实施有针对性的日志记录，并设置性能分析以识别跨设备的计算和通信瓶颈。

📚 **References**:  
📚 **参考文献** ：

- [FineWeb](https://huggingface.co/spaces/HuggingFaceFW/blogpost-fineweb-v1) by Penedo et al.: Article to recreate a large-scale dataset for LLM pretraining (15T), including FineWeb-Edu, a high-quality subset.  
	Penedo 等人的 [FineWeb](https://huggingface.co/spaces/HuggingFaceFW/blogpost-fineweb-v1) ：文章旨在重建用于 LLM 预训练的大规模数据集 (15T)，其中包括高质量子集 FineWeb-Edu。
- [RedPajama v2](https://www.together.ai/blog/redpajama-data-v2) by Weber et al.: Another article and paper about a large-scale pre-training dataset with a lot of interesting quality filters.  
	Weber 等人的 [RedPajama v2](https://www.together.ai/blog/redpajama-data-v2) ：另一篇关于大规模预训练数据集的文章和论文，其中包含许多有趣的质量过滤器。
- [nanotron](https://github.com/huggingface/nanotron) by Hugging Face: Minimalistic LLM training codebase used to make [SmolLM2](https://github.com/huggingface/smollm).  
	Hugging Face 的 [nanotron](https://github.com/huggingface/nanotron) ：用于制作 [SmolLM2 的](https://github.com/huggingface/smollm) 极简 LLM 训练代码库。
- [Parallel training](https://www.andrew.cmu.edu/course/11-667/lectures/W10L2%20Scaling%20Up%20Parallel%20Training.pdf) by Chenyan Xiong: Overview of optimization and parallelism techniques.  
	陈彦雄的 [并行训练](https://www.andrew.cmu.edu/course/11-667/lectures/W10L2%20Scaling%20Up%20Parallel%20Training.pdf) ：优化和并行技术概述。
- [Distributed training](https://arxiv.org/abs/2407.20018) by Duan et al.: A survey about efficient training of LLM on distributed architectures.  
	Duan 等人的 [分布式训练](https://arxiv.org/abs/2407.20018) ：关于在分布式架构上高效训练 LLM 的调查。
- [OLMo 2](https://allenai.org/olmo) by AI2: Open-source language model with model, data, training, and evaluation code.  
	AI2 的 [OLMo 2](https://allenai.org/olmo) ：开源语言模型，包含模型、数据、训练和评估代码。
- [LLM360](https://www.llm360.ai/) by LLM360: A framework for open-source LLMs with training and data preparation code, data, metrics, and models.  
	[LLM360](https://www.llm360.ai/) 由 LLM360 提供：一个开源 LLM 框架，包含训练和数据准备代码、数据、指标和模型。

---

### 3\. Post-Training Datasets3. 训练后数据集

---

Post-training datasets have a precise structure with instructions and answers (supervised fine-tuning) or instructions and chosen/rejected answers (preference alignment).  
训练后数据集具有精确的结构，包含指令和答案（监督微调）或指令和已选择/已拒绝的答案（偏好对齐）。  
Conversational structures are a lot rarer than the raw text used for pre-training, which is why we often need to process seed data and refine it to improve the accuracy, diversity, and complexity of the samples.  
对话结构比用于预训练的原始文本要少得多，因此我们经常需要处理种子数据并对其进行改进，以提高样本的准确性、多样性和复杂性。  
More information and examples are available in my repo [💾 LLM Datasets](https://github.com/mlabonne/llm-datasets).  
更多信息和示例可在我的仓库 [💾 LLM 数据](https://github.com/mlabonne/llm-datasets) 集中找到。

---

- **Storage & chat templates**: Because of the conversational structure, post-training datasets are stored in a specific format like ShareGPT or OpenAI/HF. Then, these formats are mapped to a chat template like ChatML or Alpaca to produce the final samples that the model is trained on.  
	**存储与聊天模板** ：由于对话结构的特性，训练后的数据集会以特定格式存储，例如 ShareGPT 或 OpenAI/HF。然后，这些格式会被映射到聊天模板（例如 ChatML 或 Alpaca），从而生成模型训练所需的最终样本。
- **Synthetic data generation**: Create instruction-response pairs based on seed data using frontier models like GPT-4o. This approach allows for flexible and scalable dataset creation with high-quality answers. Key considerations include designing diverse seed tasks and effective system prompts.  
	**合成数据生成** ：利用 GPT-4o 等前沿模型，基于种子数据创建指令-响应对。这种方法能够灵活、可扩展地创建高质量答案的数据集。关键考虑因素包括设计多样化的种子任务和有效的系统提示。
- **Data enhancement**: Enhance existing samples using techniques like verified outputs (using unit tests or solvers), multiple answers with rejection sampling, [Auto-Evol](https://arxiv.org/abs/2406.00770), Chain-of-Thought, Branch-Solve-Merge, personas, etc.  
	**数据增强** ：使用验证输出（使用单元测试或求解器）、拒绝抽样的多答案、 [自动进化](https://arxiv.org/abs/2406.00770) 、思维链、分支求解合并、角色等技术来增强现有样本。
- **Quality filtering**: Traditional techniques involve rule-based filtering, removing duplicates or near-duplicates (with MinHash or embeddings), and n-gram decontamination. Reward models and judge LLMs complement this step with fine-grained and customizable quality control.  
	**质量过滤** ：传统技术包括基于规则的过滤、去除重复项或近似重复项（使用 MinHash 或嵌入）以及 n-gram 去污。奖励模型和评判 LLM 通过更精细、可定制的质量控制来补充这一步骤。

📚 **References**:  
📚 **参考文献** ：

- [Synthetic Data Generator](https://huggingface.co/spaces/argilla/synthetic-data-generator) by Argilla: Beginner-friendly way of building datasets using natural language in a Hugging Face space.  
	Argilla 的 [合成数据生成器](https://huggingface.co/spaces/argilla/synthetic-data-generator) ：在 Hugging Face 空间中使用自然语言构建数据集的入门友好方式。
- [LLM Datasets](https://github.com/mlabonne/llm-datasets) by Maxime Labonne: Curated list of datasets and tools for post-training.  
	Maxime Labonne 的 [LLM 数据集](https://github.com/mlabonne/llm-datasets) ：精选的训练后数据集和工具列表。
- [NeMo-Curator](https://github.com/NVIDIA/NeMo-Curator) by Nvidia: Dataset preparation and curation framework for pre- and post-training data.  
	Nvidia 的 [NeMo-Curator](https://github.com/NVIDIA/NeMo-Curator) ：用于训练前和训练后数据的数据集准备和管理框架。
- [Distilabel](https://distilabel.argilla.io/dev/sections/pipeline_samples/) by Argilla: Framework to generate synthetic data. It also includes interesting reproductions of papers like UltraFeedback.  
	Argilla 的 [Distilabel](https://distilabel.argilla.io/dev/sections/pipeline_samples/) ：一个用于生成合成数据的框架。它还包含对 UltraFeedback 等论文的有趣复现。
- [Semhash](https://github.com/MinishLab/semhash) by MinishLab: Minimalistic library for near-deduplication and decontamination with a distilled embedding model.  
	[Semhash](https://github.com/MinishLab/semhash) by MinishLab：一个极简的库，用于近乎去重和去污染，采用精简的嵌入模型。
- [Chat Template](https://huggingface.co/docs/transformers/main/en/chat_templating) by Hugging Face: Hugging Face's documentation about chat templates.  
	Hugging Face 的 [聊天模板](https://huggingface.co/docs/transformers/main/en/chat_templating) ：Hugging Face 关于聊天模板的文档。

---

### 4\. Supervised Fine-Tuning4. 监督式微调

---

SFT turns base models into helpful assistants, capable of answering questions and following instructions. During this process, they learn how to structure answers and reactivate a subset of knowledge learned during pre-training.  
SFT 将基础模型转化为能够回答问题和执行指令的实用助手。在此过程中，它们学习如何构建答案，并重新激活预训练期间学习到的部分知识。  
Instilling new knowledge is possible but superficial: it cannot be used to learn a completely new language.  
灌输新知识是可能的，但却是肤浅的：它不能用来学习一门全新的语言。  
Always prioritize data quality over parameter optimization.  
始终将数据质量置于参数优化之上。

---

---

- **Training techniques**: Full fine-tuning updates all model parameters but requires significant compute. Parameter-efficient fine-tuning techniques like LoRA and QLoRA reduce memory requirements by training a small number of adapter parameters while keeping base weights frozen.  
	**训练方法** ：完全微调会更新所有模型参数，但需要大量的计算资源。参数高效的微调方法，例如 LoRA 和 QLoRA，通过训练少量适配器参数并保持基础权重不变来降低内存需求。  
	QLoRA combines 4-bit quantization with LoRA to reduce VRAM usage.  
	QLoRA 将 4 位量化与 LoRA 相结合，以减少 VRAM 使用量。  
	These techniques are all implemented in the most popular fine-tuning frameworks:[TRL](https://huggingface.co/docs/trl/en/index), [Unsloth](https://docs.unsloth.ai/), and [Axolotl](https://axolotl.ai/).  
	这些技术都在最流行的微调框架中得到实现： [TRL](https://huggingface.co/docs/trl/en/index) 、 [Unsloth](https://docs.unsloth.ai/) 和 [Axolotl](https://axolotl.ai/) 。

---

- **Training parameters**: Key parameters include learning rate with schedulers, batch size, gradient accumulation, number of epochs, optimizer (like 8-bit AdamW), weight decay for regularization, and warmup steps for training stability.  
	**训练参数** ：关键参数包括学习率（带调度器）、批大小、梯度累积、轮数、优化器（如 8 位 AdamW）、正则化权重衰减以及训练稳定性预热步骤。  
	LoRA also adds three parameters: rank (typically 16-128), alpha (1-2x rank), and target modules.  
	LoRA 还增加了三个参数：rank（通常为 16-128）、alpha（rank 的 1-2 倍）和目标模块。

---

- **Distributed training**: Scale training across multiple GPUs using DeepSpeed or FSDP. DeepSpeed provides three ZeRO optimization stages with increasing levels of memory efficiency through state partitioning. Both methods support gradient checkpointing for memory efficiency.  
	**分布式训练** ：使用 DeepSpeed 或 FSDP 在多个 GPU 上扩展训练规模。DeepSpeed 提供三个 ZeRO 优化阶段，通过状态划分逐步提高内存效率。两种方法都支持梯度检查点以提升内存效率。
- **Monitoring**: Track training metrics including loss curves, learning rate schedules, and gradient norms. Monitor for common issues like loss spikes, gradient explosions, or performance degradation.  
	**监控** ：跟踪训练指标，包括损失曲线、学习率调度和梯度范数。监控常见问题，例如损失峰值、梯度爆炸或性能下降。

📚 **References**:  
📚 **参考文献** ：

- [Fine-tune Llama 3.1 Ultra-Efficiently with Unsloth](https://huggingface.co/blog/mlabonne/sft-llama3) by Maxime Labonne: Hands-on tutorial on how to fine-tune a Llama 3.1 model using Unsloth.  
	Maxime Labonne 的《 [使用 Unsloth 超高效地微调 Llama 3.1》](https://huggingface.co/blog/mlabonne/sft-llama3) ：关于如何使用 Unsloth 微调 Llama 3.1 模型的实践教程。
- [Axolotl - Documentation](https://axolotl-ai-cloud.github.io/axolotl/) by Wing Lian: Lots of interesting information related to distributed training and dataset formats.  
	[墨西哥钝口螈 - Wing Lian 编写的文档](https://axolotl-ai-cloud.github.io/axolotl/) ：包含大量与分布式训练和数据集格式相关的有趣信息。
- [Mastering LLMs](https://parlance-labs.com/education/) by Hamel Husain: Collection of educational resources about fine-tuning (but also RAG, evaluation, applications, and prompt engineering).  
	Hamel Husain 的 [《掌握 LLM》](https://parlance-labs.com/education/) ：关于微调（以及 RAG、评估、应用和提示工程）的教育资源集合。
- [LoRA insights](https://lightning.ai/pages/community/lora-insights/) by Sebastian Raschka: Practical insights about LoRA and how to select the best parameters.  
	Sebastian Raschka 的 [LoRA 见解](https://lightning.ai/pages/community/lora-insights/) ：关于 LoRA 的实用见解以及如何选择最佳参数。

---

### 5\. Preference Alignment5. 偏好一致性

---

Preference alignment is a second stage in the post-training pipeline, focused on aligning generated answers with human preferences. This stage was designed to tune the tone of LLMs and reduce toxicity and hallucinations.  
偏好对齐是训练后流程的第二阶段，其重点在于使生成的答案与人类偏好保持一致。该阶段旨在调整逻辑推理模型（LLM）的语气，并减少其毒性和幻觉。  
However, it has become increasingly important to also boost their performance and improve their usefulness. Unlike SFT, there are many preference alignment algorithms. Here, we'll focus on the three most important ones: DPO, GRPO, and PPO.  
然而，提升它们的性能和实用性也变得越来越重要。与 SFT 不同，偏好对齐算法有很多种。本文将重点介绍其中最重要的三种：DPO、GRPO 和 PPO。

---

- **Rejection sampling**: For each prompt, use the trained model to generate multiple responses, and score them to infer chosen/rejected answers. This creates on-policy data, where both responses come from the model being trained, improving alignment stability.  
	**拒绝采样** ：对于每个提示，使用训练好的模型生成多个响应，并对其进行评分以推断已选择/已拒绝的答案。这创建了策略内数据，其中所有响应均来自正在训练的模型，从而提高了对齐稳定性。
- **[Direct Preference Optimization](https://arxiv.org/abs/2305.18290)** Directly optimizes the policy to maximize the likelihood of chosen responses over rejected ones. It doesn't require reward modeling, which makes it more computationally efficient than RL techniques but slightly worse in terms of quality. Great for creating chat models.  
	**[直接偏好优化](https://arxiv.org/abs/2305.18290)** 直接优化策略，以最大化被选择响应相对于被拒绝响应的概率。它不需要奖励建模，因此比强化学习技术计算效率更高，但质量略逊一筹。非常适合创建聊天模型。
- **Reward model**: Train a reward model with human feedback to predict metrics like human preferences. It can leverage frameworks like [TRL](https://huggingface.co/docs/trl/en/index), [verl](https://github.com/volcengine/verl), and [OpenRLHF](https://github.com/OpenRLHF/OpenRLHF) for scalable training.  
	**奖励模型** ：利用人类反馈训练奖励模型，以预测诸如人类偏好之类的指标。它可以利用 [TRL](https://huggingface.co/docs/trl/en/index) 、 [verl](https://github.com/volcengine/verl) 和 [OpenRLHF](https://github.com/OpenRLHF/OpenRLHF) 等框架进行可扩展的训练。

---

- **Reinforcement Learning**: RL techniques like [GRPO](https://arxiv.org/abs/2402.03300) and [PPO](https://arxiv.org/abs/1707.06347) iteratively update a policy to maximize rewards while staying close to the initial behavior. They can use a reward model or reward functions to score responses.  
	**强化学习** ：诸如 [GRPO](https://arxiv.org/abs/2402.03300) 和 [PPO](https://arxiv.org/abs/1707.06347) 之类的强化学习技术会迭代地更新策略，以在保持接近初始行为的同时最大化奖励。它们可以使用奖励模型或奖励函数来对响应进行评分。  
	They tend to be computationally expensive and require careful tuning of hyperparameters, including learning rate, batch size, and clip range. Ideal for creating reasoning models.  
	它们计算量通常很大，需要仔细调整超参数，包括学习率、批大小和裁剪范围。非常适合用于创建推理模型。

---

📚 **References**:  
📚 **参考文献** ：

- [Illustrating RLHF](https://huggingface.co/blog/rlhf) by Hugging Face: Introduction to RLHF with reward model training and fine-tuning with reinforcement learning.  
	通过 Hugging Face 来 [说明 RLHF](https://huggingface.co/blog/rlhf) ：使用奖励模型训练和强化学习微调来介绍 RLHF。
- [LLM Training: RLHF and Its Alternatives](https://magazine.sebastianraschka.com/p/llm-training-rlhf-and-its-alternatives) by Sebastian Raschka: Overview of the RLHF process and alternatives like RLAIF.  
	[LLM 培训：Sebastian Raschka 的 RLHF 及其替代方案](https://magazine.sebastianraschka.com/p/llm-training-rlhf-and-its-alternatives) ：RLHF 流程概述以及 RLAIF 等替代方案。
- [Preference Tuning LLMs](https://huggingface.co/blog/pref-tuning) by Hugging Face: Comparison of the DPO, IPO, and KTO algorithms to perform preference alignment.  
	通过拥抱面孔 [进行偏好调整 LLM](https://huggingface.co/blog/pref-tuning) ：DPO、IPO 和 KTO 算法在执行偏好对齐方面的比较。
- [Fine-tune with DPO](https://mlabonne.github.io/blog/posts/Fine_tune_Mistral_7b_with_DPO.html) by Maxime Labonne: Tutorial to fine-tune a Mistral-7b model with DPO and reproduce [NeuralHermes-2.5](https://huggingface.co/mlabonne/NeuralHermes-2.5-Mistral-7B).  
	Maxime Labonne 的 [DPO 微调](https://mlabonne.github.io/blog/posts/Fine_tune_Mistral_7b_with_DPO.html) 教程：使用 DPO 微调 Mistral-7b 模型并重现 [NeuralHermes-2.5](https://huggingface.co/mlabonne/NeuralHermes-2.5-Mistral-7B) 。
- [Fine-tune with GRPO](https://huggingface.co/learn/llm-course/en/chapter12/5) by Maxime Labonne: Practical exercise to fine-tune a small model with GRPO.  
	Maxime Labonne 的 [《使用 GRPO 进行微调](https://huggingface.co/learn/llm-course/en/chapter12/5) ：使用 GRPO 微调小型模型的实践练习》。
- [DPO Wandb logs](https://wandb.ai/alexander-vishnevskiy/dpo/reports/TRL-Original-DPO--Vmlldzo1NjI4MTc4) by Alexander Vishnevskiy: It shows you the main DPO metrics to track and the trends you should expect.  
	Alexander Vishnevskiy 的 [DPO Wandb 日志](https://wandb.ai/alexander-vishnevskiy/dpo/reports/TRL-Original-DPO--Vmlldzo1NjI4MTc4) ：它向您展示了要跟踪的主要 DPO 指标以及您应该预期的趋势。

---

### 6\. Evaluation6. 评估

---

Reliably evaluating LLMs is a complex but essential task guiding data generation and training. It provides invaluable feedback about areas of improvement, which can be leveraged to modify the data mixture, quality, and training parameters.  
可靠地评估线性模型是一项复杂但至关重要的任务，它指导着数据的生成和训练。评估结果能够提供关于改进领域的宝贵反馈，这些反馈可用于调整数据混合、质量和训练参数。  
However, it's always good to remember Goodhart's law: "When a measure becomes a target, it ceases to be a good measure."  
然而，我们始终应该记住古德哈特定律：“当一项指标成为目标时，它就不再是一项好的指标了。”

---

- **Automated benchmarks**: Evaluate models on specific tasks using curated datasets and metrics, like MMLU. It works well for concrete tasks but struggles with abstract and creative capabilities. It is also prone to data contamination.  
	**自动化基准测试** ：使用精心挑选的数据集和指标（例如 MMLU）评估模型在特定任务上的性能。它适用于具体任务，但在抽象和创造性能力方面表现不佳。此外，它也容易受到数据污染的影响。
- **Human evaluation**: It involves humans prompting models and grading responses. Methods range from vibe checks to systematic annotations with specific guidelines and large-scale community voting (arena). It is more suited for subjective tasks and less reliable for factual accuracy.  
	**人工评估** ：这种方法涉及人工引导模型并对模型的响应进行评分。评估方法包括感觉检查、使用特定指南进行系统标注以及大规模社区投票（例如 Arena）。这种方法更适合主观性任务，但在事实准确性方面可靠性较低。
- **Model-based evaluation**: Use judge and reward models to evaluate model outputs. It highly correlates with human preferences but suffers from bias toward their own outputs and inconsistent scoring.  
	**基于模型的评估** ：使用评判和奖励模型来评估模型输出。它与人类偏好高度相关，但存在偏向自身输出和评分不一致的问题。
- **Feedback signal**: Analyze error patterns to identify specific weaknesses, such as limitations in following complex instructions, lack of specific knowledge, or susceptibility to adversarial prompts. This can be improved with better data generation and training parameters.  
	**反馈信号** ：分析错误模式以识别具体弱点，例如难以遵循复杂指令、缺乏特定知识或容易受到对抗性提示的影响。这可以通过改进数据生成和训练参数来提升。

📚 **References**:  
📚 **参考文献** ：

- [LLM evaluation guidebook](https://huggingface.co/spaces/OpenEvals/evaluation-guidebook) by Hugging Face: Comprehensive guide about evaluation with practical insights.  
	Hugging Face 出版的 [LLM 评估指南](https://huggingface.co/spaces/OpenEvals/evaluation-guidebook) ：提供具有实用见解的全面评估指南。
- [Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) by Hugging Face: Main leaderboard to compare LLMs in an open and reproducible way (automated benchmarks).  
	Hugging Face 的 [Open LLM 排行榜](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) ：以开放和可复现的方式（自动化基准测试）比较 LLM 的主要排行榜。
- [Language Model Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness) by EleutherAI: A popular framework for evaluating LLMs using automated benchmarks.  
	EleutherAI 的 [Language Model Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness) ：一个使用自动化基准测试来评估 LLM 的流行框架。
- [Lighteval](https://github.com/huggingface/lighteval) by Hugging Face: Alternative evaluation framework that also includes model-based evaluations.  
	Hugging Face 的 [Lighteval](https://github.com/huggingface/lighteval) ：一种替代评估框架，也包括基于模型的评估。
- [Chatbot Arena](https://lmarena.ai/) by LMSYS: Elo rating of general-purpose LLMs, based on comparisons made by humans (human evaluation).  
	LMSYS 的 [Chatbot Arena](https://lmarena.ai/) ：基于人类比较（人工评估）的通用 LLM 的 Elo 评级。

---

### 7\. Quantization7. 量化

---

Quantization is the process of converting the parameters and activations of a model to a lower precision. For example, weights stored using 16 bits can be converted into a 4-bit representation.  
量化是将模型的参数和激活值转换为较低精度的过程。例如，用 16 位存储的权重可以转换为 4 位表示。  
This technique has become increasingly important to reduce the computational and memory costs associated with LLMs.  
该技术对于降低 LLM 相关的计算和内存成本变得越来越重要。

---

- **Base techniques**: Learn the different levels of precision (FP32, FP16, INT8, etc.) and how to perform naïve quantization with absmax and zero-point techniques.  
	**基础技术** ：学习不同精度级别（FP32、FP16、INT8 等）以及如何使用 absmax 和零点技术进行朴素量化。
- **GGUF & llama.cpp**: Originally designed to run on CPUs, [llama.cpp](https://github.com/ggerganov/llama.cpp) and the GGUF format have become the most popular tools to run LLMs on consumer-grade hardware. It supports storing special tokens, vocabulary, and metadata in a single file.  
	**GGUF 和 llama.cpp** ： [llama.cpp](https://github.com/ggerganov/llama.cpp) 和 GGUF 格式最初设计用于在 CPU 上运行，如今已成为在消费级硬件上运行语言语言模型 (LLM) 的最流行工具。它支持将特殊标记、词汇表和元数据存储在单个文件中。
- **GPTQ & AWQ**: Techniques like [GPTQ](https://arxiv.org/abs/2210.17323) / [EXL2](https://github.com/turboderp/exllamav2) and [AWQ](https://arxiv.org/abs/2306.00978) introduce layer-by-layer calibration that retains performance at extremely low bitwidths. They reduce catastrophic outliers using dynamic scaling, selectively skipping or re-centering the heaviest parameters.  
	**GPTQ 和 AWQ** ： [GPTQ](https://arxiv.org/abs/2210.17323) / [EXL2](https://github.com/turboderp/exllamav2) 和 [AWQ](https://arxiv.org/abs/2306.00978) 等技术引入了逐层校准，即使在极低的位宽下也能保持性能。它们通过动态缩放来减少灾难性的异常值，选择性地跳过或重新调整最耗资源的参数。
- **SmoothQuant & ZeroQuant**: New quantization-friendly transformations (SmoothQuant) and compiler-based optimizations (ZeroQuant) help mitigate outliers before quantization. They also reduce hardware overhead by fusing certain ops and optimizing dataflow.  
	**SmoothQuant 和 ZeroQuant** ：新的量化友好型转换（SmoothQuant）和基于编译器的优化（ZeroQuant）有助于在量化之前缓解异常值问题。它们还通过融合某些操作和优化数据流来降低硬件开销。

📚 **References**:  
📚 **参考文献** ：

- [Introduction to quantization](https://mlabonne.github.io/blog/posts/Introduction_to_Weight_Quantization.html) by Maxime Labonne: Overview of quantization, absmax and zero-point quantization, and LLM.int8() with code.  
	Maxime Labonne 的 [量化入门](https://mlabonne.github.io/blog/posts/Introduction_to_Weight_Quantization.html) ：量化概述、绝对最大值和零点量化，以及 LLM.int8() 代码。
- [Quantize Llama models with llama.cpp](https://mlabonne.github.io/blog/posts/Quantize_Llama_2_models_using_ggml.html) by Maxime Labonne: Tutorial on how to quantize a Llama 2 model using llama.cpp and the GGUF format.  
	Maxime Labonne 的教程：如何使用 llama.cpp 和 GGUF 格式 [量化 Llama 2 模型](https://mlabonne.github.io/blog/posts/Quantize_Llama_2_models_using_ggml.html) 。
- [4-bit LLM Quantization with GPTQ](https://mlabonne.github.io/blog/posts/4_bit_Quantization_with_GPTQ.html) by Maxime Labonne: Tutorial on how to quantize an LLM using the GPTQ algorithm with AutoGPTQ.  
	Maxime Labonne 的 [GPTQ 4 位 LLM 量化](https://mlabonne.github.io/blog/posts/4_bit_Quantization_with_GPTQ.html) 教程：如何使用 AutoGPTQ 和 GPTQ 算法量化 LLM。
- [Understanding Activation-Aware Weight Quantization](https://medium.com/friendliai/understanding-activation-aware-weight-quantization-awq-boosting-inference-serving-efficiency-in-10bb0faf63a8) by FriendliAI: Overview of the AWQ technique and its benefits.  
	[了解 FriendliAI 的激活感知权重量化](https://medium.com/friendliai/understanding-activation-aware-weight-quantization-awq-boosting-inference-serving-efficiency-in-10bb0faf63a8) ：AWQ 技术概述及其优势。
- [SmoothQuant on Llama 2 7B](https://github.com/mit-han-lab/smoothquant/blob/main/examples/smoothquant_llama_demo.ipynb) by MIT HAN Lab: Tutorial on how to use SmoothQuant with a Llama 2 model in 8-bit precision.  
	[SmoothQuant on Llama 2 7B](https://github.com/mit-han-lab/smoothquant/blob/main/examples/smoothquant_llama_demo.ipynb) by MIT HAN Lab: Tutorial on how to use SmoothQuant with a Llama 2 model in 8 bit precision.
- [DeepSpeed Model Compression](https://www.deepspeed.ai/tutorials/model-compression/) by DeepSpeed: Tutorial on how to use ZeroQuant and extreme compression (XTC) with DeepSpeed Compression.  
	[DeepSpeed 模型压缩](https://www.deepspeed.ai/tutorials/model-compression/) （DeepSpeed 出品）：如何将 ZeroQuant 和极限压缩 (XTC) 与 DeepSpeed 压缩结合使用的教程。

---

### 8\. New Trends8. 新趋势

Here are notable topics that didn't fit into other categories. Some are established techniques (model merging, multimodal), but others are more experimental (interpretability, test-time compute scaling) and the focus of numerous research papers.  
以下是一些值得关注的主题，它们不属于其他类别。有些是成熟的技术（例如模型融合、多模态），而另一些则更具实验性（例如可解释性、测试时计算扩展），也是众多研究论文的重点。

- **Model merging**: Merging trained models has become a popular way of creating performant models without any fine-tuning. The popular [mergekit](https://github.com/cg123/mergekit) library implements the most popular merging methods, like SLERP, [DARE](https://arxiv.org/abs/2311.03099), and [TIES](https://arxiv.org/abs/2311.03099).  
	**模型合并** ：合并已训练好的模型已成为一种无需微调即可创建高性能模型的流行方法。流行的 [mergekit](https://github.com/cg123/mergekit) 库实现了最常用的合并方法，例如 SLERP、 [DARE](https://arxiv.org/abs/2311.03099) 和 [TIES](https://arxiv.org/abs/2311.03099) 。
- **Multimodal models**: These models (like [CLIP](https://openai.com/research/clip), [Stable Diffusion](https://stability.ai/stable-image), or [LLaVA](https://llava-vl.github.io/)) process multiple types of inputs (text, images, audio, etc.) with a unified embedding space, which unlocks powerful applications like text-to-image.  
	**多模态模型** ：这些模型（如 [CLIP](https://openai.com/research/clip) 、 [稳定扩散](https://stability.ai/stable-image) 或 [LLaVA](https://llava-vl.github.io/) ）使用统一的嵌入空间处理多种类型的输入（文本、图像、音频等），从而解锁了强大的应用，如文本到图像。

---

- **Interpretability**: Mechanistic interpretability techniques like Sparse Autoencoders (SAEs) have made remarkable progress to provide insights about the inner workings of LLMs.  
	**可解释性** ：稀疏自编码器 (SAE) 等机制可解释性技术取得了显著进展，为深入了解 LLM 的内部运作提供了见解。  
	This has also been applied with techniques such as abliteration, which allow you to modify the behavior of models without training.  
	这种方法也应用于诸如抹除之类的技术，该技术允许你在不进行训练的情况下修改模型的行为。

---

- **Test-time compute**: Reasoning models trained with RL techniques can be further improved by scaling the compute budget during test time. It can involve multiple calls, MCTS, or specialized models like a Process Reward Model (PRM).  
	**测试时计算** ：利用强化学习技术训练的推理模型可以通过在测试时增加计算预算来进一步改进。这可能涉及多次调用、蒙特卡洛测试集（MCTS）或诸如进程奖励模型（PRM）之类的专用模型。  
	Iterative steps with precise scoring significantly improve performance for complex reasoning tasks.  
	采用精确评分的迭代步骤可以显著提高复杂推理任务的性能。

---

📚 **References**:  
📚 **参考文献** ：

- [Merge LLMs with mergekit](https://mlabonne.github.io/blog/posts/2024-01-08_Merge_LLMs_with_mergekit.html) by Maxime Labonne: Tutorial about model merging using mergekit.  
	[使用 mergekit 合并 LLMs](https://mlabonne.github.io/blog/posts/2024-01-08_Merge_LLMs_with_mergekit.html) （Maxime Labonne 著）：关于使用 mergekit 进行模型合并的教程。
- [Smol Vision](https://github.com/merveenoyan/smol-vision) by Merve Noyan: Collection of notebooks and scripts dedicated to small multimodal models.  
	Merve Noyan 的 [Smol Vision](https://github.com/merveenoyan/smol-vision) ：专门用于小型多模态模型的笔记本和脚本集合。
- [Large Multimodal Models](https://huyenchip.com/2023/10/10/multimodal.html) by Chip Huyen: Overview of multimodal systems and the recent history of this field.  
	Chip Huyen 的 [《大型多模态模型》](https://huyenchip.com/2023/10/10/multimodal.html) ：多模态系统概述及该领域的最新发展历程。
- [Unsensor any LLM with abliteration](https://huggingface.co/blog/mlabonne/abliteration) by Maxime Labonne: Direct application of interpretability techniques to modify the style of a model.  
	Maxime Labonne 的 [《Unsensor any LLM with abliteration》](https://huggingface.co/blog/mlabonne/abliteration) ：直接应用可解释性技术来修改模型的风格。
- [Intuitive Explanation of SAEs](https://adamkarvonen.github.io/machine_learning/2024/06/11/sae-intuitions.html) by Adam Karvonen: Article about how SAEs work and why they make sense for interpretability.  
	Adam Karvonen 对 [SAE 的直观解释](https://adamkarvonen.github.io/machine_learning/2024/06/11/sae-intuitions.html) ：本文介绍了 SAE 的工作原理以及它们为何对可解释性有意义。
- [Scaling test-time compute](https://huggingface.co/spaces/HuggingFaceH4/blogpost-scaling-test-time-compute) by Beeching et al.: Tutorial and experiments to outperform Llama 3.1 70B on MATH-500 with a 3B model.  
	Beeching 等人 [扩展测试时计算](https://huggingface.co/spaces/HuggingFaceH4/blogpost-scaling-test-time-compute) ：教程和实验，使用 3B 模型在 MATH-500 上超越 Llama 3.1 70B。

## 👷 The LLM Engineer👷 法学硕士工程师

This section of the course focuses on learning how to build LLM-powered applications that can be used in production, with a focus on augmenting models and deploying them.  
本课程的这一部分重点学习如何构建可在生产环境中使用的 LLM 应用程序，重点是增强模型和部署模型。

[![](https://github.com/mlabonne/llm-course/raw/main/img/roadmap_engineer.png)](https://github.com/mlabonne/llm-course/blob/main/img/roadmap_engineer.png)

### 1\. Running LLMs1. 运行 LLM

---

Running LLMs can be difficult due to high hardware requirements. Depending on your use case, you might want to simply consume a model through an API (like GPT-4) or run it locally.  
由于硬件要求高，运行低层模型可能比较困难。根据您的具体应用场景，您可能只想通过 API 使用模型（例如 GPT-4），或者在本地运行模型。  
In any case, additional prompting and guidance techniques can improve and constrain the output for your applications.  
总之，额外的提示和指导技术可以改进和限制应用程序的输出。

---

- **LLM APIs**: APIs are a convenient way to deploy LLMs. This space is divided between private LLMs ([OpenAI](https://platform.openai.com/), [Google](https://cloud.google.com/vertex-ai/docs/generative-ai/learn/overview), [Anthropic](https://docs.anthropic.com/claude/reference/getting-started-with-the-api), etc.) and open-source LLMs ([OpenRouter](https://openrouter.ai/), [Hugging Face](https://huggingface.co/inference-api), [Together AI](https://www.together.ai/), etc.).  
	**LLM API** ：API 是部署 LLM 的一种便捷方式。该领域分为私有 LLM（ [OpenAI](https://platform.openai.com/) 、 [Google](https://cloud.google.com/vertex-ai/docs/generative-ai/learn/overview) 、 [Anthropic](https://docs.anthropic.com/claude/reference/getting-started-with-the-api) 等）和开源 LLM（ [OpenRouter](https://openrouter.ai/) 、 [Hugging Face](https://huggingface.co/inference-api) 、 [Together AI](https://www.together.ai/) 等）。
- **Open-source LLMs**: The [Hugging Face Hub](https://huggingface.co/models) is a great place to find LLMs. You can directly run some of them in [Hugging Face Spaces](https://huggingface.co/spaces), or download and run them locally in apps like [LM Studio](https://lmstudio.ai/) or through the CLI with [llama.cpp](https://github.com/ggerganov/llama.cpp) or [ollama](https://ollama.ai/).  
	**开源 LLM** ： [Hugging Face Hub](https://huggingface.co/models) 是寻找 LLM 的好地方。您可以直接在 [Hugging Face Spaces](https://huggingface.co/spaces) 中运行其中一些，或者下载它们并在本地应用程序中使用 [LM Studio](https://lmstudio.ai/) 或通过 CLI 使用 [llama.cpp](https://github.com/ggerganov/llama.cpp) 或 [ollama](https://ollama.ai/) 运行。
- **Prompt engineering**: Common techniques include zero-shot prompting, few-shot prompting, chain of thought, and ReAct. They work better with bigger models, but can be adapted to smaller ones.  
	**提示工程** ：常用技术包括零样本提示、少样本提示、思维链和 ReAct。它们在大型模型中效果更佳，但也可以应用于小型模型。
- **Structuring outputs**: Many tasks require a structured output, like a strict template or a JSON format. Libraries like [Outlines](https://github.com/outlines-dev/outlines) can be used to guide the generation and respect a given structure. Some APIs also support structured output generation natively using JSON schemas.  
	**输出结构化** ：许多任务需要结构化的输出，例如严格的模板或 JSON 格式。可以使用 [Outlines](https://github.com/outlines-dev/outlines) 等库来指导输出生成并遵循给定的结构。一些 API 也原生支持使用 JSON 模式生成结构化输出。

📚 **References**:  
📚 **参考文献** ：

- [Run an LLM locally with LM Studio](https://www.kdnuggets.com/run-an-llm-locally-with-lm-studio) by Nisha Arya: Short guide on how to use LM Studio.  
	Nisha Arya 的《 [使用 LM Studio 在本地运行 LLM](https://www.kdnuggets.com/run-an-llm-locally-with-lm-studio) ：LM Studio 使用方法简明指南》。
- [Prompt engineering guide](https://www.promptingguide.ai/) by DAIR.AI: Exhaustive list of prompt techniques with examples  
	DAIR.AI 出品的 [提示工程指南](https://www.promptingguide.ai/) ：提示技术详尽列表及示例
- [Outlines - Quickstart](https://dottxt-ai.github.io/outlines/latest/quickstart/): List of guided generation techniques enabled by Outlines.  
	[大纲 - 快速入门](https://dottxt-ai.github.io/outlines/latest/quickstart/) ：大纲支持的引导式生成技术列表。
- [LMQL - Overview](https://lmql.ai/docs/language/overview.html): Introduction to the LMQL language.  
	[LMQL - 概述](https://lmql.ai/docs/language/overview.html) ：LMQL 语言简介。

---

### 2\. Building a Vector Storage2. 构建矢量存储

Creating a vector storage is the first step to building a Retrieval Augmented Generation (RAG) pipeline. Documents are loaded, split, and relevant chunks are used to produce vector representations (embeddings) that are stored for future use during inference.  
创建向量存储是构建检索增强生成（RAG）流程的第一步。文档被加载、分割，并使用相关的数据块生成向量表示（嵌入），这些向量表示将被存储起来，以便在推理过程中使用。

- **Ingesting documents**: Document loaders are convenient wrappers that can handle many formats: PDF, JSON, HTML, Markdown, etc. They can also directly retrieve data from some databases and APIs (GitHub, Reddit, Google Drive, etc.).  
	**导入文档** ：文档加载器是方便的封装器，可以处理多种格式：PDF、JSON、HTML、Markdown 等。它们还可以直接从一些数据库和 API（GitHub、Reddit、Google Drive 等）检索数据。
- **Splitting documents**: Text splitters break down documents into smaller, semantically meaningful chunks. Instead of splitting text after *n* characters, it's often better to split by header or recursively, with some additional metadata.  
	**文档分割** ：文本分割器将文档拆分成更小、语义更有意义的片段。通常情况下，与其按 *n 个* 字符分割文本，不如按标题或递归方式分割，并添加一些元数据。
- **Embedding models**: Embedding models convert text into vector representations. Picking task-specific models significantly improves performance for semantic search and RAG.  
	**嵌入模型** ：嵌入模型将文本转换为向量表示。选择特定任务的模型可以显著提高语义搜索和随机数生成器（RAG）的性能。
- **Vector databases**: Vector databases (like [Chroma](https://www.trychroma.com/), [Pinecone](https://www.pinecone.io/), [Milvus](https://milvus.io/), [FAISS](https://faiss.ai/), [Annoy](https://github.com/spotify/annoy), etc.) are designed to store embedding vectors. They enable efficient retrieval of data that is 'most similar' to a query based on vector similarity.  
	**向量数据库** ：向量数据库（如 [Chroma](https://www.trychroma.com/) 、 [Pinecone](https://www.pinecone.io/) 、 [Milvus](https://milvus.io/) 、 [FAISS](https://faiss.ai/) 、 [Annoy](https://github.com/spotify/annoy) 等）旨在存储嵌入向量。它们能够基于向量相似性，高效地检索与查询“最相似”的数据。

📚 **References**:  
📚 **参考文献** ：

- [LangChain - Text splitters](https://python.langchain.com/docs/how_to/#text-splitters): List of different text splitters implemented in LangChain.  
	[LangChain - 文本分割器](https://python.langchain.com/docs/how_to/#text-splitters) ：LangChain 中实现的不同文本分割器列表。
- [Sentence Transformers library](https://www.sbert.net/): Popular library for embedding models.  
	[Sentence Transformers 库](https://www.sbert.net/) ：流行的嵌入模型库。
- [MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard): Leaderboard for embedding models.  
	[MTEB 排行榜](https://huggingface.co/spaces/mteb/leaderboard) ：嵌入模型排行榜。
- [The Top 7 Vector Databases](https://www.datacamp.com/blog/the-top-5-vector-databases) by Moez Ali: A comparison of the best and most popular vector databases.  
	Moez Ali 评选的 [7 大矢量数据库](https://www.datacamp.com/blog/the-top-5-vector-databases) ：最佳和最受欢迎的矢量数据库对比。

---

### 3\. Retrieval Augmented Generation3. 检索增强生成

With RAG, LLMs retrieve contextual documents from a database to improve the accuracy of their answers. RAG is a popular way of augmenting the model's knowledge without any fine-tuning.  
RAG（评级赋值生成）技术使逻辑学习模型（LLM）能够从数据库中检索上下文文档，从而提高其答案的准确性。RAG 是一种无需任何微调即可增强模型知识的常用方法。

- **Orchestrators**: Orchestrators like [LangChain](https://python.langchain.com/docs/get_started/introduction) and [LlamaIndex](https://docs.llamaindex.ai/en/stable/) are popular frameworks to connect your LLMs with tools and databases. The Model Context Protocol (MCP) introduces a new standard to pass data and context to models across providers.  
	**编排器** ：像 [LangChain](https://python.langchain.com/docs/get_started/introduction) 和 [LlamaIndex](https://docs.llamaindex.ai/en/stable/) 这样的编排器是连接 LLM 模型与工具和数据库的常用框架。模型上下文协议 (MCP) 引入了一种新的标准，用于在不同提供商之间传递数据和上下文信息。
- **Retrievers**: Query rewriters and generative retrievers like CoRAG and HyDE enhance search by transforming user queries. Multi-vector and hybrid retrieval methods combine embeddings with keyword signals to improve recall and precision.  
	**检索器** ：查询重写器和生成式检索器（例如 CoRAG 和 HyDE）通过转换用户查询来增强搜索效果。多向量和混合检索方法将词嵌入与关键词信号相结合，以提高召回率和精确率。
- **Memory**: To remember previous instructions and answers, LLMs and chatbots like ChatGPT add this history to their context window. This buffer can be improved with summarization (e.g., using a smaller LLM), a vector store + RAG, etc.  
	**记忆** ：为了记住之前的指令和答案，LLM 和 ChatGPT 等聊天机器人会将这些历史记录添加到上下文窗口中。可以通过摘要（例如，使用更小的 LLM）、向量存储 + RAG 等方式来改进此缓冲区。
- **Evaluation**: We need to evaluate both the document retrieval (context precision and recall) and the generation stages (faithfulness and answer relevancy). It can be simplified with tools [Ragas](https://github.com/explodinggradients/ragas/tree/main) and [DeepEval](https://github.com/confident-ai/deepeval) (assessing quality).  
	**评估** ：我们需要评估文档检索阶段（上下文精确度和召回率）以及生成阶段（忠实度和答案相关性）。可以使用 [Ragas](https://github.com/explodinggradients/ragas/tree/main) 和 [DeepEval 等](https://github.com/confident-ai/deepeval) 工具（质量评估）简化评估过程。

📚 **References**:  
📚 **参考文献** ：

- [Llamaindex - High-level concepts](https://docs.llamaindex.ai/en/stable/getting_started/concepts.html): Main concepts to know when building RAG pipelines.  
	[Llamaindex - 高级概念](https://docs.llamaindex.ai/en/stable/getting_started/concepts.html) ：构建 RAG 流水线时需要了解的主要概念。
- [Model Context Protocol](https://modelcontextprotocol.io/introduction): Introduction to MCP with motivate, architecture, and quick starts.  
	[模型上下文协议](https://modelcontextprotocol.io/introduction) ：MCP 简介，包括动机、架构和快速入门。
- [Pinecone - Retrieval Augmentation](https://www.pinecone.io/learn/series/langchain/langchain-retrieval-augmentation/): Overview of the retrieval augmentation process.  
	[松果 - 检索增强](https://www.pinecone.io/learn/series/langchain/langchain-retrieval-augmentation/) ：检索增强过程概述。
- [LangChain - Q&A with RAG](https://python.langchain.com/docs/tutorials/rag/): Step-by-step tutorial to build a typical RAG pipeline.  
	[LangChain - RAG 问答](https://python.langchain.com/docs/tutorials/rag/) ：构建典型 RAG 流水线的逐步教程。
- [LangChain - Memory types](https://python.langchain.com/docs/how_to/chatbots_memory/): List of different types of memories with relevant usage.  
	[LangChain - 内存类型](https://python.langchain.com/docs/how_to/chatbots_memory/) ：不同类型内存及其相关用途的列表。
- [RAG pipeline - Metrics](https://docs.ragas.io/en/stable/concepts/metrics/index.html): Overview of the main metrics used to evaluate RAG pipelines.  
	[RAG 流水线 - 指标](https://docs.ragas.io/en/stable/concepts/metrics/index.html) ：用于评估 RAG 流水线的主要指标概述。

---

### 4\. Advanced RAG4. 高级 RAG

Real-life applications can require complex pipelines, including SQL or graph databases, as well as automatically selecting relevant tools and APIs. These advanced techniques can improve a baseline solution and provide additional features.  
实际应用可能需要复杂的流程，包括 SQL 或图数据库，以及自动选择相关工具和 API。这些高级技术可以改进基础解决方案并提供更多功能。

- **Query construction**: Structured data stored in traditional databases requires a specific query language like SQL, Cypher, metadata, etc. We can directly translate the user instruction into a query to access the data with query construction.  
	**查询构建** ：传统数据库中存储的结构化数据需要特定的查询语言，例如 SQL、Cypher、元数据等。我们可以通过查询构建将用户指令直接转换为查询语句来访问数据。
- **Tools**: Agents augment LLMs by automatically selecting the most relevant tools to provide an answer. These tools can be as simple as using Google or Wikipedia, or more complex, like a Python interpreter or Jira.  
	**工具** ：智能体通过自动选择最相关的工具来提供答案，从而增强学习生命周期模型（LLM）的功能。这些工具可以很简单，例如使用谷歌或维基百科，也可以更复杂，例如使用 Python 解释器或 Jira。
- **Post-processing**: Final step that processes the inputs that are fed to the LLM. It enhances the relevance and diversity of documents retrieved with re-ranking, [RAG-fusion](https://github.com/Raudaschl/rag-fusion), and classification.  
	**后处理** ：处理输入到 LLM 的最终步骤。它通过重排序、 [RAG 融合](https://github.com/Raudaschl/rag-fusion) 和分类来增强检索到的文档的相关性和多样性。
- **Program LLMs**: Frameworks like [DSPy](https://github.com/stanfordnlp/dspy) allow you to optimize prompts and weights based on automated evaluations in a programmatic way.  
	**程序化学习学习模型** ：像 [DSPy](https://github.com/stanfordnlp/dspy) 这样的框架允许您以程序化的方式，根据自动评估来优化提示和权重。

📚 **References**:  
📚 **参考文献** ：

- [LangChain - Query Construction](https://blog.langchain.dev/query-construction/): Blog post about different types of query construction.  
	[LangChain - 查询构造](https://blog.langchain.dev/query-construction/) ：一篇关于不同类型查询构造的博客文章。
- [LangChain - SQL](https://python.langchain.com/docs/tutorials/sql_qa/): Tutorial on how to interact with SQL databases with LLMs, involving Text-to-SQL and an optional SQL agent.  
	[LangChain - SQL](https://python.langchain.com/docs/tutorials/sql_qa/) ：关于如何使用 LLM 与 SQL 数据库交互的教程，涉及文本到 SQL 和可选的 SQL 代理。
- [Pinecone - LLM agents](https://www.pinecone.io/learn/series/langchain/langchain-agents/): Introduction to agents and tools with different types.  
	[Pinecone - LLM 代理](https://www.pinecone.io/learn/series/langchain/langchain-agents/) ：介绍不同类型的代理和工具。
- [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/) by Lilian Weng: A more theoretical article about LLM agents.  
	Lilian Weng 的 [LLM 驱动的自主代理](https://lilianweng.github.io/posts/2023-06-23-agent/) ：一篇关于 LLM 代理的理论性文章。
- [LangChain - OpenAI's RAG](https://blog.langchain.dev/applying-openai-rag/): Overview of the RAG strategies employed by OpenAI, including post-processing.  
	[LangChain - OpenAI 的 RAG](https://blog.langchain.dev/applying-openai-rag/) ：概述 OpenAI 所采用的 RAG 策略，包括后处理。
- [DSPy in 8 Steps](https://dspy-docs.vercel.app/docs/building-blocks/solving_your_task): General-purpose guide to DSPy introducing modules, signatures, and optimizers.  
	[DSPy 八步入门](https://dspy-docs.vercel.app/docs/building-blocks/solving_your_task) ：DSPy 通用指南，介绍模块、签名和优化器。

---

### 5\. Agents5. 代理人

An LLM agent can autonomously perform tasks by taking actions based on reasoning about its environment, typically through the use of tools or functions to interact with external systems.  
LLM 代理能够根据对环境的推理采取行动，自主地执行任务，通常是通过使用工具或功能与外部系统交互。

- **Agent fundamentals**: Agents operate using thoughts (internal reasoning to decide what to do next), action (executing tasks, often by interacting with external tools), and observation (analyzing feedback or results to refine the next step).  
	**智能体的基本原理** ：智能体通过思考（内部推理来决定下一步做什么）、行动（执行任务，通常通过与外部工具交互）和观察（分析反馈或结果来改进下一步）来运作。
- **Agent protocols**: [Model Context Protocol](https://modelcontextprotocol.io/) (MCP) is the industry standard for connecting agents to external tools and data sources with MCP servers and clients. More recently, [Agent2Agent](https://a2a-protocol.org/) (A2A) tries to standardize a common language for agent interoperability.  
	**代理协议** ： [模型上下文协议](https://modelcontextprotocol.io/) (MCP) 是业界标准，它使用 MCP 服务器和客户端将代理连接到外部工具和数据源。最近， [Agent2Agent](https://a2a-protocol.org/) (A2A) 尝试为代理互操作性制定通用语言。
- **Vendor frameworks**: Each major cloud model provider has its own agentic framework with [OpenAI SDK](https://openai.github.io/openai-agents-python/), [Google ADK](https://google.github.io/adk-docs/), and [Claude Agent SDK](https://platform.claude.com/docs/en/agent-sdk/overview) if you're particularly tied to one vendor.  
	**供应商框架** ：每个主要的云模型提供商都有自己的代理框架，如果您特别依赖于某个供应商，可以使用 [OpenAI SDK](https://openai.github.io/openai-agents-python/) 、 [Google ADK](https://google.github.io/adk-docs/) 和 [Claude Agent SDK](https://platform.claude.com/docs/en/agent-sdk/overview) 。
- **Other frameworks**: Agent development can be streamlined using different frameworks like [LangGraph](https://www.langchain.com/langgraph) (design and visualization of workflows) [LlamaIndex](https://docs.llamaindex.ai/en/stable/use_cases/agents/) (data-augmented agents with RAG), or custom solutions. More experimental frameworks include collaboration between different agents, such as [CrewAI](https://docs.crewai.com/introduction) (role-based team workflows) and [AutoGen](https://github.com/microsoft/autogen) (conversation-driven multi-agent systems).  
	**其他框架** ：可以使用不同的框架来简化代理开发，例如 [LangGraph](https://www.langchain.com/langgraph) （工作流的设计和可视化）、 [LlamaIndex](https://docs.llamaindex.ai/en/stable/use_cases/agents/) （基于 RAG 的数据增强型代理）或自定义解决方案。更具实验性的框架包括不同代理之间的协作，例如 [CrewAI](https://docs.crewai.com/introduction) （基于角色的团队工作流）和 [AutoGen](https://github.com/microsoft/autogen) （对话驱动的多代理系统）。

📚 **References**:  
📚 **参考文献** ：

- [Agents Course](https://huggingface.co/learn/agents-course/unit0/introduction): Popular course about AI agents made by Hugging Face.  
	[智能体课程](https://huggingface.co/learn/agents-course/unit0/introduction) ：由 Hugging Face 制作的关于人工智能智能体的热门课程。
- [LangGraph](https://langchain-ai.github.io/langgraph/concepts/why-langgraph/): Overview of how to build AI agents with LangGraph.  
	[LangGraph](https://langchain-ai.github.io/langgraph/concepts/why-langgraph/) ：如何使用 LangGraph 构建 AI 代理概述。
- [LlamaIndex Agents](https://docs.llamaindex.ai/en/stable/use_cases/agents/): Uses cases and resources to build agents with LlamaIndex.  
	[LlamaIndex Agents](https://docs.llamaindex.ai/en/stable/use_cases/agents/) ：使用 LlamaIndex 构建代理的用例和资源。

---

### 6\. Inference optimization6. 推理优化

Text generation is a costly process that requires expensive hardware. In addition to quantization, various techniques have been proposed to maximize throughput and reduce inference costs.  
文本生成是一个成本高昂的过程，需要昂贵的硬件。除了量化之外，人们还提出了各种技术来最大限度地提高吞吐量并降低推理成本。

- **Flash Attention**: Optimization of the attention mechanism to transform its complexity from quadratic to linear, speeding up both training and inference.  
	**闪光注意力** ：优化注意力机制，将其复杂度从二次方转化为线性，从而加快训练和推理速度。
- **Key-value cache**: Understand the key-value cache and the improvements introduced in [Multi-Query Attention](https://arxiv.org/abs/1911.02150) (MQA) and [Grouped-Query Attention](https://arxiv.org/abs/2305.13245) (GQA).  
	**键值缓存** ：了解键值缓存以及 [多查询注意力机制](https://arxiv.org/abs/1911.02150) (MQA) 和 [分组查询注意力机制](https://arxiv.org/abs/2305.13245) (GQA) 中引入的改进。
- **Speculative decoding**: Use a small model to produce drafts that are then reviewed by a larger model to speed up text generation. EAGLE-3 is a particularly popular solution.  
	**推测性解码** ：使用小型模型生成草稿，然后用大型模型进行审查，以加快文本生成速度。EAGLE-3 是一种特别流行的解决方案。

📚 **References**:  
📚 **参考文献** ：

- [GPU Inference](https://huggingface.co/docs/transformers/main/en/perf_infer_gpu_one) by Hugging Face: Explain how to optimize inference on GPUs.  
	通过 Hugging Face 进行 [GPU 推理](https://huggingface.co/docs/transformers/main/en/perf_infer_gpu_one) ：解释如何优化 GPU 上的推理。
- [LLM Inference](https://www.databricks.com/blog/llm-inference-performance-engineering-best-practices) by Databricks: Best practices for how to optimize LLM inference in production.  
	Databricks 的 [LLM 推理](https://www.databricks.com/blog/llm-inference-performance-engineering-best-practices) ：如何在生产环境中优化 LLM 推理的最佳实践。
- [Optimizing LLMs for Speed and Memory](https://huggingface.co/docs/transformers/main/en/llm_tutorial_optimization) by Hugging Face: Explain three main techniques to optimize speed and memory, namely quantization, Flash Attention, and architectural innovations.  
	通过 Hugging Face [优化 LLM 的速度和内存](https://huggingface.co/docs/transformers/main/en/llm_tutorial_optimization) ：解释优化速度和内存的三种主要技术，即量化、Flash Attention 和架构创新。
- [Assisted Generation](https://huggingface.co/blog/assisted-generation) by Hugging Face: HF's version of speculative decoding. It's an interesting blog post about how it works with code to implement it.  
	Hugging Face [辅助生成](https://huggingface.co/blog/assisted-generation) ：HF 版本的推测性解码。一篇有趣的博文介绍了它如何通过代码实现。
- [EAGLE-3 paper](https://arxiv.org/abs/2503.01840?utm_source=chatgpt.com): Introduces EAGLE-3 and reports speedups up to 6.5×.  
	[EAGLE-3 论文](https://arxiv.org/abs/2503.01840?utm_source=chatgpt.com) ：介绍了 EAGLE-3，并报告速度提升高达 6.5 倍。
- [Speculators](https://github.com/vllm-project/speculators): Library made by vLLM for building, evaluating, and storing speculative decoding algorithms (e.g., EAGLE-3) for LLM inference.  
	[Speculators](https://github.com/vllm-project/speculators) ：由 vLLM 创建的库，用于构建、评估和存储 LLM 推理的推测性解码算法（例如 EAGLE-3）。

---

### 7\. Deploying LLMs7. 部署 LLM

Deploying LLMs at scale is an engineering feat that can require multiple clusters of GPUs. In other scenarios, demos and local apps can be achieved with much lower complexity.  
大规模部署 LLM 是一项工程挑战，可能需要多个 GPU 集群。但在其他情况下，演示和本地应用程序的实现复杂度要低得多。

- **Local deployment**: Privacy is an important advantage that open-source LLMs have over private ones. Local LLM servers ([LM Studio](https://lmstudio.ai/), [Ollama](https://ollama.ai/), [oobabooga](https://github.com/oobabooga/text-generation-webui), [kobold.cpp](https://github.com/LostRuins/koboldcpp), etc.) capitalize on this advantage to power local apps.  
	**本地部署** ：隐私是开源 LLM 相对于私有 LLM 的一个重要优势。本地 LLM 服务器（ [LM Studio](https://lmstudio.ai/) 、 [Ollama](https://ollama.ai/) 、 [oobabooga](https://github.com/oobabooga/text-generation-webui) 、 [kobold.cpp](https://github.com/LostRuins/koboldcpp) 等）正是利用这一优势来支持本地应用程序。
- **Demo deployment**: Frameworks like [Gradio](https://www.gradio.app/) and [Streamlit](https://docs.streamlit.io/) are helpful to prototype applications and share demos. You can also easily host them online, for example, using [Hugging Face Spaces](https://huggingface.co/spaces).  
	**演示部署** ： [Gradio](https://www.gradio.app/) 和 [Streamlit](https://docs.streamlit.io/) 等框架有助于构建应用程序原型和分享演示。您还可以轻松地将它们托管到网上，例如使用 [Hugging Face Spaces](https://huggingface.co/spaces) 。
- **Server deployment**: Deploying LLMs at scale requires cloud (see also [SkyPilot](https://skypilot.readthedocs.io/en/latest/)) or on-prem infrastructure and often leverages optimized text generation frameworks like [TGI](https://github.com/huggingface/text-generation-inference), [vLLM](https://github.com/vllm-project/vllm/tree/main), etc.  
	**服务器部署** ：大规模部署 LLM 需要云（另请参阅 [SkyPilot](https://skypilot.readthedocs.io/en/latest/) ）或本地基础设施，并且通常利用优化的文本生成框架，如 [TGI](https://github.com/huggingface/text-generation-inference) 、 [vLLM](https://github.com/vllm-project/vllm/tree/main) 等。
- **Edge deployment**: In constrained environments, high-performance frameworks like [MLC LLM](https://github.com/mlc-ai/mlc-llm) and [mnn-llm](https://github.com/wangzhaode/mnn-llm/blob/master/README_en.md) can deploy LLM in web browsers, Android, and iOS.  
	**边缘部署** ：在资源受限的环境中， [MLC LLM](https://github.com/mlc-ai/mlc-llm) 和 [mnn-llm](https://github.com/wangzhaode/mnn-llm/blob/master/README_en.md) 等高性能框架可以将 LLM 部署到 Web 浏览器、Android 和 iOS 上。

📚 **References**:  
📚 **参考文献** ：

- [Streamlit - Build a basic LLM app](https://docs.streamlit.io/knowledge-base/tutorials/build-conversational-apps): Tutorial to make a basic ChatGPT-like app using Streamlit.  
	[Streamlit - 构建一个基本的 LLM 应用程序](https://docs.streamlit.io/knowledge-base/tutorials/build-conversational-apps) ：使用 Streamlit 制作类似 ChatGPT 的基本应用程序的教程。
- [HF LLM Inference Container](https://huggingface.co/blog/sagemaker-huggingface-llm): Deploy LLMs on Amazon SageMaker using Hugging Face's inference container.  
	[HF LLM 推理容器](https://huggingface.co/blog/sagemaker-huggingface-llm) ：使用 Hugging Face 的推理容器在 Amazon SageMaker 上部署 LLM。
- [Philschmid blog](https://www.philschmid.de/) by Philipp Schmid: Collection of high-quality articles about LLM deployment using Amazon SageMaker.  
	[Philschmid 博客，](https://www.philschmid.de/) 作者 Philipp Schmid：收集了有关使用 Amazon SageMaker 部署 LLM 的高质量文章。
- [Optimizing latence](https://hamel.dev/notes/llm/inference/03_inference.html) by Hamel Husain: Comparison of TGI, vLLM, CTranslate2, and mlc in terms of throughput and latency.  
	Hamel Husain [优化延迟](https://hamel.dev/notes/llm/inference/03_inference.html) ：TGI、vLLM、CTranslate2 和 mlc 在吞吐量和延迟方面的比较。

---

### 8\. Securing LLMs8. 确保 LLMs

In addition to traditional security problems associated with software, LLMs have unique weaknesses due to the way they are trained and prompted.  
除了与软件相关的传统安全问题外，LLM 还由于其训练和提示方式而存在独特的弱点。

- **Prompt hacking**: Different techniques related to prompt engineering, including prompt injection (additional instruction to hijack the model's answer), data/prompt leaking (retrieve its original data/prompt), and jailbreaking (craft prompts to bypass safety features).  
	**提示破解** ：与提示工程相关的不同技术，包括提示注入（附加指令以劫持模型的答案）、数据/提示泄露（检索其原始数据/提示）和越狱（构造提示以绕过安全功能）。
- **Backdoors**: Attack vectors can target the training data itself, by poisoning the training data (e.g., with false information) or creating backdoors (secret triggers to change the model's behavior during inference).  
	**后门** ：攻击向量可以针对训练数据本身，例如，通过污染训练数据（例如，用虚假信息）或创建后门（秘密触发器，用于在推理期间改变模型的行为）。
- **Defensive measures**: The best way to protect your LLM applications is to test them against these vulnerabilities (e.g., using red teaming and checks like [garak](https://github.com/leondz/garak/)) and observe them in production (with a framework like [langfuse](https://github.com/langfuse/langfuse)).  
	**防御措施** ：保护 LLM 应用程序的最佳方法是针对这些漏洞进行测试（例如，使用红队演练和 [garak](https://github.com/leondz/garak/) 等检查），并在生产环境中观察它们（使用 [langfuse](https://github.com/langfuse/langfuse) 等框架）。

📚 **References**:  
📚 **参考文献** ：

- [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/) by HEGO Wiki: List of the 10 most critical vulnerabilities seen in LLM applications.  
	HEGO Wiki 列出的 [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/) ：LLM 应用程序中最常见的 10 个关键漏洞列表。
- [Prompt Injection Primer](https://github.com/jthack/PIPE) by Joseph Thacker: Short guide dedicated to prompt injection for engineers.  
	Joseph Thacker 的 [《提示注入入门》](https://github.com/jthack/PIPE) ：面向工程师的提示注入简明指南。
- [LLM Security](https://llmsecurity.net/) by [@llm\_sec](https://twitter.com/llm_sec): Extensive list of resources related to LLM security.  
	[LLM 安全](https://llmsecurity.net/) （作者： [@llm\_sec](https://twitter.com/llm_sec) ）：与 LLM 安全相关的丰富资源列表。
- [Red teaming LLMs](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/red-teaming) by Microsoft: Guide on how to perform red teaming with LLMs.  
	微软 [红队 LLM](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/red-teaming) 指南：如何使用 LLM 执行红队演练。

---

## Acknowledgements致谢

This roadmap was inspired by the excellent [DevOps Roadmap](https://github.com/milanm/DevOps-Roadmap) from Milan Milanović and Romano Roth.  
该路线图的灵感来源于 Milan Milanović 和 Romano Roth 的优秀 [DevOps 路线图](https://github.com/milanm/DevOps-Roadmap) 。

Special thanks to:  
特别鸣谢：

- Thomas Thelen for motivating me to create a roadmap  
	感谢 Thomas Thelen 激励我制定路线图
- André Frade for his input and review of the first draft  
	感谢 André Frade 对初稿的意见和审阅
- Dino Dunn for providing resources about LLM security  
	感谢 Dino Dunn 提供有关 LLM 安全性的资源
- Magdalena Kuhn for improving the "human evaluation" part  
	Magdalena Kuhn 对“人工评估”部分的改进做出了贡献
- Odoverdose for suggesting 3Blue1Brown's video about Transformers  
	Odoverdose 推荐了 3Blue1Brown 关于变形金刚的视频
- Everyone who contributed to the educational references in this course:)  
	感谢所有为本课程提供教育参考资料的人:)

*Disclaimer: I am not affiliated with any sources listed here.  
免责声明：我与此处列出的任何来源均无关联。*

---

[![Star History Chart](https://camo.githubusercontent.com/a617c40678857173522d2f6eadfe102be8f72200949455e4739f779f213fb565/68747470733a2f2f6170692e737461722d686973746f72792e636f6d2f7376673f7265706f733d6d6c61626f6e6e652f6c6c6d2d636f7572736526747970653d44617465)](https://www.star-history.com/#mlabonne/llm-course&Date)