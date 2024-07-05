# LLM-Finetuning

# PEFT Fine-Tuning Project 🚀

Welcome to the PEFT (Pretraining-Evaluation Fine-Tuning) project repository! This project focuses on efficiently fine-tuning large language models using LoRA and Hugging Face's transformers library.

![](https://huggingface.co/datasets/trl-internal-testing/example-images/resolve/main/images/trl_overview.png)

## Fine Tuning Notebook Table 📑

| Notebook Title                                               | Description                                                  | Colab Badge                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **1. Efficiently Train Large Language Models with LoRA and Hugging Face** | Details and code for efficient training of large language models using LoRA and Hugging Face. | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/1.Efficiently_train_Large_Language_Models_with_LoRA_and_Hugging_Face.ipynb) |
| **2. Fine-Tune Your Own Llama 2 Model in a Colab Notebook**  | Guide to fine-tuning your Llama 2 model using Colab.         | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/2.Fine_Tune_Your_Own_Llama_2_Model_in_a_Colab_Notebook.ipynb) |
| **3. Guanaco Chatbot Demo with LLaMA-7B Model**              | Showcase of a chatbot demo powered by LLaMA-7B model.        | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/3.Guanaco%20Chatbot%20Demo%20with%20LLaMA-7B%20Model.ipynb) |
| **4. PEFT Finetune-Bloom-560m-tagger**                       | Project details for PEFT Finetune-Bloom-560m-tagger.         | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/4.PEFT%20Finetune-Bloom-560m-tagger.ipynb#scrollTo=MDqJWba-tpnv) |
| **5. Finetune_Meta_OPT-6-1b_Model_bnb_peft**                 | Details and guide for finetuning the Meta OPT-6-1b Model using PEFT and Bloom-560m-tagger. | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/5.Finetune_Meta_OPT-6-1b_Model_bnb_peft.ipynb) |
| **6.Finetune Falcon-7b with BNB Self Supervised Training**   | Guide for finetuning Falcon-7b using BNB self-supervised training. | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/6.Finetune%20Falcon-7b%20with%20BNB%20Self%20Supervised%20Training.ipynb) |
| **7.FineTune LLaMa2 with QLoRa**                             | Guide to fine-tune the Llama 2 7B pre-trained model using the PEFT library and QLoRa method | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/7.FineTune_LLAMA2_with_QLORA.ipynb) |
| **8.Stable_Vicuna13B_8bit_in_Colab**                         | Guide of Fine Tuning Vecuna 13B_8bit                         | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/8.Stable_Vicuna13B_8bit_in_Colab.ipynb) |
| **9. GPT-Neo-X-20B-bnb2bit_training**                        | Guide How to train the GPT-NeoX-20B model using bfloat16 precision | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/9.GPT-neo-x-20B-bnb_4bit_training.ipynb) |
| **10. MPT-Instruct-30B Model Training**                      | MPT-Instruct-30B is a large language model from MosaicML that is trained on a dataset of short-form instructions. It can be used to follow instructions, answer questions, and generate text. | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/10.MPT_Instruct_30B.ipynb) |
| **11.RLHF_Training_for_CustomDataset_for_AnyModel**          | How train a Model with RLHF training on any LLM model with custom dataset | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/11_RLHF_Training_for_CustomDataset_for_AnyModel.ipynb) |
| **12.Fine_tuning_Microsoft_Phi_1_5b_on_custom_dataset(dialogstudio)** | How train a model with trl SFT Training on Microsoft Phi 1.5 with custom | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/12_Fine_tuning_Microsoft_Phi_1_5b_on_custom_dataset(dialogstudio).ipynb) |
| **13. Finetuning OpenAI GPT3.5 Turbo**                       | How to finetune GPT 3.5 on your own data                     | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/13.Fine_tuning_OpenAI_GPT_3_5_turbo.ipynb) |
| **14. Finetuning Mistral-7b FineTuning Model using Autotrain-advanced** | How to finetune Mistral-7b using autotrained-advanced        | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/14.Finetuning_Mistral_7b_Using_AutoTrain.ipynb) |
| **15. RAG LangChain Tutorial**                               | How to Use RAG using LangChain                               | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/15.RAG_LangChain.ipynb) |
| **16. Knowledge Graph LLM with LangChain PDF Question Answering** | How to build knowledge graph with pdf question answering     | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/16.Neo4j_and_LangChain_for_Enhanced_Question_Answering.ipynb) |
| **17. Text to Knolwedge Graph with OpenAI Function with Neo4j and Langchain Agent Question Answering** | How to build knowledge graph from text or Pdf Document with pdf question Answering | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/17.OpenAI_Constructing_Graph_for_Questio_Answer.ipynb) |
| **18. Convert the Document to Knowledgegraph using Langchain and Openai** | This notebook is help you to understand how easiest way you can convert your any documents into Knowledgegraph for your next RAG based Application | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/18.Convert_Document_to_Knowledge_Graph_Langchain_Openai.ipynb) |
| **19. How to train a 1-bit Model with LLMs?**                | This notebook is help you to train a model with 1-bit and 2-bit quantization method using hqq framework | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/19.HQQ_1bit_ipynb.ipynb) |
| **20.Alpaca_+_Gemma2_9b_Unsloth_2x_faster_finetuning**                | This notebook is help you to train a model with gemma2 9b | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashishpatel26/LLM-Finetuning/blob/main/20.Alpaca_%2B_Gemma2_9b_Unsloth_2x_faster_finetuning.ipynb) |
## Contributing 🤝

Contributions are welcome! If you'd like to contribute to this project, feel free to open an issue or submit a pull request.

## License 📝

This project is licensed under the [MIT License](LICENSE).

---

Created with ❤️ by [Ashish](https://github.com/ashishpatel26/)
