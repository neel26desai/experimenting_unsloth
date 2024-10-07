# experimenting_unsloth

#Overview
In this repository we are exploring the use of Unsloth to perform finetuning of a number of popular open weights LLMs.
We have finetune LLMs for the Following usecases:
1. Chat
2. Instruction Following
3. SQL Code generation
4. Text Summarization
5. Continous text generation

## Files and their Contents
1. Finetuning_llama3_1.ipynb: Finetuning Llama 3.1 for continous text generation text like writing an article, poem or novel, using TinyStories dataset

2. Finetuning_MistralNemo12b.ipynb: Finetuning MistralNemo 12b model, for converting Human queries to sql queries , using b-mc2/sql-create-context

3. Finetunning_Gemma2.ipynb: Finetuning Gemma 2-9b model, for text summarization using 10% of CNN Daily news summarization dataset.

4. UnslothChatUI.ipynb: Chat UI for accessing model llama 3 and other unsloth finetuend models

5. Finetuning_Phi3_5.ipynb: Finetuning Phi3.5 mini for continous text generation text like writing an article, poem or novel, using TinyStories dataset.

6. Finetuning_Llama3.ipynb: Finetuning Llama 3, for chat interaction, using philschmid/guanaco-sharegpt-style data

7. Finetuning_Mistral0_3.ipynb: Finetuning Mistral0.3 model, for converting Human queries to sql queries , using b-mc2/sql-create-context

8. Finetuning_Phi3.ipynb: Finetuning Phi3 for chat use case, using mahiatlinux/Reflection-Dataset-ShareGPT-v2 dataset

9. Finetunning_Qwen2.ipynb: Finetuning Qwen2-0.5b model, for text summarization using 10% of CNN Daily news summarization dataset.

10. Finetuning_Gemma2_2b.ipynb: Fine tuning Gemma 2:2b model, for following instructions using yahma/alpaca-cleaned datasets, which is a subset of alpaca dataset.

11. TinyLlama_Learn_New_Language.ipynb:  teaching tiny-llama model a new language "Hindi".

12. TinyLlama_Conversational_ChatTemplate.ipynb: Using tinyl llama to explore finetuning it for conversation, text classification, and using multiple datasets for a single finetunning operation.

13. TinyLLama_DPO_Finetuning.ipynb: Demonatrating DPO based finetunning using unsloth, on chat based data

14. ORPO_Finetuning.ipynb: Demonatrating ORPA based finetunning using unsloth, on intruction following data.

15. CheckpointLearning.ipynb: IDemonstrating the learning from checkpoint feature of Unsloth.

16. MentalHelathChatbot_Phi3.ipynb: Buildig a mental health chatbot, by finetuning Phi3-mini model, on heliosbrahma/mental_health_chatbot_dataset

17. Exporting_Unsloth_Model_to_Ollama.ipynb: Exporting a model finetuned using Unsloth to ollama, and using this model for inference via Ollama server.

## Video:

https://youtu.be/3Mg8YID5wCw



