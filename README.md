# DD2424-project
Deep learning in data science

## Ovearleaf project
https://www.overleaf.com/9578595952hnrxvvymqytp

## Install and run

### Install
Open a terminal at folder and run
```
conda env create -f environment.yml
```

### Run
```
conda activate DD2424 && jupyter notebook
```

## Git basics

First pull updates from remote
```
git pull
```

You can always see which files are staged, updated and not tracked with
```
git status
```

Add the file to index 
```
git add <file>
```
or add all files with
```
git add .
```

Then commit all staged files with an *mandatory* message
```
git commit -m "The script now handles the X case"
```

At last, upload to the remote
```
git push
```
