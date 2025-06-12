# Smoker-Image-Classification


This project aims to build an image classification model that can detect whether a person is a smoker or not based on visual cues in images. The pipeline follows a modular structure including configuration management, component-based development, and experiment tracking.

## Dataset

You can access the dataset [here](https://drive.google.com/file/d/1cxFvUze9NIPn6vsKszjqQuS5ocd5CxPZ/view?usp=sharing).

---

## Workflows
0. cnnClassifier/__init__.py 'logger'
1. Update `config.yaml`  
2. Update `secrets.yaml` *(Optional)*  
3. Update `params.yaml`  
4. Update the entity  
5. Update the configuration manager in `src/config`  
6. Update the components  
7. Update the pipeline  
8. Update the `main.py`  
9. Update the `dvc.yaml`  

---

### Create a Conda Environment After Cloning the Repository

```bash
conda create -n cnnsmoker python=3.10 -y
conda activate cnnsmoker


```bash
pip install -r requirements.txt
