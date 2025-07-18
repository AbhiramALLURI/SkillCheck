# SkillCheck
Check your resume's suitability with the job description and find ways to improve it



SkillCheck is an intelligent resume screening tool that analyzes candidate resumes against a job description using Google’s Gemini Pro model. It extracts structured applicant data, evaluates eligibility, and provides AI-generated upskilling advice.

Live Demo → (Add your Streamlit Cloud or Render URL)

🚀 Features

✅ Compare multiple resumes to a single JD
✅ Extract structured data (skills, experience, education, etc.)
✅ Gemini-based smart eligibility assessment
✅ AI-driven personalized upskilling recommendations
✅ Easy-to-use Streamlit interface
✅ Supports PDF, DOCX, and TXT formats

📸 Screenshot


(Add your image after uploading)

📂 Folder Structure

skillmap/
│
├── analyzer.py         # Core Gemini-powered logic
├── streamlit_app.py    # UI using Streamlit
├── README.md
└── requirements.txt
🛠️ Setup Instructions

Clone the repository:
git clone https://github.com/yourusername/skillmap.git
cd skillmap
Install dependencies:
pip install -r requirements.txt
Set your Gemini API key:
Open analyzer.py and replace:
genai.configure(api_key="your_gemini_api_key_here")
Run the Streamlit app:
streamlit run streamlit_app.py
🧪 Tech Stack

Python 🐍
Streamlit ⚡
Google Generative AI (Gemini Pro)
LangChain document loaders
🔐 Note on API Key

This app uses Gemini Pro via the google.generativeai library. You can get your key here:
https://makersuite.google.com/app/apikey

Store your API key securely in environment variables or st.secrets if deploying.

🧠 AI Use Case

Instead of basic keyword matching, SkillMap extracts applicant skills and experience and compares them meaningfully to the JD, returning structured eligibility and upskilling feedback. It answers:

“Is this candidate a good fit? If not, what do they need to learn?”
🤝 Contributing

Contributions are welcome! Fork the repo and raise a PR.

📬 For any suggestions, feedback or collaboration:
abhiramalluri05@gmail.com

Let me know if you'd like this pushed into a README.md file or zipped with the app.
