# Training spaCy's spancat component in Python 🐍

<p align="center">
  <img src="https://user-images.githubusercontent.com/46863334/194558740-95e51e09-81d9-41b6-8481-38a2aaee3f98.gif" alt="spancat"/>
</p>

The code behind [this medium article on training spaCy's spancat component in Python](https://hackmd.io/Yg2u3MZQS26_WbdO5WSdWw?edit).

To download the dataset used in this article, sign up to kaggle and [download the .csv dataset here](https://www.kaggle.com/datasets/debasisdotcom/name-entity-recognition-ner-dataset). 

## Set up 🛠️

1. **Clone this git repo:** `git clone https://github.com/india-kerle/spancat.git`
2. **Create your conda environment:** `conda create --name spancat_training`
3. **Activate your conda environment:** `conda activate spancat_training` 
4. **(at the repo base) install dependencies:** `pip install -r requirements.txt`
5. **add your environment to jupyter notebook:** `python -m ipykernel install --user --name=spancat_training`

6. Run the notebook to replicate the training! Remember to make sure your kernel is the right environment, `spancat_training`.  
