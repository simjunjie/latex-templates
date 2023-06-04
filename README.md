# LaTeX Templates
This project contains templates for different LaTeX document classes.

## Updating the git history
Commit the changes to the respective branch.
Update `<root>/README.md`.
Then
```
git checkout <updated-branch>
git rebase root
```

## Article Build Sequence
The build sequence is as follows:
```
pdflatex ➞ biber ➞ pdflatex ➞ pdflatex
```

## llncs Build Sequence
The build sequence is as follows:
```
pdflatex ➞ bibtex ➞ pdflatex ➞ pdflatex
```

## Beamer Build Sequence
The build sequence is as follows:
```
pdflatex ➞ biber ➞ pdflatex ➞ pdflatex
```