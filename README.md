# DeepRacer-Analyzer

This repository provides tooling for the analysis of AWS DeepRacer training experiments. It enables users to visualise and evaluate the performance of their reinforcement learning models trained using the AWS DeepRacer service.

## Features

- Visualise training metrics and performance statistics.
- Evaluate and compare different DeepRacer training experiments.
- Gain insights into the learning progress and performance of reinforcement learning models.

## Prerequisites

To use the DeepRacer-Analyzer, you will need the following:

1. An AWS account.
2. Python 3 installed.
3. Jupyter notebook installed.

## Getting started

1. Clone or download this repository to your local machine.
2. Install the required Python dependencies using **pip**.
```
pip install --upgrade deepracer-utils>=0.9
```
3. Launch the jupyter notebook.

## Usage

Follow these steps to use the DeepRacer-Analyzer:

1. Download the DeepRacer log files from the AWS Management Console for the experiments you want to analyze. These log files contain important training data.

2. Extract the downloaded log files and place them in the "logs" directory within the DeepRacer-Analyzer repository.

3. Open the Jupyter Notebook and navigate to the section where the "model_logs_root" variable is defined. Update the variable to point to the root directory of the newly added log files. This ensures that the notebook can locate and analyse the log files correctly.

4. Update track_name variable. If you are using a different track than the default "ReInvent:2018" track, navigate to the section where the "track_name" variable is defined. Update the variable with the name of the track you are using. This allows the notebook to correctly evaluate and compare the performance of your models on the specific track.

5. Run all the cells in the Jupyter Notebook. This will execute the provided tools and visualisations, allowing you to analyse the training metrics and evaluate the performance of your DeepRacer models.

## Resources

Here are some additional resources related to AWS DeepRacer:

* [AWS DeepRacer Information](https://aws.amazon.com/deepracer/)
* [AWS DeepRacer GitHub Repository](https://github.com/aws-deepracer-community/deepracer-analysis)
* [AWS DeepRacer Documentation](https://docs.aws.amazon.com/deepracer/latest/developerguide/what-is-deepracer.html)
* [deepracer-utils](https://pypi.org/project/deepracer-utils/)
* [Jupyter Notebook Documentation](https://jupyter-notebook.readthedocs.io/en/stable/)






