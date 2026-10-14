# NLP Lab 8 — Part-of-Speech (POS) Tagging

**Name:** Hadi Muneer Abu Allairat  
**Student ID:** 2230005761

Solution notebook: [`Lab8_Solution_Part_of_Speech.ipynb`](Lab8_Solution_Part_of_Speech.ipynb)

POS tagging with NLTK (`pos_tag`) and spaCy (`en_core_web_sm`), including coarse vs
fine-grained tags and displaCy visualisation. Tasks 1, 2 and 3 are answered at the end.

The lab's own demonstration cells are kept unchanged, with analysis added underneath. Two bugs
in them are explained and corrected alongside: the `pos_tag` demo tags each word in isolation
(which changes 3 of 9 tags on its own example sentence), and the adjective finder's
`if 'JJ' in i` test misses comparative and superlative adjectives.

All cells are executed and their outputs saved, so the notebook can be read without re-running
it. Every tag and count quoted in the written answers comes from those outputs.
