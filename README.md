# Data Dialogues Meet-Up 01-13-2026

This repo goes along with [this deck](https://docs.google.com/presentation/d/167eM1LvP0yp-4H2TI2fZRUFQTBvKiIi4zUuZHvQNCa4/edit?usp=sharing)

## Context
### Unlocking Model Transparency: Gaining Deeper Insight with SHAP Values

Machine learning models can help businesses make important decisions, but often the reasoning behind those decisions is indecipherable, and stakeholders may not trust them. SHAP values, derived from game theory, help bring insight into why machine learning models make their predictions, and they can also allow for more targeted, actionable uses. I will demonstrate the use of SHAP values using practical examples and code snippets.

## How to use:
1. To run this notebook directly from the repo, you'll need poetry installed
2. All necessary dependencies are in the pyproject.toml file
3. Using pyenv and poetry, you can run
```
pyenv install 3.12.10
poetry env use 3.12.10
poetry install
poetry run jupyter notebook
poetry run python -m ipykernel install --user --name={kernel-name}
```
4. Alternatively, you can use snippets of the code in your own work
- Caveat: when using a pipeline, especially one that one-hot encodes features, you’ll need to take extra steps to ensure the code to get SHAP values and feature names works. 
