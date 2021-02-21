# General Domain Neural Networks for Speciﬁc Image Similarity Domain
## Using the Danish Real Estate dataset

> This repository is the culmination of the authors Bachelor Thesis Project.

### Abstract
This study investigates the ability of two general-domain CNN's to perform as well as an in-domain model through image augmentation and fine-tuning the top layers of the general-domain models. The purpose of this study has been to teach two publicly available pre-trained general-domain models to be able to give meaningful representations of images from the Danish housing market, with only limited labeled in-domain images. This was done for the purpose of helping real estate agencies to increase their customer engagement, by allowing the customers to search for homes that matches their aesthetic preferences.

An elaborate investigation of transfer learning has been used to train different layers of the general-domain models. Through supervised transfer learning it was possible to teach the two general-domain models to be equally as good at representing features found in the in-domain images as the in-domain model were.

A previous study claims the impact of using the in-domain preprocessing scheme can improve a models top-1 accuracy by 30\% points. In the purpose of recreating the results from the previous study, a variety of experiments were conducted, however this claim was refuted.

By reducing the dimensionality of the representation/feature vector it is possible to obtain higher top-1 accuracies, this was also reported in the previous study. The experiments in this study can acknowledge the impact of reducing dimensionality of the feature vector.

Finally an experiment with supervised contrastive learning is conducted, however due to the limited in-domain data available, this was not a success.
