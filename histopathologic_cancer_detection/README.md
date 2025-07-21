# Cancer Detection Using CNN and Pythorch

The Histopathologic Cancer Detection competition on Kaggle challenges participants to develop an algorithm that can identify metastatic cancer in small image patches taken from larger digital pathology scans of lymph node sections.

## Problem Description:

You are provided with a large set of small color images (96x96 pixels) extracted from histopathologic scans of lymph node sections.

Each image must be classified as either containing metastatic tumor tissue or not—a binary classification task.

A positive label means the center 32x32 pixel region of the patch contains at least one pixel of tumor tissue. Tumor tissue in the outer region does not influence the label, but is included to support fully convolutional models and ensure consistent predictions when applied to whole-slide images.

The dataset includes a CSV file (train_labels.csv) providing ground truth labels for the training images, and you are to predict labels for the test images.

The competition uses a slightly modified version of the PatchCamelyon (PCam) benchmark dataset, with duplicates removed.

## Goal:
Build a machine learning model that can accurately classify these image patches for the presence of metastatic cancer, aiding in the automation of pathology workflows.

## Evaluation Metric:
Submissions are evaluated using the Area Under the ROC Curve (AUC) between the predicted probabilities and the observed targets.

This competition is a classic computer vision challenge in medical imaging, aimed at improving cancer detection accuracy and efficiency in clinical settings

[Link to Kaggle competition](https://www.kaggle.com/competitions/histopathologic-cancer-detection)
