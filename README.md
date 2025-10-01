Animals Classification Project

Contents
--------
- animals_classification.ipynb   : Jupyter Notebook (runnable in Google Colab)
- requirements.txt               : Python dependencies
- dataset/                       : Empty folder structure where you place your images
  - train/
    - bird/
    - cat/
    - deer/
    - dog/
    - frog/
    - horse/
  - val/
    - bird/
    - cat/
    - deer/
    - dog/
    - frog/
    - horse/
  - test/
    - bird/
    - cat/
    - deer/
    - dog/
    - frog/
    - horse/

How to run (Google Colab)
-------------------------
1. Upload this repository zip to Google Drive or unzip locally.
2. Open Google Colab: https://colab.research.google.com/
3. Upload 'animals_classification.ipynb' to Colab or open it from Drive.
4. If using Colab, enable GPU: Runtime -> Change runtime type -> GPU (e.g., Tesla T4).
5. Install dependencies (if not preinstalled) by running:
   !pip install -r requirements.txt
6. Prepare your dataset in the folder 'dataset/' with the structure above.
   - You can upload the dataset to Colab or mount Google Drive.

Notes
-----
- The notebook uses MobileNetV2 for transfer learning and an SVM baseline using HOG features.
- The notebook is written to be runnable in Colab; some cells download or preprocess the dataset.
- Set random seed for reproducibility when running experiments.
- If your dataset is large, prefer training on cloud GPU.

If you need me to run the notebook and produce results, tell me where your images are (upload them here or provide a zip).
