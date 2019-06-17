# Hst956/6.S897 Final Project

Final Project for ML for Healthcare: [Paper](https://github.com/pkarnati2004/hst956/blob/master/pkarnati-aslevy-ezhou-final.pdf)

## From Abstract

Parkinson’s disease (PD) is a neurodegenerativedisorder that causes the impairment of certain movementfunctions. It manifests itself heterogeneously across differentpatients, and it is also diagnosed and staged via relativelysubjective processes, making it hard to study in an objectivemanner. In this paper, we investigate Parkinson’s progressionand stage Parkinson’s using magnetic resonance imaging (MRI)images and critical biomarker data as more objective datasources. A convolutional neural network (CNN) extracts fea-tures from the imaging data, and k-means clustering groupstogether images with common features. By adding in biomarkerdata, we develop a fuller picture of the heterogeneity of thisdisease, but also of the commonalities that draw certain clusterstogether

## Dataset

Dataset used is from the Parkinson's Progression Markers Initiative (PPMI)[https://www.ppmi-info.org/]. Approval is required to access the dataset.

## Methods

We used a Logistic Regression approach using Biomarker data as our baseline for Parkinson's disease modelling. We then use a CNN (ResNet50 from Keras) to stage and classify patients using MRI scans. More information can be found in the uploaded paper.

