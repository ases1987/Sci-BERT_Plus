# Sci-BERT+
A Scientific NER System based on an Bi-LSTM core architecture and Sci-BERT language model. The Google Colab files are attached with each of the codes pero dataset and tagging method. The architecture of the model could be seen as follows:

![Architecture](https://user-images.githubusercontent.com/68359766/173453698-2e0c1893-7e67-4a7d-81a0-59ee0b7bc337.jpg)

Our work is published in ...... Please use the following to cite our work:

@Article{DAD,
author={Markewich, Logan
        and Zhang, Hao
        and Xing, Yubin
        and Lambert-Shirzad, Navid
        and Jiang, Zhexin
        and Lee, Roy Ka-Wei
        and Li, Zhi
        and Ko, Seok-Bum},
title={Segmentation for document layout analysis: not dead yet},
journal={International Journal on Document Analysis and Recognition (IJDAR)},
year={2022},
month={Jan},
day={13},
abstract={Document layout analysis is often the first task in document understanding systems, where a document is broken down into identifiable sections. One of the most common approaches to this task is image segmentation, where each pixel in a document image is classified. However, this task is challenging because as the number of classes increases, small and infrequent objects often get missed. In this paper, we propose a weighted bounding box regression loss methodology to improve accuracy for segmentation of document layouts, while demonstrating our results on our dense article dataset (DAD) and the existing PubLayNet dataset. First, we collect and annotate 43 document object classes across 450 open access research articles, constructing DAD. After benchmarking several segmentation networks, we achieve an F1 score of 96.26{\%} on DAD and 97.11{\%} on PubLayNet with DeeplabV3+, while also showing a bounding box regression method for segmentation results that improves the F1 by +1.99 points on DAD. Finally, we demonstrate the networks trained on DAD can be used as a bootstrapped annotation tool for the existing document layout datasets, decreasing annotation time by 38{\%} with DeeplabV3+.},
issn={1433-2825},
doi={10.1007/s10032-021-00391-3},
url={https://doi.org/10.1007/s10032-021-00391-3}
}
