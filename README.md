# diy_llm
DIY LLM benchmarking

## Overview

How does DIY Sagemaker LLM scale with load?

I had a really hard time answering this question for a client so I want to do experiments on autoscaling with an opensource LLM in Sagemaker.

## Data

The assumed data structure is that data is in 
```
data/enron/maildir
```

This has been excluded from git but can be downloaded from 

`https://www.cs.cmu.edu/~enron/enron_mail_20150507.tar.gz`

## Resources

Data

https://www.cs.cmu.edu/~enron/

Autoscaling article:

https://medium.com/@sepehr.keykhaie/serving-large-language-models-llms-at-scale-on-aws-b53136667db7



Suggested light LLMs:

- Huggingface distilbert-base-uncased
- TinyBERT tinybert
- ALBERT albert
- MiniLM minilm

Sagemaker deploy of Llama 3.1 70B:

https://www.philschmid.de/sagemaker-llama-llm

In case you want to add in RAG:

https://www.pinecone.io/learn/sagemaker-rag/

