# PUNchlineGenerator

Generates a pun-like variation of a user-entered phrase. Incorporates a Levenshtein distance algortithm in conjunction with the CMU Pronouncing Dictionary.

Contains: <ul>
<li>Jupyter Notebook file with code showing how edit distance works
<li>CSV file of "real" words and their pronunciations. (CMU Dict contains some weird words that are removed from this)
<li>Jupyter Notebook file with the actual "pun" code
</ul>

Current status: returns the input string (as a list) with one word substituted for a similar-sounding word.
