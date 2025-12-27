# NGPT
HELLO!
This project is quite important to me as it is my first major( or minor) implementation of the transformer archietecture with the goal of recreating shakespearean like texts. 
It serves as one of the foundational  stepping stones in my ai journey.
# NanoGPT: Character-Level Transformer

A minimal, from-scratch implementation of a **Decoder-only Transformer** (GPT-style) for character-level text generation. This project is inspired by Andrej Karpathy's gpt walk through and serves as an educational deep dive into the architecture that powers modern LLMs.

##  Overview
This model is trained on the **Tiny Shakespeare** dataset. Instead of predicting words, it operates at the character level, learning to associate patterns of letters, punctuation, and whitespace to generate text that mimics the style of Elizabethan drama.

### Key Features:
* **Self-Attention Mechanism:** Implements Query, Key, and Value vectors for token communication.
* **Multi-Head Attention:** Multiple parallel attention "heads" to capture diverse linguistic patterns.
* **Residual Connections & LayerNorm:** Ensures stable training for deeper network architectures.
* **Causal Masking:** Prevents the model from "looking into the future" during training.

---

## 🛠 Setup & Installation

1. **Clone the repository:**
   ```
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
   cd your-repo-name
   ```
2. **Install Requirements:**
   pip install -r requirements.txt
