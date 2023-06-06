# ASL Fingerspelling Translation

This repository contains notebooks and resources for the ASL Fingerspelling Translation competition. The goal of this competition is to detect and translate American Sign Language (ASL) fingerspelling into text. 

## Notebooks

### asl-dataprocessing.ipynb

This notebook provides code and instructions for preprocessing the ASL fingerspelling dataset. It covers data cleaning, normalization techniques to enhance the quality. The processed data will be used for training models in subsequent notebooks.

### character_to_prediction_index.json

This JSON file contains a mapping from individual fingerspelled characters to their corresponding prediction indices. This mapping is necessary for translating the predicted indices back into the respective characters during the translation phase.

### exploring-asl-data.ipynb

This notebook offers an in-depth exploration of the ASL fingerspelling dataset. It provides insights into the data distribution, visualizations of the fingerspelled characters, and statistical analysis. This exploration will help you gain a better understanding of the dataset and potentially identify patterns or challenges that can inform their model development.

### first model: model.ipynb

In this notebook, the initial model for ASL fingerspelling translation is developed. It covers the architecture design, training process, and evaluation of the model. Participants can refer to this notebook as a starting point to build their own models or as a baseline for comparison.

## Getting Started

To get started with the ASL Fingerspelling Translation competition, follow the steps below:

1. Clone this repository to your local machine using `git clone https://github.com/your-username/ASL-Fingerspelling-Translation.git`
2. Install the required basic dependencies and libraries specified in the `requirements.txt` file.
3. Open and run the notebooks in the specified order to preprocess the data, explore the dataset, and develop your models.
4. Refer to the documentation and comments within the notebooks for detailed instructions and explanations.
5. Feel free to experiment, iterate, and improve upon the existing models and techniques. Collaboration and sharing of insights are encouraged.

## Contributions

Contributions to this repository are welcome. If you discover any issues, have suggestions for improvements, or want to share your own model implementations, feel free to submit a pull request. Let's collaborate and make progress together in advancing ASL fingerspelling translation!

## License

This repository is licensed under the [MIT License](LICENSE). Please review the license file for more details.
