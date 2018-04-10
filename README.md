## IPython Notebooks for exploring Natural Language Processing in Python  ##

1. introduction to NLTK - Explore a Corpus and Treebank  
```
corpora.ipynb
```
2. Tokenising Text and Parts-Of-Speech  
```
tokenisation.ipynb
```
3. Grammer Structure and Dependency Trees   
```
grammar.ipynb   
```
4. Classification of Sentences using Machine Learning  
```
classification.ipynb
```
To add file to GitHub Initialize the local directory as a Git repository.
```
git init
git add .
#Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'
git commit -m "First commit"
#Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use
'git reset --soft HEAD~1' and commit and add the file again
git remote add origin <remote repository URL >
#if fatal: remote origin already exists. then change origin to origin1 
git push origin master
#or delete the origin
git remote rm origin
```
