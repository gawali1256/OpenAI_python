Live Interactive Chatbot with GPT-3.5 and Google SERP Integration using LangChain
GitHub License

A powerful and innovative project that combines the capabilities of OpenAI's GPT-3.5 language model, Google SERP API, and LangChain framework to create an interactive chatbot that provides real-time, context-aware responses using live search results.

Overview
This project showcases the fusion of cutting-edge technologies to develop an intelligent chatbot that goes beyond traditional conversational AI. By integrating GPT-3.5, Google SERP (Search Engine Results Page) data, and the LangChain framework, we have created an interactive assistant that not only generates human-like responses but also leverages the most current information available on the web.

Features
Real-time Search Integration: Unlike traditional chatbots that rely solely on pre-trained data, our chatbot fetches live data from Google SERP using the SERP.ai API. This ensures that the responses provided by the chatbot are based on the latest and most relevant information available.

Context-Aware Responses: By combining LangChain's scalable AI/LLM capabilities and GPT-3.5's natural language understanding, our chatbot understands and maintains context throughout the conversation. This enables it to generate coherent and meaningful responses that take into account the user's queries and previous interactions.

Flexible Integration: The project provides a comprehensive TypeScript implementation using Next.js, making it easy to adapt and integrate into various applications and platforms.

Getting Started
Follow these steps to set up the project on your local machine:


Configure API Keys: Create a .env file based on .env.example and fill in your OpenAI and SERP.ai API keys.
Customize Chatbot Settings: In the utils/makechain.ts file, adjust the LangChain settings and GPT-3.5 API parameters according to your requirements.
Ingest Data: Place your PDF files containing text in the docs folder and run npm run ingest to convert them into embeddings.
Launch the Chatbot: Run npm run dev to start the local development environment. Interact with the chat interface and observe how the chatbot generates responses based on real-time search results.
Troubleshooting
Encountering issues? Here are a few common troubleshooting steps:

Ensure you're using Node.js version 18 or greater.
Double-check that your API keys and environment settings in the .env file are accurate.
Verify that your LangChain and Pinecone versions match those specified in this repository.
Review the GitHub repository's Issues and Discussions sections for possible solutions to common problems.
Contributing
We welcome contributions from the community! If you have ideas for improvements or bug fixes, feel free to submit a pull request. Please ensure you follow our Code of Conduct.

License
This project is licensed under the MIT License.

Disclaimer: This project is a demonstration of advanced AI integration and is not intended for production use without proper modification and testing.
