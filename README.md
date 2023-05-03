
### **Dataset**

---

[**The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions**](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T)

---

<!-- ## Files Tables

| Sr.No | File Name                                                    | Link                                                         |
| ----- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1     | Exploratory data analysis                                    | [**Notebook**](http://nbviewer.ipython.org/urls/raw.github.com/ashishpatel26/Skin-Lesions-Detection-Deep-learning/main/Notebooks/Skin_Cancer_EDA.ipynb) |
| 2     | Baseline model                                               | [**Notebook**](http://nbviewer.ipython.org/urls/raw.github.com/ashishpatel26/Skin-Lesions-Detection-Deep-learning/main/Notebooks/Baseline_CNN.ipynb) |
| 3     | VGG16            | [**Notebook**](http://nbviewer.ipython.org/urls/raw.github.com/ashishpatel26/Skin-Lesions-Detection-Deep-learning/main/Notebooks/Fine_Tuning_VGG16.ipynb) |
| 4    |  Inception V3 on ImageNet | [**Notebook**](https://nbviewer.jupyter.org/github/ashishpatel26/Skin-Lesions-Detection-Deep-learning/blob/main/Notebooks/Retraining_InceptionV3.ipynb) |
| 5     | DenseNet 201 on ImageNet | [**Notebook**](https://nbviewer.jupyter.org/github/ashishpatel26/Skin-Lesions-Detection-Deep-learning/blob/main/Notebooks/Retraining_DenseNet.ipynb) |
| 6     | Ensemble model of the fully fine-tuned Inception V3 and DenseNet 201 | **[Notebook](https://nbviewer.jupyter.org/github/ashishpatel26/Skin-Lesions-Detection-Deep-learning/blob/main/Notebooks/Ensemble_Models.ipynb)** |

 -->



## Results

| Models        | Validation           | Test            |  Depth          | # Params          |
| ------------- |:-------------:| :-------------:| :-------------:| :-------------:|
|  Baseline   | 77.48% |76.54% | 11 layers | 2,124,839 |
|  VGG16    |  79.82%      |   79.64%  | 23 layers | 14,980,935 |
|  Inception V3  | 86.92% | 86.826% | _ | _ |
|  DenseNet 201   | **86.696%** | **87.725%** | _ | _ |
|  Ensemble of fully-fine-tuned Inception V3 and DenseNet 201 | **88.8%** | **88.52%** | _ | _ |


## The Dataset

[The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T,)
