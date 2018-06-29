Background about Word Mover Distance:
http://vene.ro/blog/word-movers-distance-in-python.html

# MRP_2018
Major Research Project (Grad) 

DOC2VEC tutorial:
http://linanqiu.github.io/2015/10/07/word2vec-sentiment/

### Prerequesite Installation
<b>*Create new Anaconda environment</b><br>
conda create -n python35 python=3.5 tensorflow ipython


*Issue with missing conda environment in jupyter notebook<br>
run conda install nb_conda<br>
run conda install ipykernel<br>
run python -m ipykernel install --user --name python35 --display-name "Python35"

conda install pytorch torchvision -c pytorch

<br>conda install scikit-learn
<br>conda install pandas
<br><br>*install textblob
<br>conda install -c https://conda.anaconda.org/sloria textblob
<br>python -m textblob.download_corpora

<br>*Install Spacy
<br>conda install -c conda-forge spacy
<br>python -m spacy download en

<br>conda install matplotlib
