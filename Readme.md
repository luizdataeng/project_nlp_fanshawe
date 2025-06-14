# NLP Project

This repository contains Natural Language Processing (NLP) course materials and projects.

## Create a virtual environment named .venv
python3.13 -m venv .venv

## Activating the Virtual Environment

After creating the virtual environment, you need to activate it.

### On macOS/Linux:

```bash
# If your virtual environment is named .venv and is in the project root:
source .venv/bin/activate
```

## Project Structure

Add your project structure and additional documentation here.

## Install uv package
curl -Ls https://astral.sh/uv/install.sh | sh



## Step 1: Upgrade pip, setuptools, and wheel (optional with uv, but included for compatibility)

```bash
uv pip install -U pip setuptools wheel
```

## Step 2: Install spaCy

```bash
uv pip install -U spacy
```

## Step 3: Download the English model

```bash
python -m spacy download en_core_web_lg


## Run requirements.txt
uv pip install -r requirements.txt
