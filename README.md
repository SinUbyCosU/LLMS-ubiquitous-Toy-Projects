# LLMS-ubiquitous-Toy-Projects
Place where i dump my toy LLM projects
# GitaGPT Tutorial (NanoGPT Style)

Character-level GPT trained from scratch on Bhagavad Gita text. Inspired by Karpathy’s GPT from scratch tutorial.

---

##  What this is

- Transformer (built from scratch, no HF)
- Trained on Bhagavad Gita (text file)
- Uses character-level tokenizer
- Generates Gita-style text
- Gradio chatbot to demo it

---
 #####Note: The dataset is very toy-sized — handcrafted and small — meant for demonstration purposes only.
Don't expect real Vedantic wisdom. Expect mildly wise-sounding gibberish.####
## How to run

```bash
# Clone the repo
git clone https://github.com/SinUbyCosU/LLMS-ubiquitous-Toy-Projects.git
cd LLMS-ubiquitous-Toy-Projects/MiniGitaGpt

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the chatbot interface
python gita_gpt_chat.py

