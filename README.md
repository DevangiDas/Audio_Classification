
Audio Classifier

This project is an audio classifier specifically designed to identify and classify Capuchin bird calls. The classifier utilizes machine learning techniques and audio signal processing to automatically recognize different bird call patterns.

Objective

The goal of this project is to recognize and classify Capuchin bird calls in a given audio dataset. The classifier is trained on two classes: Capuchin bird call and not Capuchin bird call.

Dataset

The dataset used for training and evaluating the classifier consists of a collection of labeled audio recordings. The dataset hierarchy is as follows:

data folder:

Forest Recordings (100 files): These are the recordings used to count the number of calls within. Each clip is 3 minutes long and includes a mix of Capuchin bird calls and other sounds.

Parsed_Capuchinbird_Clips (217 files): These are parsed clips that include specific bird calls from Capuchin birds.

Parsed_Not_Capuchinbird_Clips (593 files): These files are parsed sounds from other animals/birds that are useful in training the classifier to recognize what is not a Capuchin bird.
The training data is split into 70% for training and 30% for testing.

Installation and Setup

To run this project on your local machine, follow these steps:

Clone the repository:

Copy code
git clone https://github.com/DevangiDas/Audio_classification

Navigate to the project directory:
Copy code
cd Audio_classification

Modify the code to suit your local setup:

Open the   Audio_classification.ipynb   file in Jupyter Notebook or your preferred Python development environment.

Adjust the file paths in the code to match the location of the audio dataset on your computer.

Customize any other parameters or settings as needed.

Install the required dependencies:
 
Run the notebook:

Execute the cells in the Audio_classification.ipynb notebook to train the classifier and generate predictions.
The notebook contains instructions and comments to guide you through the process.

Output

After running the project, a results.csv file will be generated in the project directory. This file contains the number of Capuchin bird calls detected in each forest recording of the dataset.

Evaluation and Metrics

The classifier's performance can be assessed by examining the following metrics and visualizations:

Precision, Recall, and Loss: The notebook includes line graphs depicting the precision, recall, and loss of the classifier during training and evaluation. These graphs provide insights into the model's performance.

Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.


Acknowledgments

Thanks to Kaggle for providing the Capuchin bird call dataset used in this project.
Special thanks to the open-source community for their invaluable contributions to the field of machine learning and audio signal processing.