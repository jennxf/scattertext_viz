# Scattertext-PyData
Notebooks for the Seattle PyData 2017 talk on Scattertext
# Changes i made to the original code to get it working for python 3.6:
1. use conda environment py36
2. conda install cycler
3. pip3 install dependencies while in py36
4. python3 -m pip install ipykernel [see code](https://stackoverflow.com/questions/28831854/how-do-i-add-python3-kernel-to-jupyter-ipython)
5. python -m ipykernel install --name py36
6. conda install -c conda-forge matplotlib 
7. pip install -U spacy
8. python -m spacy download en
9. initiate jupyter notebook 
10. select a new notebook with py36
A guide to using the python package [Scattertext](http://github.com/JasonKessler/scattertext).  If you feel so moved, please star it, fork it, or even contribute!

Check out the introductory presentation [here](https://github.com/JasonKessler/Scattertext-PyData/raw/master/PyData2017Kessler.pptx).

# Video
[![Watch the PyData talk here](https://raw.githubusercontent.com/JasonKessler/jasonkessler.github.io/master/scattertext_youtube.png)](https://www.youtube.com/watch?v=H7X9CA2pWKo)

# Using the notebooks
The notebooks look best in Chrome.

## Slow but interactive way
In order to use these notebooks, please execute the following commands, please clone this repo and run (in Python 3):
```
$ git clone https://github.com/JasonKessler/Scattertext-PyData
$ pip3 install scattertext agefromname
$ cd Scattertext-PyData
$ jupyter notebook
```
## Fast and non-interative way
* [First Notebook](https://nbviewer.jupyter.org/github/JasonKessler/Scattertext-PyData/blob/master/PyData-Scattertext-Part-1.ipynb) how to use Scattertext to visualize differences in document types.
[![Conventions-Visualization.html](https://jasonkessler.github.io/2012conventions0.0.2.2.png)](https://nbviewer.jupyter.org/github/JasonKessler/Scattertext-PyData/blob/master/PyData-Scattertext-Part-1.ipynb)
* [Second Notebook](https://nbviewer.jupyter.org/github/JasonKessler/Scattertext-PyData/blob/master/PyData-Scattertext-Part-2.ipynb) how to use Scattertext and AgeFromName to understand how lanugage, gender and political party intersect.
[![Gender and Party](https://github.com/JasonKessler/Scattertext-PyData/raw/master/img/genderandparty.png)](https://nbviewer.jupyter.org/github/JasonKessler/Scattertext-PyData/blob/master/PyData-Scattertext-Part-2.ipynb)
* [Third Notebook](https://nbviewer.jupyter.org/github/JasonKessler/Scattertext-PyData/blob/master/PyData-Scattertext-Part-3.ipynb) how to use Scattertext to visualize how the same word or semantic type is discussed different between document categories. In this case, we explore how "jobs" is discussed differently by Republicans and Democrats.
[![Word representations](https://github.com/JasonKessler/Scattertext-PyData/raw/master/img/gensim_similarity.png)](https://nbviewer.jupyter.org/github/JasonKessler/Scattertext-PyData/blob/master/PyData-Scattertext-Part-3.ipynb)


