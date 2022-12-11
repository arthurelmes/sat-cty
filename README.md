# sat-cty Satellite Data City Summary

### Authors: 
 - Arthur Elmes (arthur.elmes@gmail.com)
 - Bily Brown (bilyhasmail@gmail.com)

 
 ### Environment 
 You'll need to use a Python runtime environment with the required libraries.
 The simpest way to do this is to use `conda`, which is a Python environment and
 package management application (https://docs.conda.io/projects/conda/en/latest/user-guide/install/).
 Note that Miniconda is sufficient; Anaconda is a larger application. Either is fine,
 but Miniconda is mini.

 With conda installed, run the following lines in the terminal:
```
conda env create -f sat-cty-conda-env.yml
conda activate sat-city
pip install -r requirements.txt
```

Note: you can actually combine the `pip` installs with the conda environment yml, but for now
I'm keeping them separate for simpler development.
