# Data_X_2023

This repository was created for our project within the course Data-X – Applied Data Analytics Models in Real World Tasks (4IT439). This project is conducted using Python language. 

**Authors:**_ [**Veronika Vacková**](https://www.linkedin.com/in/veronika-vera-vackova/), [**Barbora Dobrovolná**](https://www.linkedin.com/in/dobrovolnab/), [**Simona Dohová**](https://www.linkedin.com/in/simona-dohov%C3%A1-182427153/), [**Karolína Krutinová**](https://www.linkedin.com/in/karol%C3%ADna-krutinov%C3%A1/)

The goal of this project is to evaluate penguin species using machine learning methods.
In this project, the Penguin dataset is used: The new Iris, which will be used to create a model that will predict what species the penguin is classified as. 

## How to Install and Run the Project
### Virtual environment
At first, create a new enviroment using version Python  `Python 3.9.13`

```bash
conda create -n yourenv python=3.9.13
```
Next, activate your virtual environment.

```bash
conda activate yourenv
```
Afterwards, it is essential to install all packages required for this project.

```bash
pip install -r requirements.txt
```
### Loading a model
Use `pickle` package for loading the model to your working space.
``` bash
import pickle
model_loaded = pickle.load(open('model.h5', 'rb'))
```
