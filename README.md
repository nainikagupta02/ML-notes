# ml notes

personal machine learning study notes by [nainika gupta](https://nainikagupta02.github.io/).

**read the notebook:** https://nainikagupta02.github.io/ML-notes/

## structure

- foundations
- training & evaluation
- supervised learning
- trees & ensembles
- clustering
- dimensionality reduction
- comparisons

feature engineering, curse of dimensionality, gradient descent, covariance matrix, residuals & the bias–variance tradeoff, and the supervised learning overview have been added as concise notes adapted from my study pages. the remaining topics are placeholders.

## fill in a note

1. open a topic’s `.qmd` file under `notes/`.
2. replace the placeholders with your notes; the format is markdown with support for equations and code.
3. remove the `not yet written` badge when ready.
4. commit the changes. github actions rebuilds and publishes the site automatically.

keep headings and prose lowercase. preserve the case required by equations, variable names, code, and references.

## add a topic

copy `templates/note.qmd`, give it a title, and save it in the appropriate section under `notes/`. add its path to `_quarto.yml` and link it from the section’s `index.qmd`.

## local preview

install quarto 1.9.38 or newer, then run `quarto preview` from this folder. use `quarto render` to build the site in `_site/`.
