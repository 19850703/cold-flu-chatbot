# cold-flu-chatbot
Chatbot for Vaccine Schedule Planning and Consultation in Nova Scotia
# 🧪 Vaccine Schedule Planning and Consultation Chatbot (Nova Scotia)

This is an educational chatbot project designed to help users in Nova Scotia better understand their **vaccine schedules**, eligibility, and preparation guidelines. It uses the **AnythingLLM + Ollama** stack with **Retrieval-Augmented Generation (RAG)** based on official, locally relevant immunization materials.

> ⚠️ **Disclaimer**  
> This chatbot is for educational and research purposes only. It does not provide medical advice, diagnoses, or treatment. Always consult a licensed healthcare provider.

---

## 📌 Project Overview

- **Goal:** Provide accurate, up-to-date information about vaccine schedules and eligibility in Nova Scotia.
- **Powered By:**
  - [✅= Ollama](https://ollama.com) for running LLM models locally (e.g., Llama3, Mistral)
  - [✅ AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) for knowledge-based chatbot capabilities
  - [✅ Nova Scotia Government & Health Canada]([https://novascotia.ca/dhw/cdpc/]

---

## 📁 Project Structure

```bash
cold-flu-chatbot/
├── knowledge_base/
│   ├── knowledge_document_1.pdf     # Cancer immunization guidance
│   ├── knowledge_document_2.pdf     # Flu/COVID/RSV guidelines 2024–25
│   ├── knowledge_document_3.pdf     # NS routine immunization schedule
│   └── knowledge_document_4.pdf     # Eligibility for high-risk conditions
│
├── prompt/
│   └── system_prompt.txt            # Defines chatbot behavior and disclaimers
│
├── documentation/
│   ├── scenario_pack.md             # Background and instructions
│   └── use_case_description.md      # Problem framing and success metrics
│
├── demo/
│   ├── demo_video.mp4               # Screen recording of chatbot usage
│   └── chat_transcript.txt          # Chat logs from AnythingLLM
│
└── README.md                        # This file
