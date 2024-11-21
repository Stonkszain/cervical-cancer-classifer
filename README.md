# cervical-cancer-classifer

This is a project which uses the Cervical Cancer largest dataset (SipakMed) to classify images into 5 categories. It uses the tiny version of the Convnext family of models pretrained on the ImageNet-21k dataset. It is trained by fine tuning this model over 3 epochs.

The total training time was 4 minutes and 39 seconds on a Tesla P100 GPU. This was trained on a Kaggle notebook.

It achieves a validation accuracy of 94%.

"The SIPaKMeD Database consists of 4049 images of isolated cells that have been manually cropped from 966 cluster cell images of Pap smear slides. These images were acquired through a CCD camera adapted to an optical microscope. The cell images are divided into five categories containing normal, abnormal and benign cells." (https://www.kaggle.com/datasets/prahladmehandiratta/cervical-cancer-largest-dataset-sipakmed)
