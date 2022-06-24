# An End-to-End Deep Learning Architecture for Graph Classification  

【Authors】Muhan Zhang Zhicheng Cui Marion Neumann Yixin Chen  
【Publisher】AAAI 2018  
【Submission】2018  
【URL】https://ojs.aaai.org/index.php/AAAI/article/view/11782  

【Abstract】  
Neural networks are typically designed to deal with data in tensor forms. In this paper, we propose a novel neural network architecture accepting graphs of arbitrary structure. Given a dataset containing graphs in the form of (G,y) where G is a graph and y is its class, we aim to develop neural networks that read the graphs directly and learn a classification function. There are two main challenges: 1) how to extract useful features characterizing the rich information encoded in a graph for classification purpose, and 2) how to sequentially read a graph in a meaningful and consistent order. To address the first challenge, we design a localized graph convolution model and show its connection with two graph kernels. To address the second challenge, we design a novel SortPooling layer which sorts graph vertices in a consistent order so that traditional neural networks can be trained on the graphs. Experiments on benchmark graph classification datasets demonstrate that the proposed architecture achieves highly competitive performance with state-of-the-art graph kernels and other graph neural network methods. Moreover, the architecture allows end-to-end gradient-based training with original graphs, without the need to first transform graphs into vectors.  

## １．研究概要
## ２．問題設定と解決した点
## ３．技術や手法のキモ
## ４．主張の有効性検証
## ５．議論すべき点
## ６．次に読むべき論文
