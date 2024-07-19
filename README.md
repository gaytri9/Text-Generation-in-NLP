# Text-Generation-in-NLP
## Overview
This project explores the use of Natural Language Processing (NLP) for generating sports-related text. The goal is to create a model capable of generating coherent and contextually relevant sports commentary, news articles, or match summaries.

## Dataset
The dataset used for this project comprises sports articles, commentary transcripts, and match summaries. The data is stored in a **'.zip'** file named **'sports_data.zip'**.

## Source
The dataset is sourced from various publicly available sports news websites and commentary archives.

## Installation
To set up the project, follow these steps:

1. Clone the repository:
```
git clone https://github.com/gaytri9/text-generation.git
```
2. Navigate to the project directory:
```
cd sports-text-generation
```
3. Create a virtual environment:
```
python -m venv venv
```
4. Activate the virtual environment:
   4.1 On Windows:
    ```   
    venv\Scripts\activate
    ```
   4.2 On macOS and Linux:
     ```
     source venv/bin/activate
     ```
5. Install the required packages:
```
pip install -r requirements.txt
```

## Usage
To run the text generation model, follow these steps:

1. Preprocess the dataset:
```
python preprocess.py
```
2. Train the model:
```
python train.py
```

## Directory Structure
```
sports-text-generation/
│
├── data/
│   └── sports_data/
│
├── output/
│   └── generated_texts/
│
├── src/
│   ├── preprocess.py
│   ├── train.py
│   └── generate.py
│
├── models/
│   └── text_generator.h5
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Files
**1. `preprocess.py`**: Preprocesses the dataset for training.
**2. `train.py`**: Trains the text generation model.
**3. `generate.py`**: Generates sports-related text based on input seed text.
**4. `text_generator.h5`**: The trained model.

## Model Architecture
The model architecture is based on a Recurrent Neural Network (RNN) with Long Short-Term Memory (LSTM) units, which are effective for sequential data and text generation tasks.
