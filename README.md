# Automatic brain tumor grading from MRI data using convolutional neural networks and quality assessment

## Description

This repository contains the subject's ID used for Training, Validation, and Test.

More details can be found in our paper.

## Contents

```brats2017_subjects_sets.py``` we divided BRATS 2017 Training set into the following subsets: Training (60%), Validation (20%), and Test (20%). This script contains the subject's ID of each subset (it can also be used for BRATS 2018, since the provided Training set is equal).

This can be used to compare directly with us, using the Test set (results in the paper, Table 1).


## Citation

If you found this code useful, please, cite our paper:

Sérgio Pereira, Raphael Meier, Victor Alves, Mauricio Reyes, and Carlos A. Silva, "Automatic brain tumor grading from MRI data using convolutional neural networks and quality assessment", MICCAI Workshop on Interpretability of Machine Intelligence in Medical Image Computing, Lecture Notes in Computer Science, 2018.


## Abstract

Glioblastoma Multiforme is a high grade, very aggressive, brain tumor, with patients having a poor prognosis. Lower grade gliomas are less aggressive, but they can evolve into higher grade tumors over time. Patient management and treatment can vary considerably with tumor grade, ranging from tumor resection followed by a combined radio- and chemotherapy to a "wait and see" approach. Hence, tumor grading is important for adequate treatment planning and monitoring. The gold standard for tumor grading relies on histopathological diagnosis of biopsy specimens. However, this procedure is invasive, time consuming, and prone to sampling error. Given these disadvantages, automatic tumor grading from widely used MRI protocols would be clinically important, as a way to expedite treatment planning and assessment of tumor evolution. In this paper, we propose to use Convolutional Neural Networks for predicting tumor grade directly from imaging data. In this way, we overcome the need for expert annotations of regions of interest. We evaluate two prediction approaches: from the whole brain, and from an automatically defined tumor region. Finally, we employ interpretability methodologies as a quality assurance stage to check if the method is using image regions indicative of tumor grade for classification.

## Contact
For information related with the paper, please feel free to contact me via e-mail: id5692@alunos.uminho.pt
