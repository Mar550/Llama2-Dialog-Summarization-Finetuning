<h1> Support Insights </h1>
<h3> An LLM-based Quality Analysis tool for customer support interactions </h3>

This repository contains the codes files used to finetune the Llama2 7B model for dialog summarisation in the context of customer support, and effectively evaluate the results.

<h3> Roadmap </h3>
There are 3 main secctions on this project:

  1. Data Preprocessing: In this part, we pre-processed the TWEETSUM dataset which contains various dialogs between customers and agents from twitter. The pre-processing involves cleaning the dataset, reducing it content, and formatting it to the instruction format specific to the model we will be using. 
  2. Fine-tuning of the Llama2 Model : The second step involves training the Llama2 7b chat base model with instruction fine-tuning using the previously formatted dataset.
  3. Evaluation : The last step focuses on evaluating the training results, first by comparing the outputs of the two models, then by using benchmarks such as ROUGE  and BERTScore

<h3> Pre-requisites </h3>
- At least 22 GB of GPU memory
- A Hugging-face account with a Read/Write permission token
