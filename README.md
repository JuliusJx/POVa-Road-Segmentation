# Road segmentation POVa project

### Content:

- */demo_images/* - images for final_model_demo.ipynb script
- *final_model_demo.ipynb* - script to evaluate model on testing data
- *POVa_script* - script for model training
- *requirements.txt* - list of libraries needed to run both scripts
- *doc.pdf* - project report

---

### Training:

- ```pip install -r requirements.txt``` - to install dependencies
- script requires **pova_train** and **pova_test** folders to be created in script folder. These folders should contain images and their masks.
- open POVa_script.ipynb inside IDE
- run all cells

**NOTE: Images in demo_images folder are insufficient for this task. Images for training purposes should be downloaded from the [dataset](https://www.kaggle.com/datasets/balraj98/deepglobe-road-extraction-dataset).**

### Model evaluation:

- ```pip install -r requirements.txt``` - to install dependencies
- download the [model](https://nextcloud.fit.vutbr.cz/s/BbyNYoGNWjT5WZm) and put it into the same folder as evaluation script
- open final_model_demo.ipynb inside IDE
- run all cells