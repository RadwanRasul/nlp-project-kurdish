<h1 align="center">Training and evaluating a POS-Tag model for Kurmanji-Kurdish using scikit-learn</h1>

<p align="center">This project aims to examine the UD Kurmanji-Kurdish treebank used by Stanza to train the language model "kmr". Trying to find out the potential reasons for the low unlabeled attachment score (UAS) of Stanza’s model, we extracted tokens and POS-tags from the UD-treebank, trained and evaluated a POS-tag model using scikit-learn. In our search for an answer, we also did some linguistic analyses.</p>


## :heavy_check_mark: Requirements

[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

[![Python 3.9.4](https://img.shields.io/badge/Python-3.9.4-blue.svg)](https://www.python.org/downloads/release/python-394/)

The following open source packages are used in this project:

scikit-learn

Matplotlib

CoNLL-U Parser

IPython 

## :desktop_computer: Installation

To run this project, you need to:

:arrow_right: install [Jupyter Notebook](https://jupyter.org/)

```
  pip install notebook
```

:arrow_right: install [CoNLL-U Parser](https://pypi.org/project/conllu/)

```
  pip install conllu
```

:arrow_right: install [scikit-learn](https://scikit-learn.org/)

```
  pip install -U scikit-learn
```

:arrow_right: install [IPython](https://ipython.org/)

```
  pip install ipython
```

:arrow_right: download our Jupyter Notebook file which you can find under the main branch of this repository

:arrow_right: upload this Jupyter Notebook file to your local host so that you can run our code

:arrow_right: download the two CoNLL-U files which you can find in the folder kmr_mg-ud under the main branch

:arrow_right: save these files in the same directory where you uploaded the Jupyter Notebook file

:arrow_right: do not forget to change the names of your Pickle files before you run that code block

## :fountain_pen: Authors

:man: - [@RadwanRasul](https://github.com/RadwanRasul)

:woman: - [@nuryuecel](https://github.com/nuryuecel)

## :scroll: References

For this project we have used the UD Kurmanji treebank.

```
@inproceedings{gokirmak:2017,
    author = {Memduh Gökırmak and Francis M. Tyers},
    title = {A Dependency Treebank for Kurmanji Kurdish},
    booktitle = {Proceedings of the Fourth International Conference on Dependency Linguistics (DepLing, 2017)},
    pages = {64--73},
    year = 2017
}
```

This project was implemented using Scikit-Learn.

```
@article{scikit-learn,
 title={Scikit-learn: Machine Learning in {P}ython},
 author={Pedregosa, F. and Varoquaux, G. and Gramfort, A. and Michel, V.
         and Thirion, B. and Grisel, O. and Blondel, M. and Prettenhofer, P.
         and Weiss, R. and Dubourg, V. and Vanderplas, J. and Passos, A. and
         Cournapeau, D. and Brucher, M. and Perrot, M. and Duchesnay, E.},
 journal={Journal of Machine Learning Research},
 volume={12},
 pages={2825--2830},
 year={2011}
}
```

## :copyright: License

Our project is licensed under the Creative Commons License Attribution-ShareAlike 4.0 International.

The complete license text is available at:
http://creativecommons.org/licenses/by-sa/4.0/legalcode

## :books: Remarks

✤ This is the final project for the course Advanced Natural Language Processing with Python (Summer 2021), at [Heinrich-Heine-Universität Düsseldorf](https://www.hhu.de/)
