# scribble

A website for comic book OCR and text generation: [Website](https://28619.gradio.app)

## Setup to run Gradio App locally
1. Clone repo.
2. Create a python3 venv using `python3 -m venv env` and then `source env/bin/activate` or `<venv>\Scripts\activate.bat`, depending on your OS.
3. Run `make install` to download the dependencies.
4. Run `export COHERE_APIKEY=REPLACE`, replacing `REPLACE` with your Cohere API key.
5. Run `app.py` (with `--flagging` if you want to allow users to flag generations as incorrect, offensive, etc.), and you now have a local Gradio app!

## Notes
- Project for the TAMU Datathon to solve the [CBRE Challenge: Get in Line](https://tamudatathon.com/challenges/docs/cbre) and the [Best Use of NLP by Cohere - MLH](https://tamudatathon.com/challenges/docs/mlh_challenges#best-use-of-nlp-by-cohere---mlh) challenges.
- Since we are open-sourcing the necessary code for others to create their own Gradio link, please only use the one provided in this repo for privacy reasons.

## Credit
- Tesseract for their [OCR engine](https://github.com/tesseract-ocr/tesseract).
- [Cohere.ai](https://cohere.ai/) for their text generation API.
