## ChatADS

[ChatADS](https://chat.openai.com/g/g-BLIbeS205-chatads) is a GPT that allows users to search NASA ADS and ask questions about paper content using natural language.

It uses the NASA ADS API along with an API for arXiv paper Q&A developed by Tom Tumiel.

If you have ChatGPT Plus you can talk to ChatADS and receive summaries of the papers, figures in those papers, tables that synthesize the results from multiple papers, and to ask questions like: “What is Jo Bovy’s group up to nowadays?” All in natural language.

Access ChatADS here: [ChatADS GPT](https://chat.openai.com/g/g-BLIbeS205-chatads)

Here's a video demo of its use: [ChatADS Demo](https://youtu.be/CL2SSpZT_RU)

### Prompt
See prompt.txt for all the context provided to the GPT. In summary, it provides instructions on how to consistently call the ADS API and then the arXiv Q&A API until an answer is found, how to respond to users, and then information on every search term in the ADS API along with some examples. The maximum prompt size set by OpenAI is 8000 characters. Originally I started with a small prompt of just the ADS keys and examples and then I added new sentences as I tested the GPT.

### ADS API
Added the Actions section of the GPT creator.
See ads_api.yaml for the API specification used.
[Requires API token](https://ui.adsabs.harvard.edu/user/settings/token).

### arXiv Q&A API (Xplorer)
Xplorer is developed by Tom Tumiel and is a semantic search and Q&A system for arXiv papers. 
See [Xplorer Website & API](https://arxivxplorer.com/).
Or try out the [Xplorer GPT](https://chat.openai.com/g/g-WeT9tE7SR-xplorer)
