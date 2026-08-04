LLMs are such a step change in how machine learning models interact with natural language that they have sparked a revolution in artificial intelligence applications. Millions of people now use LLMs every day to accomplish tasks like building a travel itinerary, writing an email to a colleague, and preparing a cover letter for a job application.

Because they are so adept at certain functions of natural language processing (NLP), we hypothesized that they may be effective at others. Text classification, used widely for spam detection, sentiment analysis, and other purposes, is one of the most fundamental applications of NLP. LLMs were not built for text classification, but their strength in NLP may enable them to perform the task at a high level. If so, they could spawn a new set of applications for this technology. Our experiments set out to put LLMs to the test.

Supervised Learning for Text Classification With LLMs: A Review
In the first post in this series, we looked at our experiments with supervised learning. Specifically, we discussed how three distinct supervised learning approaches worked for text classification:

fine-tuning an existing model derived from BERT (a framework with a strong history in NLP)
fine-tuning an existing model using Low-Rank Adaptation (LoRA)
applying transfer learning to a classification head, which leveraged a trained model from another use case

