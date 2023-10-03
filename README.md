# Euro Coin Value Classifier

This repository contains the implementation and documentation of a Euro coin value classifier developed for a computer vision university course project in 2022. The project aims to accurately classify Euro coins into their respective denominations, including 1 Euro, 2 Euros, 50 Cents, 20 Cents, 10 Cents...

## Project Structure

- [Clasificación de monedas.pdf](Clasificación%20de%20monedas.pdf): An essay explaining the project's processes and results.
- [Benchmarks.pdf](Benchmarks.pdf): Benchmark results of some models considered for the project.
- [dataPreprocessing.ipynb](dataPreprocessing.ipynb): Jupyter Notebook for preprocessing the dataset, including provided images and additional images collected from a GitHub repository.
- [gimnasio.ipynb](gimnasio.ipynb): Jupyter Notebook for training models using transfer learning and other techniques.
- [ensemble.ipynb](ensemble.ipynb): Jupyter Notebook for combining model predictions and making predictions on the test image group.
- [models/](models/): Folder containing the three best-performing models.
  - [DenseNet121.hdf5](models/DenseNet121.hdf5)
  - [DenseNet169.hdf5](models/DenseNet169.hdf5)
  - [VGG16.hdf5](models/VGG16.hdf5)
- [predictions.csv](predictions.csv): CSV file containing the predictions made with `ensemble.ipynb`.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/coin-value-classifier.git
   cd coin-value-classifier
   ```

2. Set up your Python environment with the required dependencies, including a deep learning framework like TensorFlow or PyTorch.

3. Follow the Jupyter Notebooks (`dataPreprocessing.ipynb`, `gimnasio.ipynb`, `ensemble.ipynb`) to preprocess data, train models, and make predictions.

4. Explore the `models/` directory to access pre-trained model weights.

## Contributions

Contributions and improvements to this project are welcome. If you'd like to enhance the classifier's accuracy or functionality, please fork this repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

## Acknowledgments

I would like to express my sincere appreciation to [Iris Dominguez Catena](https://www.unavarra.es/pdi?uid=811899), a dedicated and knowledgeable professor who provided invaluable guidance and mentorship throughout the development of this project. Her expertise in computer vision and deep learning played a crucial role in shaping the project's success.
