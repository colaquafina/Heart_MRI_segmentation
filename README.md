# Heart MRI Segmentation

This is a project about Left Atrial Segmentation in MRI images. The dataset can be found in the kaggle (https://www.kaggle.com/datasets/adarshsng/heart-mri-image-dataset-left-atrial-segmentation
). It has 20 training dataset and 10 testing dataset. I use a simple U-net and achieve the dice-coefficient over 0.95 with 100 epochs.

There are several things neet to be notified

1. The preprocessing can really improve the model performance.

2. To increase the dataset, I choose three slices from each of the cases so we can have more data to train.

3. I choose the largest segmentation and both the left and right slices as the selected slices.
