# Crop Disease Prediction System

A machine learning application designed to classify potential crop diseases from plant leaf images.

## Overview

The Crop Disease Prediction System processes uploaded leaf images using an image classification model and presents the predicted class with an appropriate confidence score.

The application aims to support agricultural learning and preliminary crop health assessment.

## Key Features

- Plant leaf image upload
- Image preprocessing
- Crop disease classification
- Prediction confidence display
- Supported crop and disease categories
- Prediction history, if configured
- Image validation and error handling
- Educational crop health information

## Technology Stack

- Python
- TensorFlow or PyTorch
- OpenCV
- NumPy
- Pillow
- Streamlit

## Project Structure

```text
Crop-Disease-Prediction-System/
├── app.py
├── requirements.txt
├── README.md
├── src/
│   ├── image_preprocessing.py
│   ├── model_loader.py
│   └── predict_disease.py
├── models/
├── data/
│   └── README.md
└── tests/
```

## Installation

```bash
git clone https://github.com/amoltathesoftwareengineer/Crop-Disease-Prediction-System.git
cd Crop-Disease-Prediction-System
python -m venv .venv
```

Activate on Windows:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Run the Application

```bash
streamlit run app.py
```

A compatible trained model must be configured before predictions can run.

## Prediction Workflow

1. Upload a supported plant leaf image.
2. Validate and preprocess the image.
3. Run the trained classification model.
4. Display the predicted category and model confidence.
5. Present relevant educational information.

## Limitations

- Prediction quality depends on the training dataset.
- Lighting, image quality, and unseen diseases can affect results.
- Confidence scores are not guarantees of correctness.
- Results should not replace expert agricultural diagnosis.

## Future Enhancements

- Support for additional crops
- Multilingual interface
- Disease severity estimation
- Explainable image classification
- Offline inference
- Agricultural expert review workflow

## Author

Amol Tathe

GitHub: https://github.com/amoltathesoftwareengineer

## License

Add an appropriate open-source license before permitting reuse.
