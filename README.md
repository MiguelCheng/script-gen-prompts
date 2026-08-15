# 🎬 LookUp Media — AI Video Automation & Prompt Engine

> **Role Trial Task Submission:** AI Content & Automation Specialist / Prompt Engineer  
> **Model Target:** Claude 3.5 Sonnet / GPT-4o  
> **Primary Objective:** Production-Ready Video Script Outline & 5-Way Consistency Video Prompt Engine  

---

## 📌 Submission Navigation

- 🛠️ **[Master System Prompt (Deliverable 1)](./system_prompts/master_narrative_engine.md)** — The complete v6 System Prompt enforcing JSON schemas, runtime scaling, and visual anchor tokens.
- 🪵 **[Iteration Log (Deliverable 2)](./docs/iteration_log.md)** — Detailed failure logs, edge-case breakdowns, and the v1 ➔ v6 prompt progression.
- 📐 **[Scale Evaluation Rubric (Deliverable 3)](./docs/evaluation_rubric.md)** — 3-Tier quality monitoring system (LLM-as-a-Judge, automated regex, drift detection) for 1,000+ daily runs.
- 📂 **Example Generated Outputs (Validation):**
  - [`sample_mafia_romance.json`](./examples/sample_mafia_romance.json) *(Mid-Form / Emotional Drama)*
  - [`sample_scifi_survival.json`](./examples/sample_scifi_survival.json) *(Short-Form / High-Tension Sci-Fi)*

---

## 📘 Non-Technical Quick-Start Guide (Prompt Library)

### **What This Tool Does**
Takes any story title, runtime, and genre input and automatically generates a structured video script outline complete with ready-to-use image and video generation prompts for **Midjourney v6**, **Runway Gen-3**, **Luma**, and **ElevenLabs**.

### **How to Run in 3 Steps**
1. **Copy the System Prompt:** Open [`system_prompts/master_narrative_engine.md`](./system_prompts/master_narrative_engine.md) and paste it into ChatGPT (GPT-4o) or Claude 3.5 Sonnet.
2. **Provide Your Inputs:** At the bottom, type your target details:
   ```text
   Title: "Your Video Title"
   Runtime: "120 Seconds" | "30 Minutes"
   Genre: "Mafia Romance" | "Sci-Fi Survival" | "Historical Mystery"