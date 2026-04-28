# RAG_FRAMES

Course project for INFO371 - Research Topics in Language Processing, University of Bergen

# Notebooks
- 01_bm25_retrieval.ipynb - Constructing the corpus and doing BM25 indexing
- 02_baselines.ipynb - Creating and running four baseline models (B1-B4)
- 03_multihop_rag.ipynb - Creating and running the C1 and C2 RAG models
- 04_evaluation.ipynb - Running different evaluations; Token F1, EM, Retrieval Recall and LLM-as-Judge
- 05_error_analysis.ipynb - Doing 2x2 error matrix analysis and doing more in-depth analysis on the models

# Data
- titles.json - Contains all the retrieved article titles
- The Wikipedia corpus (`corpus.json`, 60MB) and BM25 index (`bm25_index.pkl`, 47MB) are too large for GitHub and can be accessed here: [Google Drive](https://drive.google.com/drive/folders/1GJTkfjuT4Omc-oIc_FY52V_qvk49TVz4?usp=drive_link), along with all the other files created by the notebooks.

# Predictions
Contains various information regarding the predictions made for each model. For each model we have a json file that shows what each model predicted to what specific question. You can also find information on how many gold articles were needed and which ones specifically, how many articles the model retrieved (if any) and specifically which ones it retrieved.

# Results
Contains json files of what each model answered, to what question, and if the LLM gave the specific answer correct or incorrect (marked as true or false).
There is also a main results table which contains the main evaluation results.
In addition there are three figures saved as .png, which shows various interesting results and which is a part of the error analysis.
