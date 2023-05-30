# Project .
A plant nutrient deficiency classification system which can detect whether a rice plant is healthy or has any of N, P or K deficiency when provided with an image of a rice leaf. Deployed webapp ([link](https://harnpredict.streamlit.app/)).

# <a name="toc">Table of Contents</a>
1. [Introduction](#intro)
2. [Dataset](#ds)
3. [Technologies Used](#tech)
4. [Installation Guide](#install)
5. [Screenshots](#ss)

# 1. <a name="intro">Introduction</a>
###### [Back to Table of Contents](#toc)
There are various methods for identifying nutrient deficiency in plants such as rapid testing & plant analysis. Also, the existing Hydroponic systems usually have automated system which is just relying on the external paraments of the plant such as temperature, humidity, etc.. Plants require nutrients to germinate, grow, fight off diseases and pests and to reproduce. A plant that lacks an essential nutrient cannot complete its life cycle. However, having too much of a nutrient can harm and even kill plants. This is why, the purpose of this project is to provide a better and fast solution for identifying plant nutrient deficiency using Image Processing techniques and Convolutional Neural Networks (CNN). This project is made to identify nutrient deficiency in rice and spinach plants. The nutrients that will be identified by this project are Macronutrients viz (Nitrogen (N), Potassium (K), and Phosphorous (P)). Various CNN models was tested and the model with the best fit is deployed using StreamLit as a webapp [here.](https://harnpredict.streamlit.app/)

The paper referred provides a detailed process: [Using Deep Convolutional Neural Networks for Image-Based Diagnosis of Nutrient Deficiencies in Rice](https://www.hindawi.com/journals/cin/2020/7307252/) by Zhe Xu, Xi Guo, Anfan Zhu, Xiaolin He, Xiaomin Zhao, Yi Han and Roshan Subedi.

# 2. <a name="ds">Dataset</a>
###### [Back to Table of Contents](#toc)
Dataset is labeled and available here: [Google Drive](https://drive.google.com/file/d/1d1DFN_gHxaQcO8xSfyHK5ktuPVUj0Q3G/view?usp=sharing)

# 3. <a name="tech">Technologies Used</a>
###### [Back to Table of Contents](#toc)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white) ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) 
# 4. <a name="install">Installation Guide</a>
###### [Back to Table of Contents](#toc)
- Create a folder in your local machine.
- Create a virtual environment.
```
pip install virtualenv
```
Open Git Bash and navigate to your project folder OR open project folder, right click and then click 'Get Bash Here'
```
python -m virtualenv {whatever_virtual_env_name_you_want_to_give}
```
- Activate the virtual environment.
```
source {whatever_virtual_env_name_you_want_to_give}/scripts/activate
```
pip install -r requirements.txt
```

# 5. <a name="ss">Screenshorts</a>
###### [Back to Table of Contents](#toc)

### 5.1. Home page
![ss1](https://drive.google.com/file/d/1d9xgBG1Y9cjDxXQ5Si5fmQn68PJOt7FG/view?usp=sharing)

### 5.2. K Deficiency detection
![ss2](https://drive.google.com/file/d/1cWOhqILEnPal_jj50HF3-zCExcz2gHWG/view?usp=sharing)

### 5.3. N Deficiency detection
![ss3](https://drive.google.com/file/d/1QAAAzFlj1TUJ8E9n36GtfjNQ-EEBzdC9/view?usp=sharing)

### 5.4. P Deficiency detection
![ss4](https://drive.google.com/file/d/1AvfdW_Cl9Cr0YEL4zMtPjhNp_C4KTnP0/view?usp=sharing)

### 5.5. Healthy Rice leaf detection
![ss5](https://drive.google.com/file/d/1gQ-uAUD-qReIDSiS34OKb3gHtJbh67sk/view?usp=sharing)
