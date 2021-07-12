---
title: Using the PMACS cluster 
---

## Introduction and cluster documentation

Lots of info and docs are available at [https://brainsciencecenter.github.io/bscLPC/](https://brainsciencecenter.github.io/bscLPC/). We won't duplicate that stuff here, but we should deep-link to anything that is particularly relevant.

## Installing/Using conda

To install `conda` in your environment:

1. log into `sciget`

2. from a bare bash shell (i.e., without running `ibash` or `xbash`), run
```
wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh	
bash ./Miniconda3-latest-Linux-x86_64.sh -b -p $HOME/software/pkg/miniconda3
```

3. log out of `sciget`

Now, whenever you want to use conda in the future on `scisub`, you can just run
```
source $HOME/software/pkg/miniconda3/bin/activate 
```
and conda should be added to your path. You can verify this by running `conda` and seeing if the help text prints.


