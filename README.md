# NucSegment
Model for segmentation of cell nuclei from microscopy images.

All notebooks were run on Google Colab for ease of collaboration and access to GPU. It is recommended that they are opened in colab.

# Directory Structure:

The kaggle dataset "2018 Data Science Bowl" was used in this project. To run the code, the .zip file needs to be `data-science-bowl-2018.zip` at `/content/`.
All training models created will be saved at `/content/output/`

The code is designed to import from a mounted google drive at `/content/drive/MyDrive/nuclei_labelling/` but the code is also designed to work if you upload the data and model yourself. It looks in the local directory befoe trying to import from google drive.

If no model is found in the local drive or in a mounter google drive, it will train a new model. Making it so that the only requirement to run the code is the `data-science-bowl-2018.zip` at `/content/`.
