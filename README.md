# Study Lantern

Study Lantern turns your notes into a concise study guide and practice questions using a locally running open-weight AI model. Your notes stay on your computer.

## Technology

- Python 3 standard library for the web server
- HTML, CSS, and JavaScript for the interface
- Ollama running Google's open-weight Gemma 3 model (`gemma3:1b`)

## Run locally

1. Install and start [Ollama](https://ollama.com/).
2. Download the model: `ollama pull gemma3:1b`
3. Run `python app.py`.
4. Open <http://127.0.0.1:8000>, paste notes, and choose **Make my study guide**.

The model runs locally and the first response may take a little while. Generated material can contain mistakes, so check it against your notes.
