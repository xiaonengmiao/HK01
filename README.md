# Answers to WeMedia01 (HK) Limited Offsite Test for University Recruitment 2018

> I Choosed Q3 Data Analysis, Visualization & Data Science. All the answers and code are in the file "DataAnalysisVisualizationDataScience.ipynb". To open it, run `jupyter notebook` from the working directory. If you are not familiar with it, please refer to **Setup** and **Virtual environment** below.

## Setup

You can open **DataAnalysisVisualizationDataScience.ipynb** with IPython notebook from the current directory, with the `jupyter notebook` command. If you have problems running the code, you may consider the correctness of all dependencies for the code. Please refer below **Virtual environment**.

## Virtual environment

I recommend using [virtual environment](https://conda.io/docs/user-guide/tasks/manage-environments.html) for the project. If you choose not to use a virtual environment, it is up to you to make sure that all dependencies for the code are installed globally on your machine. To set up a virtual environment, run the following(make sure you have `conda installed`):

```bash
cd assignment(working directory)
conda create --name myenv         # Create a virtual environment
source activate myenv             # Activate the virtual environment
conda install --name myenv --file myenv.txt  # Use myenv.txt to install listed packages 
conda install jupyter             # Install jupyter

# Working on the assignment for a while
# ... and when you are done:

source deactivate                 # Exit the virtual environment
```

Note that every time you want to work on the assignment, you should run `source activate myenv` (from within your assignment folder) to re-activate the virtual environment, and `source deactivate` again whenever you are done.


