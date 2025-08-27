# 📊 Auto PPT Generator

Auto PPT Generator is a simple web app that turns bulk text or markdown into a **fully formatted PowerPoint presentation**, styled according to a user-provided template.  

The app uses an LLM of your choice (e.g., OpenAI, Anthropic, Gemini) with your own API key to intelligently split text into slides, apply a structure, and reuse template styles, colors, fonts, and images.

---

## 🚀 Features
- Paste bulk text, markdown, or prose
- Optionally guide tone/structure (e.g., "Investor Pitch Deck")
- Upload your own `.pptx` or `.potx` template
- Generate new presentation with matching style
- Download `.pptx` output file
- Your API key is never stored

---

## 🛠️ Installation & Setup
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/auto-ppt-generator.git
   cd auto-ppt-generator

2. Install dependencies:
 ```bash
pip install -r requirements.txt

requirements.txt
streamlit
openai
python-pptx

3. Run the app locally:
 ```bash
streamlit run app.py

4. Open the local URL shown (usually http://localhost:8501).

🌍 Deployment
Option 1: Streamlit Cloud (recommended)

Push your repo to GitHub.

Go to Streamlit Cloud
.

Click New App, select your repo, branch, and app.py.

The app builds and deploys automatically.

You’ll get a public link like:

https://your-username-auto-ppt-generator.streamlit.app

Option 2: Render

Add a Procfile to your repo:

web: streamlit run app.py --server.port=$PORT --server.address=0.0.0.0


Push to GitHub.

Create a new Web Service on Render
, connect your repo, and deploy.

You’ll get a link like:

https://auto-ppt-generator.onrender.com



