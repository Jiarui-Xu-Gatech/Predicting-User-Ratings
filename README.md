# Project Group 06 S22

More details of the model is in Report06_S22.pdf

- Instruction to run the code
  - `cd` into the `code` folder.
  - The dataset is in the `ml-1m` folder. 
    - Move `user.dat`, `movies.dat`,`ratings.dat` to the same folder as the `project_code_06.ipynb` file.
  - The trained models are in the `models` folder.
    - Move the files `trained_lstm_10_epochs.pth` and `trained_trans_10_epochs.pth` in the models folder to the same folder as the `project_code_06.ipynb` file.
  - All the project codes are in the `project_code_06.ipynb` file, including code to load and convert the data, preparing data loader for the training process, model definition, and training loops.
  - After placing all the `.dat` files and model files in the right place, just run through all the cells in the Jupyter notebook and the code should output the evaluation result for the trained models.
  - Recommend running the project in an environment with a CUDA GPU, such as Google Colab, as we ran the code on Colab.

