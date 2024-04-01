# Fine-Tune & Evaluate LLMs in 2024 with Amazon SageMaker

Large Language Models or LLMs have seen a lot of progress in the last year. We went from no ChatGPT competitor to a whole zoo of LLMs, including Meta AI's Llama 2, Mistrals Mistral & Mixtral models, 
TII Falcon, and many more. Those LLMs can be used for a variety of tasks, including chatbots, question answering, summarization without any additional training. However, if you want to customize a model for 
your application. You may need to fine-tune the model on your data to achieve higher quality results than prompting or saving cost by training smaller models more efficient model.

This blog post walks you thorugh how to fine-tune open LLMs from Hugging Face using Amazon SageMaker. This blog is an extension and dedicated version to my How to Fine-Tune LLMs in 2024 with Hugging Face version, 
specifically tailored to run on Amazon SageMaker.

1. [Setup development environment](https://www.philschmid.de/sagemaker-train-evalaute-llms-2024#1-setup-development-environment)
2. [Create and prepare the dataset](https://www.philschmid.de/sagemaker-train-evalaute-llms-2024#2-create-and-prepare-the-dataset)
3. [Fine-tune LLM using trl on Amazon SageMaker](https://www.philschmid.de/sagemaker-train-evalaute-llms-2024#3-fine-tune-mistral-7b-with-qlora-on-amazon-sagemaker)
4. [Deploy & Evaluate LLM on Amazon SageMaker](https://www.philschmid.de/sagemaker-train-evalaute-llms-2024#4-deploy--evaluate-llm-on-amazon-sagemaker)
