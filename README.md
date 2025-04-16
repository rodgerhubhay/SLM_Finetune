"https://huggingface.co/AMLAN69/LoRA" - access to finetunned LoRA model


"https://huggingface.co/Qwen/Qwen2.5-3B-Instruct" - access to base model qwen3b

The model is finetunned using mentalhealth conversation dataset. The finetune is done using GRPO(Group Reward Policy Optimization). The techstack used in the process are:- Unsloth for faster finetunning, Vllm for faster inference, QLoRA(Quantized Low Rank Adaptation) using bitsandbytes and peft. 

🧠 AI Mental Health Chatbot
A lightweight, privacy-conscious mental health chatbot that simulates therapist-like conversations using a fine-tuned Small Language Model (SLM). Built during the Infinity AI Hackathon at Tredence, Bangalore, this project emphasizes empathetic support, resource efficiency, and real-time crisis intervention.

💡 What It Does
Offers empathetic, CBT/DBT-based responses to user queries.

Detects potential distress signals and provides immediate crisis helpline support.

Simulates real conversations with a therapist—calm, supportive, and human-like.

Includes wellness tools like ambient calming sounds, guided exercises, and Indian mental health helplines.

🚀 Key Features
LoRA + 4-bit Quantization: Efficient fine-tuning with minimal compute (runs on <6GB VRAM).

Unsloth Training: Fast & memory-efficient LoRA fine-tuning (70% faster).

vLLM Inference: Blazing fast inference (22 tokens/sec on RTX 3090).

GRPO (Reinforcement Learning): Improves empathy, context awareness & reduces hallucinations.

Modular LoRA Adapters: Switch between therapy styles (CBT, DBT, etc.).

Crisis Detection System: Triggers emergency help and displays local helplines based on keywords.

