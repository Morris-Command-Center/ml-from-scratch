# ML From Scratch

Build core ML algorithms yourself to actually understand them. Not about shipping - about learning.

## Philosophy

- **No high-level wrappers** - understand what's happening
- **Progressive complexity** - start wherever you want, go deeper when curious
- **ADHD-friendly** - each module is self-contained, valuable even in isolation
- **Your pace** - no curriculum pressure, pick what interests you

## Levels

### Level 1: Foundations (numpy only)
- Linear regression from scratch
- Gradient descent visualization
- Logistic regression + classification
- Loss functions and why they matter

### Level 2: Classical ML (minimal sklearn)
- Decision trees (build one yourself)
- Random forests
- K-means clustering
- PCA

### Level 3: Neural Networks (numpy → pytorch)
- Perceptron from scratch
- Backpropagation by hand
- Simple feedforward network
- Same thing in PyTorch

### Level 4: Deep Learning (pytorch)
- CNNs for images
- RNNs/LSTMs for sequences
- Attention mechanism
- Transformer architecture

### Level 5: LLM Internals
- Tokenization deep dive
- Embeddings and vector spaces
- Fine-tuning mechanics
- LoRA/QLoRA why they work

## Quick Start

```bash
# Create virtual environment
python -m venv venv
venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt

# Start Jupyter
jupyter notebook
```

## Structure

Each module contains:
- `theory.md` - Concepts explained simply
- `learn.ipynb` - Theory + code + inline visualizations
- `exercises.ipynb` - Things to try/break/experiment with
