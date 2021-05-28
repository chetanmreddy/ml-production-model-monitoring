## In this project I try to answer the question "How do you do ml model monitoring?, How do you figure out when it is time to retrain our models?"

If you would like try the notebooks, you can use them in a google colab.

Follow these steps:
1) First download the Training data from http://www2.it.lut.fi/project/imageret/diaretdb1/ and place them in the folders as instructed in the notebook (use One-Hot-encoded_GT_creation_3_classes.ipynb).

2) This will generate the groundtruth (GT) folder structure neede for the training.

3) Create an account on https://www.wandb.ai/ and follow intructions in notebook to connect the interface to colab notebook.

4) Use the notebook named Monitoring_TF2_Unet_model.ipynb to run ML model training and producrion monitoring.

5) Checkout my project dashboard here https://wandb.ai/roadrunner/Unet_process

![Screenshot from 2021-05-28 12-57-16](https://user-images.githubusercontent.com/18630132/120037666-d9905500-bfb6-11eb-861b-67e238ebe679.png)

![Screenshot from 2021-05-28 12-57-45](https://user-images.githubusercontent.com/18630132/120037687-df863600-bfb6-11eb-8352-dd3c36b888b3.png)

![Screenshot from 2021-05-28 13-18-55](https://user-images.githubusercontent.com/18630132/120037928-47d51780-bfb7-11eb-8002-3b55cfae954e.png)

