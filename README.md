# 🌍 MeetMind: AI-Driven Precision Agriculture

**MeetMind** is an intelligent climate resilience platform designed for farmers. It leverages the power of **AMD Instinct™ MI300X** to provide real-time weather analytics and automated farming insights.

## 🚀 Key Features
- **High-Performance AI:** Uses Llama 3.1 models for climate data analysis.
- **AMD Powered:** Optimized for **AMD Instinct MI300X** using **ROCm 7.2** and **vLLM** for ultra-fast inference.
- **Smart Automation:** Integrated with **n8n** for automated alerts and smart reporting via SMS/Email.
- **Interactive Dashboard:** A clean UI to visualize weather patterns and crop recommendations.

## 🛠️ Tech Stack
- **Hardware:** AMD Instinct MI300X (192GB VRAM).
- **LLM:** Llama 3.1 (via Hugging Face).
- **Backend:** Python, FastAPI, vLLM.
- **Automation:** n8n.
- **Frontend:** Streamlit / React (ذكر سمية اللي خدمتي بيه).

## 💡 Why AMD?
By using the **AMD Instinct MI300X**, we achieved high throughput and low latency, which is crucial for real-time agricultural monitoring. The massive 192GB VRAM allowed us to load large models effortlessly, ensuring farmers get instant insights even with complex datasets.

## 🔧 Installation & Setup
1. **Clone the repo:** `git clone https://github.com/yourusername/MeetMind.git`
2. **Install dependencies:** `pip install -r requirements.txt`
3. **Run the Backend:** `python main.py`
4. **Access n8n:** Import `workflow.json` into your n8n instance.

## 🏆 AMD Developer Hackathon 2026
This project was built as part of the **AMD AI Developer Hackathon** on Lablab.ai.
The system includes an automated n8n workflow that receives AI-generated weather reports via Webhooks, logs them into Google Sheets for historical tracking, and sends instant email alerts to users.
