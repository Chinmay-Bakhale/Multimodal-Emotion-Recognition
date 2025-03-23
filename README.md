# Multimodal Emotion Recognition

This project aims to classify human emotions using a multimodal approach, combining audio and video features. It utilizes the RAVDESS dataset and leverages PyTorch for model development.

## Project Structure

- **data**: Contains the RAVDESS dataset.
- **notebooks**: Includes the main notebook (`multimodal_emotion_recognition.ipynb`) for data exploration, model training, and evaluation.
- **src**: Not applicable for this project; all code is in the notebook.

## Key Features

- **Multimodal Fusion**: Combines audio and video features using an attention-based mechanism.
- **Model Architecture**: PyTorch-based neural network with separate encoders for audio and video.
- **Dataset**: RAVDESS dataset for speech emotion recognition.

## Usage

1. Clone the repository.
2. Install necessary libraries by running `!pip install librosa opencv-python scikit-learn matplotlib pandas tqdm torch torchvision torchaudio` in a cell.
3. Run the notebook (`multimodal_emotion_recognition.ipynb`) to explore the dataset, train the model, and evaluate its performance.

## Results

The project achieves emotion classification using a multimodal approach, providing insights into how audio and video modalities contribute to emotion recognition.

## Acknowledgements

- RAVDESS dataset: [https://zenodo.org/record/1188976](https://zenodo.org/record/1188976)
- PyTorch: [https://pytorch.org/](https://pytorch.org/)
