# 📝 AdHoc‑LM
*A transformer‑based language model built from scratch, specialized for diplomacy, resolutions, and debate (work in progress).*

---

## 🌍 Overview
**AdHoc‑LM** is my ongoing project to **build a large language model from scratch in PyTorch**.  

The long‑term goal is to create a model specialized in **diplomatic communication, resolution drafting, and debate simulation**.  
Right now, the project is in **Phase 1: Core LLM Build**, where I’m implementing the fundamental transformer components and training a **Mini‑AdHoc‑LM** on small datasets (e.g., Shakespeare, TinyStories, WikiText).  

This repo will be updated as I progress through each phase:  
1. Core LLM Build (now)  
2. Scaling & Engineering  
3. Domain Specialization  
4. Application & RAG Integration  
5. Visualization & Portfolio Polish  

---

## 🔹 Current Status (Phase 1)
- ✅ Repository initialized  
- ✅ Environment set up (PyTorch, CUDA, Hugging Face)  
- ✅ Tokenizer + embeddings implemented  
- 🚧 Working on: Multi‑head attention module  

---

## 📊 Dataset (Phase 1)
- **Shakespeare text** (tiny, great for debugging)  
- **TinyStories dataset** (lightweight natural language corpus)  
- Later: WikiText‑103 & OpenWebText for scaling  

**Next Steps:**  
- Implement feedforward layers & normalization  
- Add causal masking for autoregressive training  
- Build training loop  
- Train **Mini‑AdHoc‑LM** (5–10M parameters) on Shakespeare dataset  

---

## 🏗️ Architecture (WIP)
Currently implementing a **decoder‑only transformer** (GPT‑style):  
- ✅ Token + positional embeddings  
- 🚧 Multi‑head self‑attention  
- ⏳ Feedforward layers + normalization  
- ⏳ Causal masking  

---

## 🧩 Roadmap
- [x] Initialize repo + environment  
- [x] Implement tokenizer + embeddings  
- [ ] Multi‑head attention  
- [ ] Training loop for Mini‑AdHoc‑LM  
- [ ] Pretrain Mini‑AdHoc‑LM on Shakespeare  
- [ ] Publish initial training curves  

---

## 🙌 Acknowledgements
- Sebastian Raschka — *“Build a Large Language Model (From Scratch)”*  
- Hugging Face community datasets  