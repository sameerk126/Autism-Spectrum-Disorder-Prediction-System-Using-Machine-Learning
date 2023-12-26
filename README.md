# Child Autism Spectrum Disorder Prediction System

This project implements a machine learning model to predict autism based on diagnostic features. It includes a Flask web application for local deployment and testing.

## Overview

- `autism_model.py` - Trains a random forest classifier on the Autism Screening Adult dataset from UCI ML Repository. Saves the model as a pickle file.

- `app.py` - Flask application that loads the saved model and provides a web interface to get real-time predictions.

- `templates/` - Contains HTML templates for the web interface.

- `static/` - Contains CSS stylesheet for styling the web templates.

- `requirements.txt` - Python package dependencies for the project.

## Usage

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Flask App

```bash
python app.py
```

The app will be served at `http://localhost:5000`

The homepage displays the prediction form. Enter values for the diagnostic questionnaire and submit to view the autism prediction results.

## Model Training

The random forest model is already trained and saved in `autism_prediction.pkl`

To re-train the model with updated data or different parameters, run:

```bash
python autism_model.py
```

## Contributing

Contributions to improve the web interface, model training code or accuracy are welcome!

Let me know if you have any other questions! I'm happy to clarify or provide more details about the project.

#Snapshots![index](https://github.com/sameerk126/Autism-Spectrum-Disorder-Prediction-System-Using-Machine-Learning/assets/81867462/059fe26f-416e-4577-b557-c8728e4a0256)


