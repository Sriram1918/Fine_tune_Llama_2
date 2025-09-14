🚀 Fine-Tuning LLaMA 2 with LoRA

This project demonstrates parameter-efficient fine-tuning of the LLaMA-2
 language model using LoRA (Low-Rank Adaptation).

Instead of training all billions of parameters, LoRA adds small trainable matrices into specific layers, drastically reducing compute, memory, and training cost.

📌 Features

Fine-tunes LLaMA-2 (7B/13B/70B) with LoRA + PEFT

Supports 4-bit quantization via bitsandbytes to fit on smaller GPUs

Works with custom instruction-response datasets

Saves and reloads fine-tuned weights easily

Hugging Face transformers + peft + datasets integration

⚙️ Setup
1. Install Dependencies
pip install transformers datasets accelerate peft bitsandbytes trl

2. Log in to Hugging Face
huggingface-cli login


(needed to download LLaMA-2 weights and push fine-tuned models)
