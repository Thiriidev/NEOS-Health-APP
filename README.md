# NEOS-Health-APP
AI-powered health insights for patients &amp; accelerated clinical trial recruitment.
NEOS Health App – AI-Powered Blood Test Analysis & Clinical Trial Matching

📌 Project Overview

NEOS Health App is an AI-powered patient pre-screening platform that enables users to:
✅ Upload medical reports (PDFs, images, etc.).✅ Get AI-driven health insights using IBM Watson & OpenAI GPT-4.✅ Match with relevant clinical trials based on their health data.✅ Securely store & control their health records using Blockchain & Web3 security.

🛠 Tech Stack

Frontend: React.js + Tailwind CSS

Backend: Flask + FastAPI

AI Processing: IBM Watson, OpenAI GPT-4, Google Health API

Blockchain Security: Ethereum (Solidity Smart Contracts), IPFS for decentralized storage

🚀 Features

✔ AI Health Report Analysis – Scans & interprets blood, urine, and medical reports.
✔ Clinical Trial Matching – Identifies eligible patients for trials.
✔ Blockchain Security – Patients control access to their data.
✔ Decentralized Storage – Ensures privacy with IPFS & Smart Contracts.

🔧 Project Setup

1️⃣ Install Dependencies

Run the following command to install required libraries:

pip install -r requirements.txt

(Ensure you have Python 3.8+ installed)

2️⃣ Setup API Keys

Create a .env file and add:

IBM_WATSON_API_KEY=your_ibm_api_key
OPENAI_API_KEY=your_openai_api_key
INFURA_PROJECT_ID=your_infura_project_id

3️⃣ Run the Application

Google Colab:

!python colab_main.py

Local PyCharm Setup:

python app.py

📡 API Usage

To analyze a medical report via API:

curl -X POST -F "file=@sample_report.pdf" http://localhost:5000/analyze

Response:

{
  "Extracted Data": "Hemoglobin: 13.5 g/dL...",
  "AI Analysis": "Hemoglobin level normal...",
  "Blockchain Status": "Stored on Ethereum"
}

📜 Commit History & Development Process

🔄 GitHub Best Practices Followed:

✅ Feature Branching – Separate branches for AI, Blockchain, and UI.
✅ Frequent Commits – Documenting every major implementation.
✅ Detailed Commit Messages – Clearly describing changes.
✅ Pull Requests & Code Reviews – Structured development approach.

🔍 Example Commit History (Milestones):

feat(ai-processing): Implemented OCR & NLP extraction

feat(blockchain): Added Ethereum-based smart contract for patient data access

fix(ui): Improved React.js dashboard responsiveness

👨‍💻 Contributors

Thiriidev Kumar Murlidaran – Developer & Founder

📞 Contact

For inquiries, email: neosdevelopmentglobal@gmail.com

