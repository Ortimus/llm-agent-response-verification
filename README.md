# LLM Agent Response  Verification

This repository contains notebooks demonstrating practical patterns for **verifying LLM agent outputs**.
It focuses on schema validation, evaluator-driven refinement loops, and human-in-the-loop escalation with realistic examples.

## Contents

- `notebooks/`
  - `agent_response_verification.ipynb` — Master notebook with OpenAI/Groq-powered examples and explanatory text. Can be run in simulation mode too.
  - `schema_validation_comparison` — Focused notebook with Pydantic and JSON Schema validation examples.

- `requirements.txt` — Python dependencies.

## Quick start

1. Clone or download the repository.
2. Create a Python environment (recommended: `python >=3.9`).
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Open notebooks in Jupyter or VSCode. 

To run live OpenAI examples, set your OPENAI_API_KEY in .env
To run live Groq examples, set your GROQ_API_KEY in .env
If there is no .env file or none of these keys are defined, the code should run in simulation mode.



## Notebooks

- The notebooks include both **simulated runs** (so you can see behavior without an API key) and **live-capable code** for Groq. Replace the placeholder API key and run cells to execute live.

## License

MIT License — see `LICENSE` file.

---

