# Covid Chest Xray Classification
* The main goal of this project is to classify Chest X-ray Images of patients for COVID-Positive and Negative as correctly as possible.
* Built a Convolution Neural Network using Pytorch to predict the condition of the patients (COVID Positive or Negative).
* I have used the dataset from the IEEE Github Repository of Covid Chest Xray Dataset.The link to the dataset is given [here](https://github.com/ieee8023/covid-chestxray-dataset).

## Requirements
* If you don't have python installed on your machine download it from [here](https://www.python.org/ftp/python/3.8.2/python-3.8.2.exe)
* Then install pip on your machine by downloading this [get-pip.py](https://bootstrap.pypa.io/get-pip.py) and from the downloads directory and  run ```python get-pip.py```
* To start working on the project run the following command after cloning the repository.
```
pip install -r requirements.txt
```
* I suppose Anaconda is already installed in the machine. Then run the following command
```
conda install pytorch torchvision -c pytorch
```
This would install all the requirements.
## Output
* The dataset contains majority of images of Chest X-rays of patients
* If we train the data as it is, our model will be biased.
* So,Did preprocessing of the dataset.
* Trained the model with Preprocessed Data.
* Here is a snapshot of the output
![Output Image](https://github.com/saisrirammortha/Covid-Chest-Xray-Classification/blob/master/output.png)
* For detailed report See [Report](https://github.com/saisrirammortha/Covid-Chest-Xray-Classification/blob/master/project_final.pdf) in the repository.
