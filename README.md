# Chatbots are partisan: detecting implicit political lean in natural outputs of large language models
by Rachael Boyle and Haley Triem

Contains code and data for research on the implicit political bias from natural interactions with LLMs. We used natural language processing and machine learning to classify the political lean of LLM outputs when prompted with different news topics (2017-2022) and prompting styles across. LLMs: LLAMA2 13B, LLAMA2 70B, GPT3, and GPT4.

* `llm_api_prompting.ipynb` - Contains code we used to gather LLM responses to our 202 prompts (combination of 77 news topic and 2-4 prompting styles) 
* `llm_response_type_analysis.ipynb` - Contains code we used to analyze our qualitatively human labeled response type from the LLM (i.e. refusing to respond, redirecting the POV / bias presented in the prompt)
* `llm_bias_classifier.ipynb` - Contains code we used to create our political bias classifer, trained on news data with articles across the political spectrum and run on our LLM response dataset
* `mapped_llm_response_data.ipynb` - Our LLM response dataset, with our (human) response type labels and (classifier) political bias labels
