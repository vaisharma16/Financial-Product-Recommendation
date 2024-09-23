# A recommendation engine for financial products using Python, large language models (LLMs), and a text-to-text transfer transformer (T5) model. 

The recommendation engine personalizes user experiences by analyzing demographic, personal, and bureau data to recommend suitable banking products.

Important Points:

- Recommendation engines use collaborative filtering (comparing user behavior) and content-based filtering (recommending similar products) to generate personalized recommendations.
- The project employs the Zayler 7B LLM from Meta's Fine-tuned Large Language Model (FLLM) to enhance recommendation algorithms.
- The project demonstrates how to generate synthetic data using Faker library, preprocess data, and store it in a Vector database using Hugging Face embedding models.
- The Rag-based QA pipeline generates responses in text format, providing recommendations based on input customer data.
- The recommendation engine analyzes customer attributes (e.g., income level, debt-to-income ratio) to suggest suitable financial products.
