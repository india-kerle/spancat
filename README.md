# Training spaCy's spancat component in Python

![spancat_intro_example](https://user-images.githubusercontent.com/46863334/194313699-954576ce-3bf3-4e77-98be-a17e900b4dee.png)
_Labelled spans in text, [courtesy of Explosion.ai](https://explosion.ai/blog/spancat)

The code behind [this medium article on training spaCy's spancat component in Python](https://medium.com/all-you-can-heat/developing-a-heat-pump-installer-proximity-indicator-6188e321f709).

To download the dataset used in this article, sign up to kaggle and [download the .csv dataset here](https://www.kaggle.com/datasets/debasisdotcom/name-entity-recognition-ner-dataset). 


## Set up

1. **Clone this git repo:** `git clone https://github.com/india-kerle/skills_taxonomy.git`
2. **Create your conda environment:** `conda create --name spancat_training`
3. **Activate your conda environment:** `conda activate spancat_training` 
4. **(at the repo base) install dependencies:** `pip install -r requirements.txt`
5. **add your environment to jupyter notebook:** `python -m ipykernel install --user --name=spancat_training`

6. Run the notebook to replicate the training! Remember to make sure your kernel is the right environment, `spancat_training`.  
