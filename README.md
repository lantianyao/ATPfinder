# This is the code and dataset for ATPfinder

## Welcome to ATPfinder, a deep forest-based ATP prediction tool developed by a team from the Chinese University of Hong Kong (Shenzhen)

ATPfinder is a computational framework for identifying anti-tubercular peptides via deep forest architecture with effective feature representation. We also developed a downloadable desktop program for ATPfinder, which is available at https://awi.cuhk.edu.cn/~dbAMP/ATPfinder.html.

First you need to install the Python environment for Deep Forest, via the following command.

    pip install deep-forest
For details of this python package, please refer to the API [here](https://deep-forest.readthedocs.io/en/latest/ "here").

- The dataset used for the model can be found here: https://github.com/lantianyao/ATPfinder/tree/main/data
- [Feature extraction.ipynb](https://github.com/lantianyao/ATPfinder/blob/main/Feature%20extraction.ipynb) provides code to **extract peptide descriptors** used in this study.
- [Model Training.ipynb](https://github.com/lantianyao/ATPfinder/blob/main/Model%20Training.ipynb) is a quick tutorial that tells you how to **train deep forest-based model** with cross-validation.
- [Using the trained model.ipynb](https://github.com/lantianyao/ATPfinder/blob/main/Using%20the%20trained%20model.ipynb) is a quick tutorial telling you how to **use a trained deep forest model**.

If you have any questions, please feel free to contact me.

**Name: Lantian Yao
Email: lantianyao@link.cuhk.edu.cn**
