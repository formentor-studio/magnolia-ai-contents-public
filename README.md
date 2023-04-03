# Magnolia AI Contents

This project implements a set of features in [Magnolia CMS](https://www.magnolia-cms.com/) to create contents using AI and to train [Large language models](https://en.wikipedia.org/wiki/Large_language_model) using contents in [Magnolia](https://www.magnolia-cms.com/)

## Features
- Integration with the API of [OpenAI](https://platform.openai.com/docs/api-reference) and [Azure OpenAI](https://azure.microsoft.com/products/cognitive-services/openai-service/)
- UI field `textFieldAI` to create and edit text contents using AI.
- UI field `imageAI` to create images using AI.
- Creation of fine-tuned models in [Open AI GPT](https://openai.com/blog/gpt-3-apps) and [Azure OpenAI](https://azure.microsoft.com/products/cognitive-services/openai-service/)

## Modules
### ai-contents
Provides the following UI fields to create contents using AI:
- `textFieldAI` to create text using AI.
- `imageAI` to create images using AI.
### ai-training
generation of [Large language models](https://en.wikipedia.org/wiki/Large_language_model) like [GPT](https://en.wikipedia.org/wiki/GPT-3) using as input dataset contents in [Magnolia CMS](https://www.magnolia-cms.com/).

### demo-ai-contents-app
Content app of Magnolia with examples using the fields `textFieldAI` and `imageAI`

### magnolia-ai-bundle-webapp
Example of a bundle of Magnolia using the modules `ai-contents` and `ai_training`