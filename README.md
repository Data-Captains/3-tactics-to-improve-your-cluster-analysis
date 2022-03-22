# INSERT_YOUR_PROJECT_NAME_HERE

## User setup

1. Create a Python virtual environment.
   We recommend using Python version INSERT_VERSION_HERE.

1. Install the required dependencies with

   ```sh
   pip install -r user-requirements.txt
   ```

1. Set up `git-lfs`: follow [these instructions](https://git-lfs.github.com/)
   up to `git lfs install` included.

   REMOVE THIS STEP IF YOUR PROJECT DOES NOT REQUIRE GIT-LFS.

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

## INSERT_ADDITIONAL_SECTIONS_HERE

TBA
