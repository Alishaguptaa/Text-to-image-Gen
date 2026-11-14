# Text-to-Image Generator

A Flask web app that turns text prompts into images using Stable Diffusion via Hugging Face.


## Features

- Generate images from a text prompt
- Download the result


## Setup

```bash
git clone https://github.com/Alishaguptaa/Text-to-image-Gen
cd Text-to-image-Gen


python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

pip install -r requirements.txt
```

Create a `.env` file with your [Hugging Face token](https://huggingface.co/settings/tokens):

```
AUTH_TOKEN=your_token_here
```

Run the app:

```bash
python app.py
```

Then open `http://127.0.0.1:5000`.

## Project Structure

```
├── app.py                      # Flask app
├── templates/index.html        # Frontend page
├── static/style.css            # Styles
├── StableDiffusionImage.ipynb  # Image generation notebook
└── requirements.txt
```

## Tech Stack

Python, Flask, Hugging Face Diffusers, HTML/CSS

## Changes in this fork
