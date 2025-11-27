<img width="1052" height="387" alt="Screenshot 2025-11-27 at 12 23 58 PM" src="https://github.com/user-attachments/assets/250c85b4-0b25-4501-bb6c-74a2475b5ee3" />🌐 AI HUMANIZER PRO
Bridging the Gap Between Artificial Intelligence and Human Resonance
<p align="center"> <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" /> <img src="https://img.shields.io/badge/Platform-IBM%20Challenge-blue?style=for-the-badge" /> <img src="https://img.shields.io/badge/License-MIT-black?style=for-the-badge" /> <img src="https://img.shields.io/badge/TechStack-Python%20%7C%20Flask%20%7C%20Ollama%20%7C%20Gemini%202.0%20%7C%20Sapling.ai-orange?style=for-the-badge" /> </p>

Final Execution SnapShots
<img width="1600" height="955" alt="image" src="https://github.com/user-attachments/assets/af21fe33-fa9e-4be3-a9e6-39a9754e7b2b" />
<img width="1600" height="947" alt="image" src="https://github.com/user-attachments/assets/858c2164-f03b-4ffd-bb2a-7bc28c557200" />


📋 Executive Summary

Generative AI has solved the problem of volume, but introduced a crisis of quality. Modern LLM outputs exhibit:

Low perplexity

Repetitive sentence structures

A distinct “AI Accent”

Synthetic, neutral, emotionless tone

AI HUMANIZER PRO solves this by acting as a post-processing orchestration engine.

Using a hybrid Dual-LLM Architecture (Local LLM + Cloud Reasoning), it transforms robotic, algorithmic text into:

✔ Bursty
✔ Opinionated
✔ Human-like
✔ Undetectable

We don’t just generate content —

We engineer credibility.

🏗 System Architecture

<img width="952" height="610" alt="Screenshot 2025-11-27 at 12 25 38 PM" src="https://github.com/user-attachments/assets/a146cafd-7bf8-4490-8e40-6730e5609e47" />

AI HUMANIZER PRO uses an intelligent Dual-Engine Pipeline balancing privacy, cost, accuracy, and linguistic realism.
<img width="1049" height="388" alt="Screenshot 2025-11-27 at 12 24 52 PM" src="https://github.com/user-attachments/assets/6e708f2b-3135-4213-9032-82e0f3117d94" />

4
Architecture Flow (Mermaid Diagram)
graph LR
A[User Input] --> B(Local Inference Engine)
B -- DeepSeek R1 --> C{Draft Generation}
C --> D(Semantic Refinement Layer)
D -- Google Gemini 2.0 --> E[Humanized Output]
E --> F[Sapling.ai Validation]
F --> G[Client UI / .DOCX Export]

🧠 The “Humanization” Algorithm

Unlike traditional paraphrasers, AI HUMANIZER PRO uses a negative-constraint system that enforces:

1. Burstiness

Alternating sentence complexity to mimic authentic human cognitive flow.

2. Subjectivity

Injects opinion, emotional depth, and human-like variation where LLMs default to neutrality.

3. Vocabulary Filtering

Removes AI-signature statistical outliers such as:

"delve", "tapestry", "crucial", "realm", "landscape", etc.

🚀 Key Features
Hybrid Intelligence

Deep reasoning from DeepSeek R1 (local via Ollama) + stylistic nuance from Gemini 2.0 Flash.

Real-Time AI Detection Audit

Integrated Sapling.ai returns an “AI Probability Score” to validate content authenticity.

Enterprise Document Automation

Auto-generates .docx files with:

Corporate headers

Footers

Page borders

Export templates

Responsive Dark-Mode UI

Zero build steps. Pure HTML5, CSS3, JavaScript.

🛠 Tech Stack
Layer	Technology
Backend	Python, Flask
Local AI Engine	DeepSeek R1 via Ollama
Cloud Reasoner	Google Gemini 2.0 Flash
AI Authenticity Validator	Sapling.ai API
Document Generator	python-docx
Frontend	HTML5, CSS3, Vanilla JS
⚡ Installation & Setup
Prerequisites

Python 3.9+

Ollama installed & running

API Keys

Google Gemini

Sapling.ai

1. Clone the Repository
git clone https://github.com/yourusername/ai-humanizer-pro.git
cd ai-humanizer-pro

2. Virtual Environment
python -m venv venv
source venv/bin/activate
# Windows:
# venv\Scripts\activate

3. Install Dependencies
pip install -r requirements.txt

4. Add Your API Keys

Edit app.py:

SAPLING_API_KEY = "your_sapling_key"
GEMINI_API_KEY = "your_gemini_key"

5. Start Ollama Engine
ollama serve
ollama run deepseek-r1:1.5b

6. Run the Application
python app.py


Access the interface:

http://localhost:5000/

🧪 Proof of Functionality
✔ 1. Ollama DeepSeek R1 Running
>>> ollama list
deepseek-r1:1.5b    ✓ Installed

✔ 2. Gemini API Connectivity
200 OK - gemini-2.0-flash model active

✔ 3. Sapling AI Detection Score
AI Probability: 0.12 (Human-like)

✔ 4. DOCX Export Validation
4
💡 Use Case Scenarios
1. Corporate Communications

Humanizing memos, leadership messaging, emails.

2. Marketing Copy

Improves conversions by removing “salesy AI tone.”

3. Creative Writing

Supports authors while preserving their unique voice.

🔮 Future Roadmap

 Tone Sliders: Sarcasm, Professionalism, Urgency

 Batch CSV Humanization

 Chrome Extension for Gmail/Outlook

📄 License

Distributed under the MIT License.
See LICENSE for more details.

🏆 Built for the IBM Challenge
Redefining the Global Standard of AI-Generated Text.
