# 📦 Large Language Models (LLM)

A Large Language Model (LLM) is a type of artificial intelligence algorithm designed to process and understand natural language. It is a machine learning model that has been trained on massive amounts of text data, such as books, articles, and web pages. The goal of an LLM is to generate human-like responses to given prompts, which can include anything from simple questions to complex conversations.

LLMs are typically based on neural networks, which are a type of machine learning algorithm inspired by the structure and function of the human brain. Specifically, LLMs are often based on a type of neural network called a transformer, which is particularly effective at processing and generating natural language. They are particularly useful in situations where large amounts of text data need to be processed and understood quickly and accurately.

While LLMs have initially gained popularity in the NLP field, their potential applications are much broader and can be used in any field that involves natural language processing or generation. For example, LLMs can be used in computer vision tasks such as image captioning, where they can generate descriptive text for images. They can also be used in recommendation systems to generate personalized product descriptions, or in autonomous vehicles to enable more natural language communication between passengers and the vehicle.

## Natural Language Processing (NLP)

This is a field of AI that deals with the interaction between computers and humans in natural language. NLP models analyze and understand human language to derive meaning and context, enabling machines to communicate more effectively with humans.

There are many kinds of applications that use NLP:

- **Text Classification**: assigning categories or labels to text data. For instance, classifying a movie review as positive or negative

- **Sentiment Analysis**: analyzing text data to determine the sentiment behind it. This can be useful for analyzing social media posts to determine whether they are positive, negative, or neutral

- **Named Entity Recognition (NER)**: identifying and categorizing named entities in text data. Named entities can include people, places, organizations, and other entities

- **Machine Translation**: translating text from one language to another using machine learning algorithms

- **Question Answering Systems**: these systems use NLP techniques to understand natural language questions and provide answers. For instance, chatbots that help customers with their queries

- **Text Summarization**: automatically summarizing long text documents, such as news articles or research papers, to extract the most important information

- **Speech Recognition**: converting spoken language into text. Speech recognition systems use NLP techniques to recognize patterns in speech and convert them into text

<br>

## Notorious LLMs

Ordered from most recent to older:

<table class="table table-bordered table-hover table-condensed">
  <thead>
    <tr>
      <th title="Field 1">LLM Name</th>
      <th title="Field 2">Release Date</th>
      <th title="Field 3">Developer</th>
      <th title="Field 4">Number of Parameters</th>
      <th title="Field 5">Corpus Size</th>
      <th title="Field 6">License</th>
      <th title="Field 7">Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>GPT-4</td>
      <td>March 2023</td>
      <td>OpenAI</td>
      <td>Unknown</td>
      <td>Unknown</td>
      <td>public web API</td>
      <td>Available for ChatGPT Plus users and used in several products.</td>
    </tr>
    <tr>
      <td>BloombergGPT</td>
      <td>March 2023</td>
      <td>Bloomberg L.P.</td>
      <td>50 billion</td>
      <td>363 billion token dataset based on Bloomberg&#39;s data sources, plus 345 billion tokens from general purpose datasets</td>
      <td>Proprietary</td>
      <td>LLM trained on financial data from proprietary sources, that &quot;outperforms existing models on financial tasks by significant margins without sacrificing performance on general LLM benchmarks&quot;</td>
    </tr>
    <tr>
      <td>LLaMA (Large Language Model Meta AI)</td>
      <td>February 2023</td>
      <td>Meta</td>
      <td>65 billion</td>
      <td>1.4 trillion</td>
      <td>Non-commercial research</td>
      <td>Trained on a large 20-language corpus to aim for better performance with fewer parameters. Researchers from Stanford University trained a fine-tuned model based on LLaMA weights, called Alpaca.</td>
    </tr>
    <tr>
      <td>BLOOM</td>
      <td>July 2022</td>
      <td>Large collaboration led by Hugging Face</td>
      <td>175 billion</td>
      <td>350 billion tokens (1.6TB)</td>
      <td>Responsible AI</td>
      <td>Essentially GPT-3 but trained on a multi-lingual corpus (30% English excluding programming languages)</td>
    </tr>
    <tr>
      <td>OPT (Open Pretrained Transformer)</td>
      <td>May 2022</td>
      <td>Meta</td>
      <td>175 billion</td>
      <td>180 billion tokens</td>
      <td>Non-commercial research</td>
      <td>GPT-3 architecture with some adaptations from Megatron</td>
    </tr>
    <tr>
      <td>PaLM (Pathways Language Model)</td>
      <td>April 2022</td>
      <td>Google</td>
      <td>540 billion</td>
      <td>768 billion tokens</td>
      <td>Proprietary</td>
      <td>aimed to reach the practical limits of model scale</td>
    </tr>
    <tr>
      <td>LaMDA (Language Models for Dialog Applications)</td>
      <td>January 2022</td>
      <td>Google</td>
      <td>137 billion</td>
      <td>1.56T words, 168 billion tokens</td>
      <td>Proprietary</td>
      <td>Specialized for response generation in conversations. Used in Google Bard chatbot.</td>
    </tr>
    <tr>
      <td>GPT-3</td>
      <td>2020</td>
      <td>OpenAI</td>
      <td>175 billion</td>
      <td>499 billion tokens</td>
      <td>public web API</td>
      <td>A fine-tuned variant of GPT-3, termed GPT-3.5, was made available to the public through a web interface called ChatGPT in 2022</td>
    </tr>
  </tbody>
