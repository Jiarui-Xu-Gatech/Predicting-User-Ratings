# Could Transformer Outperform Long Short-Term Memory Model in Predicting User Ratings?

The project aims to find out whether the recently popular attentionbased model of Transformer  could perform better than previous baseline proposed in the work by He et al. We will compare the performance of transformer model using similar input setup to the work of Behavior Sequence Transformer [1] to a baseline Long Short-Term Memory model using the same input setup. We measure the performance of the two models on the dataset MovieLens that contains 3,900 movies, 6,040 users, and 1,000,209 ratings, and each user has rated at least 20 movies, with integer scores ranging from 1 to 5. MovieLens is widely used to test and develop recommendation algorithms, especially collaborative filtering algorithms. The two models are trained and validated on the task of predicting user ratings based on sequences of feature inputs. The Long Short-Term memory model achieves an average root mean
square error of approximately 1.3547 on validation data, and the transformer model achieves an average root mean square error of approximately 1.2122 on validation data.

More details of the model is in Report06_S22.pdf

# Instruction to run the code
  - `cd` into the `code` folder.
  - The dataset is in the `ml-1m` folder. 
    - Move `user.dat`, `movies.dat`,`ratings.dat` to the same folder as the `project_code_06.ipynb` file.
  - The trained models are in the `models` folder.
    - Move the files `trained_lstm_10_epochs.pth` and `trained_trans_10_epochs.pth` in the models folder to the same folder as the `project_code_06.ipynb` file.
  - All the project codes are in the `project_code_06.ipynb` file, including code to load and convert the data, preparing data loader for the training process, model definition, and training loops.
  - After placing all the `.dat` files and model files in the right place, just run through all the cells in the Jupyter notebook and the code should output the evaluation result for the trained models.
  - Recommend running the project in an environment with a CUDA GPU, such as Google Colab, as we ran the code on Colab.

