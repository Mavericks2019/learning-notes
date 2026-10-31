# Learning Notes

A shared repository for learning documents, including editable sources and final PDFs.

## Documents

| Topic | PDF | Source |
| --- | --- | --- |
| Word2Vec: structure and questions | [Read](word2vec-notes.pdf) | [LaTeX](main.tex) |

The Word2Vec note includes one network diagram and 12 short questions and answers about Skip-gram with full Softmax.

## Adding documents

Place each new document project in `documents/<topic>/`, keep its source and final PDF together, and add it to the index above.

## Build the Word2Vec note

Run from the repository directory with a LaTeX distribution and `latexmk` installed:

```sh
latexmk -pdf -jobname=word2vec-notes main.tex
```

The output is `word2vec-notes.pdf`. Build logs and temporary preview files are ignored by Git.
