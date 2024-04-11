### Human Protein Sequence Dataset:
https://www.uniprot.org/proteomes/UP000005640

### ESM2 Model
https://huggingface.co/facebook/esm2_t36_3B_UR50D

### Running the Code
To run the code, install all dependencies listed in the first cell of `pytorch_profiler.ipynb` and ensure that the human protein sequence dataset is stored in `human_protein_seq`. Afterwards, select the model to be used in the 3rd cell by changing "MODEL" and "TOKENIZER" as desired, and let the rest of the code run.

To generate plots, run the plotter file. Ensure that the csv respective csv files were linked correctly.