# VnDT: The Vietnamese dependency treebank

VnDT is a Vietnamese dependency treebank, consisting of 10K+ sentences. The construction of VnDT is detailed in our [following paper](https://github.com/datquocnguyen/VnDT/blob/master/VnDT-paper-CameraReadyVersion.pdf):

    @InProceedings{Nguyen2014NLDB,
      author = {Nguyen, Dat Quoc  and  Nguyen, Dai Quoc  and  Pham, Son Bao and Nguyen, Phuong-Thai and Nguyen, Minh Le},
      title = {{From Treebank Conversion to Automatic Dependency Parsing for Vietnamese}},
      booktitle = {{Proceedings of 19th International Conference on Application of Natural Language to Information Systems}},
      year = {2014},
      pages = {196-207}
    }

> **By downloading the VnDT treebank, USER agrees:**
> - to use VnDT for research or educational purposes only.
> - to not distribute or part of VnDT in any original or modified form.
>- and to cite our paper whenever VnDT is used to help produce published results.

## Data split

#### With gold-standard POS tags

The VnDT treebank with gold-standard POS tags is split as follows:

- VnDTv1.1-gold-POS-tags-train.conll: 8977 sentences
- VnDTv1.1-gold-POS-tags-dev.conll: 200 sentences
- VnDTv1.1-gold-POS-tags-test.conll: 1020 sentences

These gold-standard POS tags are defined and extracted from the corresponding [Vietnamese constituent treebank](https://www.aclweb.org/anthology/W09-3035/).

#### With predicted POS tags

The VnDT treebank with automatically predicted POS tags is split as follows:

- VnDTv1.1-predicted-POS-tags-train.conll: 8977 sentences
- VnDTv1.1-predicted-POS-tags-dev.conll: 200 sentences
- VnDTv1.1-predicted-POS-tags-test.conll: 1020 sentences

The automatically predicted POS tags are resulted in from handling the data leakage issue as detailed in the [following paper](http://arxiv.org/abs/2101.01476):

    @inproceedings{phonlp,
    title     = {{PhoNLP: A joint multi-task learning model for Vietnamese part-of-speech tagging, named entity recognition and dependency parsing}},
    author    = {Linh The Nguyen and Dat Quoc Nguyen},
    booktitle = {Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Demonstrations},
    year      = {2021}
    }

Please additionally cite this paper whenever the VnDT variant with automatically predicted POS tags is used to help produce published results.

## Versions:

- 04/2014: Released VnDT version 1.0 (VnDTv1.0).
- 12/2018: Released VnDT version 1.1 (VnDTv1.1), fixing several conversion errors that are resulted from annotation inconsistencies in the Vietnamese constituent treebank.
