# Decision Trees vs. Neural Networks

Hauptseminar Project WS 2020/2021: Oldies but Goldies (staniek).

This project consists of 2 parts:
 1. Differentiable decision trees
 2. Distilling neural networks into (conventional) decision trees

Both parts explore different ideas for combining neural networks (mostly MLPs) and decision trees (or random forests).

All code is provided as Jupyter Notebooks. There are separate notebooks for each part. Also check out the report. Please note that the report does not include additional information. Most text in the report is just copy & paste from the notebooks.

---
### Setup
Create a new virtual environment using whatever tool you like. Run
```
pip install -r requirements.txt
```
Then also install spacy's `en_core_web_sm` by running
```
python -m spacy download en_core_web_sm
```
Finally run the notebooks. All data is provided by some libraries so you don't need to worry about that.  Also, code is CPU-only, so no GPUs needed.
