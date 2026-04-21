# AgentHire-Extractor-Model

Notebook workflow for building the AgentHire JSON resume extractor:

- `agenthire_extractor_training.ipynb`
  - Phase 1: Generate supervised JSON extraction data from Kaggle resumes using local Ollama `llama3.2`
  - Phase 2: Fine-tune `HuggingFaceTB/SmolLM2-360M` with Unsloth + TRL
  - Phase 3: Export model artifacts and GGUF output for local inference
