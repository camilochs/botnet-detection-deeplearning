# Botnet detection using Deep learning

This is a implementation of the paper: "Deep learning to detect botnet via network flow summaries" using Keras.
- [link](https://link.springer.com/article/10.1007/s00521-018-3595-x)

Dependencies:

- keras==2.3.1
- pandas==1.0.1
- jupyterlab==1.2.6
- networkx==2.4

The datasets used as follows:
- [CTU-13](https://www.stratosphereips.org/datasets-ctu13)

Important:
- You need the "all-data-filtered.csv.gz" file into "datasets/" or have "CTU-13-Dataset" folder into "datasets/".

Usage:
- run jupyterlab.
- open jupyter notebook: `classifier DNN.ipynb`.