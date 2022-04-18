## Setup and Installation
The application has been written, compiled and tested using Python 3.6 and will work on all Python 3+ versions. In order to get started with running the application, please follow the steps given below:
1. Download the code and go to the downloaded code directory
`cd <>`
2. Install Python3 and pip if you don't have Python3 or pip installed on your system.
    - Download the latest Python from [https://www.python.org/downloads/](https://www.python.org/downloads/)
    - Install pip using the following command: 
    Download the script from [https://bootstrap.pypa.io/get-pip.py](https://bootstrap.pypa.io/get-pip.py).
    `$ python get-pip.py`
3.  Install all the dependencies required for the application
`$ pip install -r requirements.txt`
4. Run the files - `splash_dataset_creator.py` and `parsec_dataset_creator.py` following individual instructions for setting up the SPLASH and PARSEC benchmarks respectively. (mentioned in both the .py files)
5. Once the dataset is ready, run the threadwise_performance_prediction.ipynb and allthreads_onemodel_performance_prediction.ipynb files to get the results of all models. (You can use Google Colab to run .ipynb files for easy setup)

We have included the data we collected from PARSEC and SPLASH in the `dataset` folder.