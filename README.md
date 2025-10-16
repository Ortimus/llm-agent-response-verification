# LLM Agent Response  Verification

This repository contains notebooks demonstrating practical patterns for **verifying LLM agent outputs**.
It focuses on schema validation, evaluator-driven refinement loops, and human-in-the-loop escalation with realistic examples.

## Contents

- `notebooks/`
  - `agent_response_verification.ipynb` — Master notebook with OpenAI/Groq-powered examples and explanatory text. Can be run in simulation mode too.
  - `schema_validation_comparison` — Focused notebook with Pydantic and JSON Schema validation examples.

- `requirements.txt` — Python dependencies.

- '.env' file - Optional

Before running the project, if you want to call OpenAI or Groq, please ensure you have a .env file in your project root with the appropriate  key:

```.env
OPENAI_API_KEY=<your OpenAI API Key>

or

GROQ_API_KEY=<your GROQ API Key>
```

Note: Never commit your .env file or API keys to version control.

If there is no .env file or none of these keys are defined, the code should run in simulation mode.


## Quick start

1. Clone or download the repository.
2. Create a Python environment (recommended: `python >=3.9`).
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Open notebooks in Jupyter or VSCode.
5. Note: I have checked in the llm-env folder, so you can source that and use it instead of creating your own virtual env.



## Notebooks

- The notebooks include both **simulated runs** (so you can see behavior without an API key) and **live-capable code** for OpenAI or Groq.
- Populate the appropriate  API key in the .env file and run cells to execute live.

## License

MIT License — see `LICENSE` file.

---

