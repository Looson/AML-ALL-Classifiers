# Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research Project

## AML & ALL Detection Classifiers

[![CURRENT RELEASE](https://img.shields.io/badge/CURRENT%20RELEASE-0.0.0-blue.svg)](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/0.0.0)
[![UPCOMING RELEASE](https://img.shields.io/badge/UPCOMING%20RELEASE-0.0.1-blue.svg)](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/0.0.1)

![Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research Project](https://www.PeterMossAmlAllResearch.com/media/images/banner.png)
The Peter Moss Acute Myeloid & Lymphoblastic Leukemia classifiers are a collection of projects that use computer vision to classify AML/ALL in unseen images.

This repository includes classifier projects made with Tensorflow, Caffe, Keras, Intel Movidius (NCS & NCS2) and OpenVino. We aim to create projects in Python, Java, C++, R etc and compare results to find out which types of classifiers are more accurate.

&nbsp;

# Data Augmentation

![Acute Myeloid & Lymphoblastic Leukemia Classifier Data Augmentation program](https://www.PeterMossAmlAllResearch.com/media/images/repositories/bannerThin.png)
The [Acute Myeloid & Lymphoblastic Leukemia Classifier Data Augmentation program](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/Augmentation "Acute Myeloid & Lymphoblastic Leukemia Classifier Data Augmentation program") applies filters to datasets and increases the amount of training / test data.

&nbsp;

# Python Classifiers

This repository hosts a collection of classifiers that have been developed by the team using the Python programming language. These classifiers include Caffe, FastAI, Movidius, OpenVino, pure Python and Tensorflow classifiers each project may have multiple classifiers.

| Projects                                                                                                                         | Description                                                 | Status  |
| -------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- | ------- |
| [Caffe Classifiers](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/_Caffe/ "Caffe")                | AML/ALL classifiers created using the Caffe framework.      | Ongoing |
| [FastAI Classifiers](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/_FastAI/ "FastAI")             | AML/ALL classifiers created using the FastAI framework.     | Ongoing |
| [Keras Classifiers](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/_Keras/ "Keras")                | AML/ALL classifiers created using the Keras framework.      | Ongoing |
| [Movidius Classifiers](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/_Movidius/ "Movidius")       | AML/ALL classifiers created using Intel Movidius(NC1/NCS2). | Ongoing |
| [OpenVino Classifiers](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/_OpenVino/ "OpenVino")       | AML/ALL classifiers created using Intel OpenVino.           | Ongoing |
| [Pure Python Classifiers](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/_Pure/ "Pure Python")     | AML/ALL classifiers created using pure Python.              | Ongoing |
| [Tensorflow Classifiers](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/_Tensorflow/ "Tensorflow") | AML/ALL classifiers created using the Tensorflow framework. | Ongoing |

&nbsp;

## Caffe Python Classifiers

The Peter Moss Acute Myeloid & Lymphoblastic Leukemia Python Caffe classifiers are a collection of projects that use computer vision written in Python Caffe to classify Acute Myeloid & Lymphoblastic Leukemia in unseen images.

| Projects                                                                                                                                        | Description                                          | Status  |
| ----------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- | ------- |
| [AllCNN Caffe Classifier](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/_Caffe/allCNN "AllCNN Caffe Classifier") | allCNN classifier created using the Caffe framework. | Ongoing |

&nbsp;

## Intel Movidius/NCS Python Classifiers

This repository hosts a collection of classifiers that have been developed by the team using Python and Intel Movidius NCS/NCS2.

| Project                                                                                                                       | Description                                                       | Status  |
| ----------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- | ------- |
| [Movidius NCS](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/_Movidius/NCS/ "Movidius NCS")    | AML/ALL classifiers created using Intel Movidius NCS.             | Ongoing |
| [Movidius NCS2](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/_Movidius/NCS2/ "Movidius NCS2") | AML/ALL classifiers created using Intel Movidius NCS2 & OpenVino. | Ongoing |

&nbsp;

## FastAI Python Classifiers

The Peter Moss Acute Myeloid & Lymphoblastic Leukemia Python FastAI classifier projects are a collection of projects that use computer vision programs written using FastAI to classify Acute Myeloid & Lymphoblastic Leukemia in unseen images.

| Model  | Project                                                                                                                                                                                     | Description                           | Status  | Author                                                                                                                                                                                     |
| ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------- | ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Resnet | [FastAI Resnet50 Classifier](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/_FastAI/Resnet50/ALL-FastAI-Resnet-50.ipynb "FastAI Resnet50 Classifier")         | A FastAI model trained using Resnet50 | Ongoing | [Salvatore Raieli](https://github.com/salvatorera "Salvatore Raieli") / [Adam Milton-Barker](https://www.petermossamlallresearch.com/team/adam-milton-barker/profile "Adam Milton-Barker") |
| Resnet | [FastAI Resnet50(a) Classifier](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/_FastAI/Resnet50/ALL-FastAI-Resnet-50-a.ipynb "FastAI Resnet50(a) Classifier") | A FastAI model trained using Resnet50 | Ongoing | [Salvatore Raieli](https://github.com/salvatorera "Salvatore Raieli") / [Adam Milton-Barker](https://www.petermossamlallresearch.com/team/adam-milton-barker/profile "Adam Milton-Barker") |
| Resnet | [FastAI Resnet34 Classifier](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/_FastAI/Resnet34/ALL-FastAI-Resnet-34.ipynb "FastAI Resnet34 Classifier")         | A FastAI model trained using Resnet34 | Ongoing | [Salvatore Raieli](https://github.com/salvatorera "Salvatore Raieli") / [Adam Milton-Barker](https://www.petermossamlallresearch.com/team/adam-milton-barker/profile "Adam Milton-Barker") |
| Resnet | [FastAI Resnet18 Classifier](https://github.com/AMLResearchProject/AML-ALL-Classifiers/blob/master/Python/_FastAI/Resnet18/ALL_FastAI_Resnet_18.ipynb "FastAI Resnet18 Classifier")         | A FastAI model trained using Resnet18 | Ongoing | [Salvatore Raieli](https://github.com/salvatorera "Salvatore Raieli") / [Adam Milton-Barker](https://www.petermossamlallresearch.com/team/adam-milton-barker/profile "Adam Milton-Barker") |

&nbsp;

## Keras Python Classifiers

The Peter Moss Acute Myeloid & Lymphoblastic Leukemia Python Keras classifier projects are a collection of projects that use computer vision programs written using Keras to classify Acute Myeloid & Lymphoblastic Leukemia in unseen images.

| Dataset  | Project                                                                                                                                                   | Description                                                                                                                                                                                                                  | Status  | Author                                                                                                                                                                                                 |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ALL_IDB2 | [QuantisedCode](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/_Keras/QuantisedCode/QuantisedCode.ipynb "QuantisedCode")    | A model trained to detect ALL using Keras with Tensorflow Backend, [Paper 1](https://airccj.org/CSCP/vol7/csit77505.pdf "Paper 1") and the original [Dataset 2](https://homes.di.unimi.it/scotti/all/#datasets "Dataset 2"). | Ongoing | [Amita Kapoor](https://www.petermossamlallresearch.com/team/amita-kapoor/profile "Amita Kapoor") & [Taru Jain](https://www.petermossamlallresearch.com/students/student/taru-jain/profile "Taru Jain") |
| ALL_IDB1 | [AllCNN](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/_Keras/AllCNN/Paper_1/ALL_IDB1/Non_Augmented/AllCNN.ipynb "AllCNN") | A model trained to detect ALL using Keras with Tensorflow Backend, [Paper 1](https://airccj.org/CSCP/vol7/csit77505.pdf "Paper 1") and the original [Dataset 1](https://homes.di.unimi.it/scotti/all/#datasets "Dataset 1"). | Ongoing | [Adam Milton-Barker](https://www.petermossamlallresearch.com/team/adam-milton-barker/profile "Adam Milton-Barker")                                                                                     |
| ALL_IDB2 | [AllCNN](https://github.com/AMLResearchProject/AML-ALL-Classifiers/tree/master/Python/_Keras/AllCNN/Paper_1/ALL_IDB2/Non_Augmented/AllCNN.ipynb "AllCNN") | A model trained to detect ALL using Keras with Tensorflow Backend, [Paper 1](https://airccj.org/CSCP/vol7/csit77505.pdf "Paper 1") and the original [Dataset 2](https://homes.di.unimi.it/scotti/all/#datasets "Dataset 2"). | Ongoing | [Adam Milton-Barker](https://www.petermossamlallresearch.com/team/adam-milton-barker/profile "Adam Milton-Barker")                                                                                     |

&nbsp;

## Detecting Acute Lymphoblastic Leukemia Using Caffe, OpenVino & Neural Compute Stick Series

A series of articles / tutorials by [Adam Milton-Barker](https://www.petermossamlallresearch.com/team/adam-milton-barker/profile "Adam Milton-Barker") that take you through attempting to replicate the work carried out in the [Acute Myeloid Leukemia Classification Using Convolution Neural Network In Clinical Decision Support System](https://airccj.org/CSCP/vol7/csit77505.pdf "Acute Myeloid Leukemia Classification Using Convolution Neural Network In Clinical Decision Support System") paper.

- [Introduction to convolutional neural networks in Caffe\*](https://github.com/AMLResearchProject/AML-ALL-Classifiers/blob/master/Python/_Caffe/allCNN/Caffe-Layers.md "Introduction to convolutional neural networks in Caffe*")
- [Preparing the Acute Lymphoblastic Leukemia dataset](https://github.com/AMLResearchProject/AML-ALL-Classifiers/blob/master/Python/_Caffe/allCNN/Data-Sorting.md "Preparing the Acute Lymphoblastic Leukemia dataset")

&nbsp;

# Contributing

The Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research project encourages and welcomes code contributions, bug fixes and enhancements from the Github.

Please read the [CONTRIBUTING](https://github.com/AMLResearchProject/AML-ALL-Classifiers/blob/master/CONTRIBUTING.md "CONTRIBUTING") document for a full guide to forking our repositories and submitting your pull requests. You will also find information about our code of conduct on this page.

## Team Contributors

The following Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research project team members have contributed towards this repository:

- [Adam Milton-Barker](https://www.petermossamlallresearch.com/team/adam-milton-barker/profile "Adam Milton-Barker") - Bigfinite IoT Network Engineer & Intel Software Innovator, Barcelona, Spain
- [Salvatore Raieli](https://www.petermossamlallresearch.com/team/salvatore-raieli/profile "Salvatore Raieli") - PhD Immunolgy / Bioinformaticia, Bologna, Italy
- [Dr Amita Kapoor](https://www.petermossamlallresearch.com/team/amita-kapoor/profile "Dr Amita Kapoor") - Delhi University, Delhi, India

## Student Program Contributors

The following AML/ALL AI Student Program Students & Research Interns have contributed towards this repository:

- [Taru Jain](https://www.petermossamlallresearch.com/students/student/taru-jain/profile "Taru Jain") - Pre-final year undergraduate pursuing B.Tech in IT

&nbsp;

# Versioning

We use SemVer for versioning. For the versions available, see [Releases](https://github.com/AMLResearchProject/AML-ALL-Classifiers/releases "Releases").

# License

This project is licensed under the **MIT License** - see the [LICENSE](https://github.com/AMLResearchProject/AML-ALL-Classifiers/blob/master/LICENSE "LICENSE") file for details.

# Bugs/Issues

We use the [repo issues](https://github.com/AMLResearchProject/AML-ALL-Classifiers/issues "repo issues") to track bugs and general requests related to using this project.
