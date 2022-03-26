# 3 Tactics to Improve your Cluster Analysis

## User setup

1. Create a Python virtual environment.
   These contents were developed using Python version 3.9.4.

1. Install the required dependencies with

   ```sh
   pip install -r user-requirements.txt
   ```

1. Set up `git-lfs`: follow [these instructions](https://git-lfs.github.com/)
   up to `git lfs install` included.

1. The Jupyter notebook and all associated data can be found in the
   `project` repository. You can start the Jupyter server with

   ```sh
   jupyter notebook project/
   ```

## Developer setup

1. Follow the User setup, but in step 2 run

   ```sh
   pip install -r dev-requirements.txt
   ```

   instead.

1. Install the pre-commit hooks with

   ```sh
   pre-commit install
   ```

1. Save any notebooks in `project/notebooks` and any data in `project/data`.
