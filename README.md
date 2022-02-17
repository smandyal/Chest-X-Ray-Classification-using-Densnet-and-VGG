# **README**

The chest xray classification project has two portions to it :

* VGG16 model - major analysis and fine tuning
* DensetNet121 model - for comparsion of performances etc 

There are two requirements.txt files which need to installed in order to run the code on local machine, respectively.

*Steps to install the requirements. :* 
requirements.txt is for the vgg model
requirements-2.txt is for the densenet model


**Conda interpreter**

`conda install --file requirements.txt`
`conda install --file requirements-2.txt`


or 

**Local python interpreter**

`pip install -r requirements.txt`


## Dataset

NIH chest x-ray dataset 
<br>
 `https://drive.google.com/drive/folders/1r2qOTU_7W5JoGdZux7vtthfIMrXH1YYm?usp=sharing`


## Code files
The following are the python notebooks and model save points which can run locally or on VM with VS code or Jupyter notebook.
<br>

* `DeepLProject2_0_vgg_model.ipynb`
* `chest_x_ray_disease_classification_densenet121.ipynb`
* `https://drive.google.com/file/d/1h1O9tbt2cTO6V43zDuAvLYa62p5JaXXN/view?usp=sharing`  Save point of VGG model  

## Softwares install steps 
If needed the following are steps to install jupyter. 

* To install jupyter notebook `https://www.mygreatlearning.com/blog/how-to-install-jupyter-notebook/`
* Use jupyer from google ( colab ) `https://colab.research.google.com/?utm_source=scs-index`



## Running the code:
Both codes must be ran.
<br>

0. Install all requirements from the requirements.txt and requirements-2.txt files above
1. To run the code, upload the .ipynb files onto google colab 
2. Upload the dataset (link provided under Datasets above) to google drive  
3. change the path of the dataset in the .ipynb files to where you stored it on your google drive
4. Click run and wait for some time (It may take hours)