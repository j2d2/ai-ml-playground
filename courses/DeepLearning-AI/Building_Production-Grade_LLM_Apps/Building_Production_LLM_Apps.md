# _DeepLearning.AI Webcast:_ Building Production-Grade LLM Apps

## Speakers:
- Diana @dianaquianmorgan
- Amnon Catav - Sr Machine Learning Engineer, Pinecone (Vector DB)
  https://www.linkedin.com/in/amnon-catav-6a7068142/
- Anupam Datta - Co-founder & Chief Scientist, TruEra
  https://www.linkedin.com/in/anupamdatta/
- Joshua Reini

## Webinar Topics
- RAGs with Canopy/Pinecone  
- Evalualing and iterating with TruLens/TruEra  

Recording of webinar: https://www.youtube.com/watch?v=fo0F-DAum7E  

> __RAG:__ Retrieval-augmented generation is a technique for enhancing the accuracy and reliability of generative AI models with facts fetched from external sources.

## Canopy (E2E RAG)

https://github.com/pinecone-io/canopy

Canopy is free for commercial products

## TruLens

https://github.com/truera/trulens
https://colab.research.google.com/github/truera/trulens/

https://Trulens.org/trulens_eval/

Trulens - track experiments to select the best app configuration
  Constructing the Vector DB, Retrieval, LLM

Fixing LLM inconsistency
  Guard against hallucinations, inappropriate responses
  Keep temperature close to zero

## The RAG Triad  
Query -> Context -> (Groundedness) Response -> (back to Query)


# References

https://community.deeplearning.ai/top?period=weekly

https://www.deeplearning.ai/courses/

https://www.deeplearning.ai/short-courses/open-source-models-hugging-face

https://www.deeplearning.ai/short-courses/building-applications-vector-databases

https://www.deeplearning.ai/short-courses/building-evaluating-advanced-rag

---

# Details of webinar

1,748 watching...

__Description:__
Last year, GenAI experimentation spread like wildfire. Developers tinkered with new foundation models, data, and use cases. However, a relatively low percentage of projects moved from prototypes to production to drive real-world impact. One significant reason for this is ensuring app trustworthiness: Is an app reliable, accurate, or fair enough to be unleashed on the world? Which app responses are hallucinatory, which ones are unsafe? Could we identify issues and mitigate them during app development and in production to meet the quality level that end users need?

This year, organizations are taking their learnings from experimentation and focusing on creating and iterating enterprise-grade apps that will be reliable in the harsher realities of production environments.

How can you make your apps enterprise grade? In this webinar, technical leaders from Pinecone and TruEra will share how to create apps that are high quality and production ready. The principles will be illustrated with Pinecone Canopy and TruLens, and notebooks will be available for participants to explore.

In this workshop, you will learn: 

- What do you need to create enterprise-ready AI models and apps? Your current stack might have some gaps in it. Here’s what’s working.
- What do you need to evaluate and iterate on apps quickly, so that you can gain confidence that your app is ready for production?
- Rapid response - what happens when an app generates a hallucinatory or irrelevant or unsafe response? How to monitor, recognize when your app is in trouble and quickly get it back on the rails.

Below are the materials for the webinar later today.

Notebook:
https://github.com/truera/trulens/blob/main/trulens_eval/examples/expositional/frameworks/canopy/canopy_quickstart.ipynb

About DeepLearning.AI

DeepLearning.AI is an education technology company that is empowering the global workforce to build an AI-powered future through world-class education, hands-on training, and a collaborative community. Take your generative AI skills to the next level with short courses help you learn new skills, tools, and concepts efficiently.

About Pinecone:

Pinecone created the vector database, which acts as the long-term memory for AI models and is a core infrastructure component for AI-powered applications. The managed service lets engineers build fast and scalable applications that use embeddings from AI models, and get them into production sooner. Pinecone recently raised $100M in Series B funding at a $750M valuation. The funding round was led by Andreessen Horowitz, with participation from ICONIQ Growth and previous investors Menlo Ventures and Wing Venture Capital. Pinecone operates in San Francisco, New York, and Tel Aviv.


About TruEra:

TruEra is the leader in AI Observability, helping companies to monitor, debug, and test their AI apps in order to drive performance, quality, and trustworthiness. Powered by enterprise-class Artificial Intelligence (AI) Explainability technology based on over nine years of research, TruEra is able to facilitate faster, more accurate ML model monitoring, analysis and debugging than any other vendor. Organizations using TruEra can achieve higher quality, higher performing models that sustainably achieve measurable business results, address unfair bias, and ensure governance and compliance.
