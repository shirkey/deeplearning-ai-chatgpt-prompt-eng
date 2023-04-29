# ChatGPT Prompt Engineering for Developers - Azure OpenAI Services Edition

This repository is based on the source code shared in the [DeepLearningAI](https://www.deeplearning.ai) fantastic and free short course of [ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/).

Changes have been made to the original source code to accommodate the use of [Azure OpenAI (AOAI) Services](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/) Services as an alternative to OpenAI's own endpoints.

## Setup

- Sign-up for the [course](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)
- Create your Azure OpenAI Services Resource and Model Deployment -- refer to docs [here](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/how-to/create-resource?pivots=web-portal)
    - Choose from `eastus`, `southcentralus` or `westeu` as the region where AOAI services are currently available (as of 29/04/2023)
    - Deploy the `gpt-35-turbo` model, naming it either `gpt-35-turbo` or another name (updating .env to reflect the same)
- Copy `.env.sample` to `.env` with the specific configuration matching your Azure Deployment, including Endpoint URLs and Keys
- Install the required Python modules:
    - `pip install -r requirements.txt`
- Run the notebooks:
    - `jupyter notebook` then select the specific tutorial notebook (eg 1l -> 8l)
- Watch the course videos and follow along with each related notebook
