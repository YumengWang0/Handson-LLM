## 🤖 Project: LLM Learning & Hands-on

These Jupyter notebooks cover hands-on implementation and core concepts of Large Language Models (LLMs), from fundamentals to advanced applications.

### 📌 Contents

#### 1. LLM Fundamentals
- Tokenization (BPE, WordPiece)
- Embeddings (word vs contextual)
- Transformer architecture (attention, self-attention, multi-head)
- Positional encoding
- Training objective (causal LM, masked LM)

---

#### 2. Prompt Engineering & Inference
- Zero-shot / Few-shot prompting
- Chain-of-Thought (CoT)
- Prompt templates
- Greedy vs Beam Search vs Sampling (top-k, top-p)
- Temperature and decoding strategies

---

#### 3. Fine-tuning Techniques
- Full fine-tuning vs parameter-efficient methods
- LoRA / QLoRA / PEFT
- Instruction tuning (SFT)
- Dataset formatting (prompt → conversational format)
- Trainer setup (HuggingFace / TRL)

---

#### 4. RAG (Retrieval-Augmented Generation)
- Embeddings + Vector database (e.g., ChromaDB)
- Retriever + Generator pipeline
- Similarity search
- Prompt + context fusion
- Multi-document reasoning

---

#### 5. Multimodal LLMs
- Image + Text models (e.g., BLIP)
- Vision Transformer basics
- Cross-modal attention
- Applications: image captioning, VQA

---

#### 6. LLM Agents
- Tool calling (function calling)
- Agent workflow (Plan → Act → Observe)
- Memory (short-term vs long-term)
- Multi-step reasoning
- Frameworks (LangChain / custom agents)

---

#### 7. Optimization & Deployment
- Quantization (4-bit / 8-bit)
- Inference acceleration
- Batch vs streaming generation
- API vs local deployment
- Cost vs latency trade-offs

---

#### 8. Evaluation & Debugging
- Hallucination analysis
- Prompt sensitivity
- Evaluation metrics (BLEU, ROUGE, human eval)
- Error analysis & improvement loop