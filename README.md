# LLM Agent Evaluation Patterns — Response Verification

This repository contains notebooks, examples, and utilities demonstrating practical patterns for **verifying LLM agent outputs**.
It focuses on schema validation, evaluator-driven refinement loops, and human-in-the-loop escalation with realistic examples using Groq.

## Contents

- `notebooks/`
  - `Master_Agent_Verification_Groq.ipynb` — Master notebook with Groq-powered examples and explanatory text.
  - `Agent_Response_Validation.ipynb` — Focused notebook with JSON Schema, Pydantic retry loop, and evaluator-driven correction examples.
- `images/`
  - `evaluator_loop.png` — Diagram showing the evaluator→refinement loop.
- `examples/` — Lightweight example scripts for quick reference.
- `utils/` — Helper modules (Groq client wrapper, evaluator helpers).
- `requirements.txt` — Python dependencies.

## Quick start

1. Clone or download the repository.
2. Create a Python environment (recommended: `python >=3.9`).
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Open notebooks in Jupyter or VSCode. To run live Groq examples, set your Groq API key:

```python
from utils.groq_client import make_groq_client
client = make_groq_client("YOUR_GROQ_API_KEY")
```

## Notebooks

- The notebooks include both **simulated runs** (so you can see behavior without an API key) and **live-capable code** for Groq. Replace the placeholder API key and run cells to execute live.

## License

MIT License — see `LICENSE` file.

---

*Created by Sumitro Palit — inspired by applied AI evaluation research.*
