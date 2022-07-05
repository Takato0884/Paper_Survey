# Graph U-Nets

【Authors】Hongyang Gao, Shuiwang Ji  
【Publisher】ICML2019  
【Submission】2019  
【URL】https://arxiv.org/abs/1905.05178  

【Abstract】  
We consider the problem of representation learning for graph data. Convolutional neural networks can naturally operate on images, but have significant challenges in dealing with graph data. Given images are special cases of graphs with nodes lie on 2D lattices, graph embedding tasks have a natural correspondence with image pixel-wise prediction tasks such as segmentation. While encoder-decoder architectures like U-Nets have been successfully applied on many image pixel-wise prediction tasks, similar methods are lacking for graph data. This is due to the fact that pooling and up-sampling operations are not natural on graph data. To address these challenges, we propose novel graph pooling (gPool) and unpooling (gUnpool) operations in this work. The gPool layer adaptively selects some nodes to form a smaller graph based on their scalar projection values on a trainable projection vector. We further propose the gUnpool layer as the inverse operation of the gPool layer. The gUnpool layer restores the graph into its original structure using the position information of nodes selected in the corresponding gPool layer. Based on our proposed gPool and gUnpool layers, we develop an encoder-decoder model on graph, known as the graph U-Nets. Our experimental results on node classification and graph classification tasks demonstrate that our methods achieve consistently better performance than previous models.  

## １．研究概要  
各ノードの重要性スコアを計算し，重要性スコアに応じてノードを選択してからグラフをプーリング（小さいグラフに変換）する手法を提案した．U-Netと呼ばれる画像認識分野の有名な手法をグラフに適応する研究としても解釈できる．
## ２．問題設定と解決した点  
グラフは，画像のように規則的な格子ではないためプーリング処理が困難である．そこで，この研究ではGNNにおけるプーリング手法であるgPoolを提案する．
gPoolは，重要ノードの関係性に注意を向ける．
## ３．技術や手法のキモ  
d

![Model](../image/Gao2019/Fig1.png)  

d

## ４．主張の有効性検証  
![Model](../image/Errica2020/comparing.png)  
## ５．議論すべき点  

## ６．次に読むべき論文  
