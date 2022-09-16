# WIFS2022-RoSe-DNNWatermarking

### RoSe: A RObust and SEcure Black-Box DNN Watermarking
**IEEE International Workshop on Information Forensics and Security (WIFS) 2022**

### Auhtors: Kassem Kallas and Teddy Furon

### Centre Inria de l’Université de Rennes, France

This repository consists of the tensforflow implementation for our WIFS 2022 paper RoSe: A RObust and SEcure Black-Box DNN Watermarking available at:
https://arxiv.org/abs/2206.11024

This notebook has been tested on google Colab and on local and remote GPUs

### Requirements
tensorflow
tensorflow-model-optimization
numpy
seaborn
hashlib
PIL
h5py
zipfile
tempfile
scipy
shutil
sklearn
glob
matplotlib
math

# Abstract
Protecting the Intellectual Property rights of DNN models is of primary importance prior to their deployment. So far, the proposed methods either necessitate changes to internal model parameters or the machine learning pipeline, or they fail to meet both the security and robustness requirements. This paper proposes a lightweight, robust, and secure black-box DNN watermarking protocol that takes advantage of cryptographic one-way functions as well as the injection of in-task key image-label pairs during the training process. These pairs are later used to prove DNN model ownership during testing. The main feature is that the value of the proof and its security are measurable. The extensive experiments watermarking image classification models for various datasets as well as exposing them to a variety of attacks, show that it provides protection while maintaining an adequate level of security and robustness.

# Results
![alt Results Against Attacks](https://github.com/KassemKallas/WIFS2022-RoSe-DNNWatermarking/blob/main/Table1.png?raw=true)

![alt Results with JPEG Compression](https://github.com/KassemKallas/WIFS2022-RoSe-DNNWatermarking/blob/main/Table2.png?raw=true)

## Acknowledgments
We would like to thank the ANR and AID french agencies for funding Chaire SAIDA ANR-20-CHIA-0011.

## Citation

If you find this work useful and use it on your own research, please cite our paper  

```
@inproceedings{kallas2022rose,
  title={RoSe: A RObust and SEcure Black-Box DNN Watermarking},
  author=author={Kallas, Kassem and Furon, Teddy},
  booktitle={IEEE International Workshop on Information Forensics and Security},
  year={2022}
}

```
