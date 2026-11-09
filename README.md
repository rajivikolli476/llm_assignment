# Georgia IMF Report Analysis

This project analyses Georgia’s 2026 IMF Article IV Consultation report using Python and a small language model. The notebook extracts PDF text, summarises sections, retrieves relevant passages and produces a four-panel dashboard.

## Files needed

Download these files from this repository:

- The Jupyter notebook (`.ipynb`)
- `georgia.pdf`

The PDF is the 63-page Georgia report, IMF Country Report No. 26/133.

## Running the notebook

1. Open the notebook in Google Colab.
2. Select **Runtime → Change runtime type → T4 GPU**.
3. Upload `georgia.pdf` to the Colab working folder. Keep this filename unchanged.
4. Run the cells in order, from Cell 1 to Cell 15.

The first run installs the required packages and downloads the models. It takes longer than later runs because saved responses and embeddings are reused while the cache remains available.

A Colab runtime reset may remove local files and caches.
