# Handwritten Digit Classification

This project is focused on classifying handwritten digits using datasets from USPS and MNIST. The goal is to preprocess the data to achieve uniform dimensions and then use machine learning models to accurately classify the images.

## Requirements

- Python 3.11.9
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- TensorFlow
- Scikit-learn
- Other packages included in `requirements.txt`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/handwritten-digit-classification.git
   cd handwritten-digit-classification
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open and run the `HandwrittenDigitClassification.ipynb` notebook to execute the preprocessing and classification steps.

## Project Structure

- `HandwrittenDigitClassification.ipynb`: Main notebook for data processing and model training.
- `requirements.txt`: List of Python packages required for the project.
- `data/`: Directory containing the USPS and MNIST datasets.
- `models/`: Directory to save trained models.

## Datasets

- **USPS Dataset**: Contains images of handwritten digits used in postal code processing.
- **MNIST Dataset**: Widely used dataset of handwritten digits.

## Preprocessing

The USPS images are padded to match the MNIST image size to ensure compatibility with machine learning models. This is achieved by calculating the necessary padding and using the `np.pad` function to apply it.

## Results

Once preprocessing is complete, various machine learning models can be trained and evaluated for accuracy in classifying the handwritten digits.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License.
