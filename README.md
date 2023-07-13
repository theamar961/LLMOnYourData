# LLMOnYourData
Just wanted to see how I could connect my own database to a pre-trained LLM (gpt-3.5)


### Things you would need

1. OpenAI API Key - we will use gpt-3.5 as our base LLM to generate our output
2. Pinecone database API Key - we will use Pinecone to store our vector embeddings which can be easily used by our LLM model

### Use-cases

1. Domain-specific output - connect an LLM to your domain-specific database and train it to perform intended tasks.
2. Treat LLM Hallucinations - LLMs are trained only up to a certain point of time(gpt-3.5 is trained till late 2021), you can input updated corpus to an LLM and train it to generate up-to-date information.
3. Custom data - Let us say you want to train your LLM based on custom data/custom chat-data.

### Conclusion

Retrieval Augmentation is relevant, powerful and necessary in order to use most LLMs on your data.
