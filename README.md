# MindScript Web Playground 🌌

Live interactive playground for **MindScript** — the deterministic prompting language from SAGEWORKS AI.

### Features
- Browse official templates by modality (Text, Diagram, Image, Video, Automation)
- Edit and run MindScript (.ms) programs in-browser
- Stage-by-stage execution with real LLM outputs
- Switch between backends (OpenAI GPT, Google Gemini, or stub for testing)
- Cyber-minimal dark theme

Powered by:
- [mindscript-runtime](https://github.com/PEACEBINFLOW/mindscript-runtime) (bundled)
- [mindscript-templates](https://github.com/PEACEBINFLOW/mindscript-templates) (bundled)

### Live Demo
Once deployed: https://mindscript-web-playground.onrender.com

### Local Development
```bash
git clone https://github.com/PEACEBINFLOW/mindscript-web-playground.git
cd mindscript-web-playground
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

# Create config.yaml in mindscript_runtime/ with your keys (see runtime repo)
streamlit run app.py
