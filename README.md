# Adversarial attacks

Small pertrubations in inputs that are not noticeable for humans, can make inputs completely unrecognizable for deep neural networks, similar to optical illusions for humans. These are called adversarial attacks, and they can be transfered between networks; They can also be applied in real-world settings in the form of stickers or audio recordings. This is a problem for neural networks in safety-critical environments as well as an illustration of a lack of generalization capabilities. 

In this project two methods of white-box adversarial attacks are tested: FGSM and PGD.
This project was conducted as part of the DD2424 Deep Learning course in KTH Royal Institute of Technology. 

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