</table>

<a href="https://en.wikipedia.org/wiki/Large_language_model#List_of_large_language_models" target="_blank">Source</a>

<br>

## Other LLMs

<table class="table table-bordered table-hover table-condensed">
  <thead>
    <tr>
      <th title="Field 1">LLM Name</th>
      <th title="Field 2">Release Date</th>
      <th title="Field 3">Developer</th>
      <th title="Field 4">Number of Parameters</th>
      <th title="Field 5">Corpus Size</th>
      <th title="Field 6">License</th>
      <th title="Field 7">Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>PanGu-Σ</td>
      <td>March 2023</td>
      <td>Huawei</td>
      <td>1.085 trillion</td>
      <td>329 billion tokens</td>
      <td>Proprietary</td>
      <td> </td>
    </tr>
    <tr>
      <td>Cerebras-GPT</td>
      <td>March 2023</td>
      <td>Cerebras</td>
      <td>13 billion</td>
      <td> </td>
      <td>Apache 2.0</td>
      <td>Trained with Chinchilla formula.</td>
    </tr>
    <tr>
      <td>Falcon</td>
      <td>March 2023</td>
      <td>Technology Innovation Institute</td>
      <td>40 billion</td>
      <td>1 Trillion tokens (1TB)</td>
      <td>Proprietary</td>
      <td>The model is claimed to use only 75% of GPT-3&#39;s training compute, 40% of Chinchilla&#39;s, and 80% of PaLM-62B&#39;s.</td>
    </tr>
    <tr>
      <td>AlexaTM (Teacher Models)</td>
      <td>November 2022</td>
      <td>Amazon</td>
      <td>20 billion</td>
      <td>1.3 trillion</td>
      <td>public web API</td>
      <td>bidirectional sequence-to-sequence architecture</td>
    </tr>
    <tr>
      <td>Galactica</td>
      <td>November 2022</td>
      <td>Meta</td>
      <td>120 billion</td>
      <td>106 billion tokens</td>
      <td>CC-BY-NC-4.0</td>
      <td>Trained on scientific text and modalities.</td>
    </tr>
    <tr>
      <td>Minerva</td>
      <td>June 2022</td>
      <td>Google</td>
      <td>540 billion</td>
      <td>38.5B tokens from webpages filtered for mathematical content and from papers submitted to the arXiv preprint server</td>
      <td>Proprietary</td>
      <td>LLM trained for solving &quot;mathematical and scientific questions using step-by-step reasoning&quot;. Minerva is based on PaLM model, further trained on mathematical and scientific data.</td>
    </tr>
    <tr>
      <td>YaLM 100B</td>
      <td>June 2022</td>
      <td>Yandex</td>
      <td>100 billion</td>
      <td>1.7TB</td>
      <td>Apache 2.0</td>
      <td>English-Russian model based on Microsoft&#39;s Megatron-LM.</td>
    </tr>
    <tr>
      <td>Chinchilla</td>
      <td>March 2022</td>
      <td>DeepMind</td>
      <td>70 billion</td>
      <td>1.4 trillion tokens</td>
      <td>Proprietary</td>
      <td>Reduced-parameter model trained on more data. Used in the Sparrow bot.</td>
    </tr>
    <tr>
      <td>GPT-NeoX</td>
      <td>February 2022</td>
      <td>EleutherAI</td>
      <td>20 billion</td>
      <td>825 GiB</td>
      <td>Apache 2.0</td>
      <td>based on the Megatron architecture</td>
    </tr>
    <tr>
      <td>BERT</td>
      <td>2018</td>
      <td>Google</td>
      <td>340 million</td>
      <td>3.3 billion words</td>
      <td>Apache 2.0</td>
      <td>An early and influential language model, but encoder-only and thus not built to be prompted or generative</td>
    </tr>
  </tbody>
</table>

<a href="https://en.wikipedia.org/wiki/Large_language_model#List_of_large_language_models" target="_blank">Source</a>
