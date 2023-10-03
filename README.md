# Euro Coin Value Classifier

This repository contains the implementation and documentation of a Euro coin value classifier developed for a computer vision university course project in 2022. The project aims to accurately classify Euro coins into their respective denominations.

## Project Structure

- **data/:** Contains the training and test images used in the project.
  - `train/`: Training images for model development and fine-tuning.
  - `public_test/`: Test images for evaluating the model's performance.
  - `euro-coin-dataset`: Images taken from [euro-coin-dataset](https://github.com/SuperDiodo/euro-coin-dataset) to improve the accuracy of the models

- **models/:** Contains the best-performing model weights.
  - [DenseNet121.hdf5](models/DenseNet121.hdf5)
  - [DenseNet169.hdf5](models/DenseNet169.hdf5)
  - [VGG16.hdf5](models/VGG16.hdf5)

- **notebooks/:** This directory is dedicated to Jupyter Notebooks for specific tasks.
  - [dataPreprocessing.ipynb](notebooks/dataPreprocessing.ipynb): Notebook for preprocessing the dataset.
  - [gimnasio.ipynb](notebooks/gimnasio.ipynb): Notebook for training models.
  - [ensemble.ipynb](notebooks/ensemble.ipynb): Notebook for combining model predictions.

- **results/:** Holds the output files, such as [predictions.csv](results/predictions.csv).

- **docs/:** Contains documentation files, including essays and benchmarks.
  - [Clasificación de monedas.pdf](docs/Clasificación%20de%20monedas.pdf): An essay explaining the project.
  - [Benchmarks.pdf](docs/Benchmarks.pdf): Benchmark of the models trained.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/itogaston/CoinClassifier.git
   cd CoinClassifier
   ```

2. Set up your Python environment with the required dependencies.

3. Follow the Jupyter Notebooks (`dataPreprocessing.ipynb`, `gimnasio.ipynb`, `ensemble.ipynb`) to preprocess data, train models, and make predictions.

4. Explore the `models/` directory to access pre-trained model weights.

## Contributions

Contributions and improvements to this project are welcome. If you'd like to enhance the classifier's accuracy or functionality, please fork this repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

I would like to express my sincere appreciation to [Iris Dominguez Catena](https://www.unavarra.es/pdi?uid=811899), a dedicated and knowledgeable professor who provided invaluable guidance and mentorship throughout the development of this project. Her expertise in computer vision and deep learning played a crucial role in shaping the project's success.
