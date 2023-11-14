# Rumour Detection Model using PyTorch and ConfliBERT

This repository contains code for a rumour detection model built using PyTorch and the ConfliBERT pre-trained language model.

## Requirements

To run this model, you will need:

- A Google account
- A web browser
- A stable internet connection
- An understanding of Python programming

## Getting started

To get started, follow these steps:

1. Clone this repository to your local machine using Git or download it as a ZIP file and extract it.

2. Open a web browser and navigate to Google Colab (https://colab.research.google.com/).

3. Sign in with your Google account.

4. In the Google Colab dashboard, click on "File" and select "Upload notebook".

5. Upload the "FakeNewsDetectionModelTwitter15DatasetConfliBERTSVMLRFinal.ipynb" OR FakeNewsDetectionModelTwitter16DatasetConfliBERTSVMLRFinal.ipynb file from this repository.

6. Open the "FakeNewsDetectionModelTwitter15DatasetConfliBERTSVMLRFinal.ipynb" notebook and follow the instructions to run the fake news detection model.

## Usage

To use the fake news detection model, you will need to connect to a runtime on Google Colab and make sure that the type of runtime is GPU:

Then you must copy either dataset from the GitLab repository (either Twitter15Dataset or Twitter16Dataset) onto the files tab on Google Colab

Once you have your dataset, run the notebook to preprocess your data, train and evaluate the model, and make predictions on new data.

## Citations

@inproceedings{hu2022conflibert,
  title={ConfliBERT: A Pre-trained Language Model for Political Conflict and Violence},
  author={Hu, Yibo and Hosseini, MohammadSaleh and Parolin, Erick Skorupa and Osorio, Javier and Khan, Latifur and Brandt, Patrick and D’Orazio, Vito},
  booktitle={Proceedings of the 2022 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies},
  pages={5469--5482},
  year={2022}
}

