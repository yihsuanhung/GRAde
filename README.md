# GRAde
A GRA detection pipeline

## Clone GRAde via Git Large File Storage (LFS) 
Install Git Large File Storage: https://git-lfs.github.com/
```
git lfs install
git lfs clone https://this/repository.git
```

## Install GRAde via miniconda
First, install miniconda. 
<br>
If you have miniconda or anaconda installed, skip this step.
<br>
The official instructions of miniconda: https://conda.io/projects/conda/en/latest/user-guide/install/index.html 
<br><br>
Then, install GRAde dependencies with the following command
```
conda env create -n GRAde --file environment.yml
```
Done!
<br><br>

## Test your installation
```
python GRAdetection.py 
```
<br><br>
July 2020
