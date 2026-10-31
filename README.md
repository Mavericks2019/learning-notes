# Word2Vec Notes

A concise English guide to Word2Vec, based on a beginner's questions.

- [Read the PDF](word2vec-notes.pdf)
- [LaTeX source](main.tex)

Includes one network diagram, layer and weight definitions, and 12 short questions and answers. The examples explain one-hot inputs, embedding lookup, context predictions, sentence boundaries, and training targets.

The main model is **Skip-gram with full Softmax**.

## Build

Run from the repository directory with a LaTeX distribution and `latexmk` installed:

```sh
latexmk -pdf -jobname=word2vec-notes main.tex
```

The output is `word2vec-notes.pdf`. Build logs and temporary preview files are ignored by Git.
