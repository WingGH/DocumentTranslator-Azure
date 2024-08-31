# DocumentTranslator-Azure
A Python tool that translates Word documents using Azure's Document Translation API and compares translations with the original text using OpenAI's GPT-4 model. Ideal for ensuring translation accuracy and consistency.
This project demonstrates how to translate a Word document using Azure's Document Translation API and compare the translated text with the original using OpenAI's GPT-4 model.

## Prerequisites

- Python 3.x
- Azure Cognitive Services account with Translator resource
- Azure OpenAI Service API access

## Configuration
Update the Azure Cognitive Services endpoint and API key, OpenAI endpoint and API key:

   ```bash
  endpoint = "https://your-cognitive-service-endpoint.cognitiveservices.azure.com/"
  headers = {
      "Ocp-Apim-Subscription-Key": "your_subscription_key"
  }

  API_KEY = "your_api_key"
  ENDPOINT = "https://your-endpoint-url/openai/deployments/gpt-4o/chat/completions?api-version=2024-02-15-preview"
