# Fine-Tuning-LLM-using-LoRA
In this notebook,I am fine tuning Phi2 pretrained LLM on a custom dialogue dataset for summarization.
Here I am using LoRA technique to achieve fine tuning which reduces the number of trainable parameters to a single digit %age of actual weights of the model
In this file, I did fine tuning for 200 steps due to resource and time constraint, it showed some improvement over Zero shot inference without any fine tuning but if we increase number of training steps, then it will show much more improvement.
Further things to be done -
* Train this using QLoRA configuration
* Use other large models comparative to Phi2 like Mistral,LLAMA-2,GPT-4
