# two-towers-with-tensorflow-recommenders-lp-author
Repository for liveProject: Two Towers with TensorFlow Recommenders

## What's in here:
This repository containg all the files required for you to begin this liveProject.

**Data:** the `data` directory contains the following files:
* `metadata.json`
* `test_data.zip`
* `train_data.z*`, where `*` are numbers 0-9

**Link to download data file: https://lp-prod-resources.s3.us-west-2.amazonaws.com/866/train_data.zip**

**Preparing the data:** 

_Note: if you have successfully completed the previous project, you do not need the data in this repository - use the data you created throughout the project._

1. Unzip `test_data.csv` from `test_data.zip`
2. Next, you'll need to concatenate all training data files. Open the terminal and go to the directory where you saved the `train_data.z*` files (run: `cd {your_directory}`)
3. Run: `cat train_data.z* > train_data.zip`. The `train_data.zip` file will now appear in that directory
4. Unzip `train_data.csv` from `train_data.zip`

## Requirements:
Programming languages and libraries update quite often, and different versions have different behaviors, APIs and bugs. In order to make sure we're all on the same page, I highly recommended to use the exact libraries and versions I've used. My best recommendation is to set up a new [virtual environment](https://docs.python.org/3/tutorial/venv.html) with the same Python version I used while creating this project: 
```
Python 3.9.6
```
You can use the `requirements.txt` file in the project's GitHub repo for easier installation of the required libraries using `pip`:
```bash
pip install -r requirements.txt
```
The `requirements.txt` file is identical to all projects of this series, so once you've set up your environment, you're good to go for the rest of the series. 
