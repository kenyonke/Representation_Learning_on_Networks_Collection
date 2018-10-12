# Representation_Learning_on_Networks_Collection

## Graph Convolutional Network
paper: https://arxiv.org/abs/1609.02907
code: https://github.com/tkipf/gcn

A node representation learning method based on the structure information (adjacency matrix) and node features. GCN makes use of the idea of CNN
and create a weight sharing filter for learning latent features.

## Node2vec
paper: https://arxiv.org/pdf/1607.00653.pdf 
code: https://github.com/aditya-grover/node2vec

A node representation learning method based on the structure information only. This method followed the idea of skip-gram in word2vec
in order to learn representations of node.

## GraphSage
paper: https://arxiv.org/abs/1709.05584
code: https://github.com/williamleif/GraphSAGE

In my opinion, it is a flexible GCN algorithm. Because it can train a node at a time but GCN have to train the whole graph because of
the Graph Laplacian. Also, GrpahSage works well when the dataset is very large. 

# Graph Data
Standford Large Network: http://snap.stanford.edu/data/

The Koblenz Network Collection: http://konect.uni-koblenz.de/
