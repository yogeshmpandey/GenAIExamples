# FAQ Generation Application

In a world where data, information, and legal complexities are prevalent, the volume of legal documents is growing rapidly. Law firms, legal professionals, and businesses are dealing with an ever-increasing number of legal texts, including contracts, court rulings, statutes, and regulations. These documents contain important insights, but understanding them can be overwhelming. This is where the demand for legal FAQ Generation comes in.

Large Language Models (LLMs) have revolutionized the way we interact with text. These models can be used to create summaries of news articles, research papers, technical documents, and other types of text. Suppose you have a set of documents (PDFs, Notion pages, customer questions, etc.) and you want to summarize the content. In this example use case, we utilize LangChain to implement FAQ Generation strategies and facilitate LLM inference using Text Generation Inference on Intel Xeon and Gaudi2 processors.

The architecture for FAQ Generation will be illustrated/described below:

![Architecture](./assets/img/faqgen_architecture.png)

![Workflow](./assets/img/faqgen_workflow.png)

# Deploy FAQ Generation Service

The FAQ Generation service can be effortlessly deployed on either Intel Gaudi2 or Intel XEON Scalable Processors.

## Deploy FAQ Generation on Gaudi

Refer to the [Gaudi Guide](./docker/gaudi/README.md) for instructions on deploying FAQ Generation on Gaudi.

## Deploy FAQ Generation on Xeon

Refer to the [Xeon Guide](./docker/xeon/README.md) for instructions on deploying FAQ Generation on Xeon.
