# PUNchlineGenerator

Generates a pun-like variation of a user-entered phrase. Incorporates a Levenshtein distance algortithm in conjunction with the CMU Pronouncing Dictionary.

## Contains: 
- `Edit_Distance.ipynb` Jupyter Notebook file with code showing how edit distance works
- `Pronunciation.ipynb` Jupyter Notebook showing options for phonetic representations
- `PUNchline.ipynb` Jupyter Notebook file with the actual "pun" code
- `real_words_lower.csv` CSV file of "real" words and their pronunciations. (CMU Dict contains some weird words that are removed from this)
- `all_words.csv` CSV with words, pronunciations, and parts of speech. This includes some plurals that were not in Brown Corpus for some reason
- `scripts/` Scripts to make setting up the enviroment easier for those who is Anaconda


## Setup

If you just want to run the main code, not setup is required. These additional libraries are for supplementary material.

#### For those who use Anaconda:

- Clone repository locally
- From within the repo, call `bash scripts/setup.sh`. This should create a conda environment for you.
- Activate environment with `source activate pun_generator`


#### Otherwise, these are the requirements:

- nltk
- jupyter
- fuzzywuzzy and fuzzywuzzy[speedup] https://github.com/seatgeek/fuzzywuzzy
