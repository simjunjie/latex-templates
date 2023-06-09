# LaTeX Templates
This project contains templates for different LaTeX document classes.

## Updating the git history
Commit the changes to the respective branch.
Update `<root>/README.md`.
Then
```
git checkout <updated-branch>
git rebase root
git push -f
```

## Build Sequence
The various build sequence for the different class templates are given below

| Class | Build Sequence |
| ----------- | ----------- |
| article | pdflatex ➞ biber ➞ pdflatex ➞ pdflatex |
| llncs | pdflatex ➞ bibtex ➞ pdflatex ➞ pdflatex |
| beamer | pdflatex ➞ biber ➞ pdflatex ➞ pdflatex |
| poster | pdflatex ➞ biber ➞ pdflatex ➞ pdflatex |
| thesis | pdflatex ➞ biber ➞ pdflatex ➞ pdflatex |