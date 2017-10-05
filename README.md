# PUNchlineGenerator

Generates a pun-like variation of a user-entered phrase. Incorporates a Levenshtein distance algortithm in conjunction with the CMU Pronouncing Dictionary.

Contains: <ul>
<li>`Edit_Distance.ipynb` Jupyter Notebook file with code showing how edit distance works</li>
<li>`Pronunciation.ipynb` Jupyter Notebook showing options for phonetic representations</li>
<li>`PUNchline.ipynb` Jupyter Notebook file with the actual "pun" code</li>
<li>`real_words_lower.csv` CSV file of "real" words and their pronunciations. (CMU Dict contains some weird words that are removed from this)</li>
<li>`all_words.csv` CSV with words, pronunciations, and parts of speech. This includes some plurals that were not in Brown Corpus for some reason</li>
<li>`scripts/` Scripts to make setting up the enviroment easier for those who is Anaconda</li>
</ul>

## Setup

For those who use Anaconda:
<ul>
<li>Clone repository locally</li>
<li>From within the repo, call `bash scripts/setup.sh`. This should create a conda environment for you.</li>
<li>Activate environment with `source activate pun_generator`</li>
</ul>

Otherwise, these are the requirements:
<ul>
<li>nltk</li>
<li>jupyter</li>
<li>fuzzywuzzy and fuzzywuzzy[speedup] https://github.com/seatgeek/fuzzywuzzy</li>
</ul>