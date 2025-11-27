# Llama-3-Text-to-SQL-Fine-tuning
This project implements Parameter-Efficient Fine-Tuning (PEFT) on Llama-3-8B using QLoRA.

- Dataset: sql-create-context (HuggingFace)

- Method: LoRA (Rank=16, 4-bit Quantization)

- Result: Achieved syntax-correct SQL generation on unseen schemas.

- Framework: Unsloth, PyTorch, TRL.
