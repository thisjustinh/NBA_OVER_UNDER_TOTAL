# NBA Head-To-Head Simulation

Simulate the results of different teams in head-to-head situations: how many points each would get, and who would win!

Model training artifacts and code can be found in the `model_training` folder.

## DESCRIPTION

Models and simulates the head-to-head team performance, predicting the home team score, away team score, and 

## INSTALLATION

For recreating model training, within the `model_training` folder there is a `uv.lock` file and `pyproject.toml` to help recreate the environment. You can run `uv sync` and it will recreate the entire virtual environment required. Alternatively, the `requirements.txt` traditional file can also be used for installing libraries in bulk.

## EXECUTION

Opening and executing all cells in `nba_model_training_v3.ipynb` will recreate the data collection, feature engineering, feature selection, model training, and hyperparameter tuning, assuming that the kernel uses the virtual environment set up above. However, all the best-performing models and data files have also already been saved under this folder.