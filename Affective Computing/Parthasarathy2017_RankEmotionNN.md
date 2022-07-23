# Ranking emotional attributes with deep neural networks

【Authors】Srinivas Parthasarathy; Reza Lotfian; Carlos Busso  
【Publisher】ICASSP2017  
【Submission】2017    
【URL】https://ieeexplore.ieee.org/document/7953107  

【Abstract】  
Studies have shown that ranking emotional attributes through preference learning methods has significant advantages over conventional emotional classification/regression frameworks. Preference learning is particularly appealing for retrieval tasks, where the goal is to identify speech conveying target emotional behaviors (e.g., positive samples with low arousal). With recent advances in deep neural networks (DNNs), this study explores whether a preference learning framework relying on deep learning can outperform conventional ranking algorithms. We use a deep learning ranker implemented with the RankNet algorithm to evaluate preference between emotional sentences in terms of dimensional attributes (arousal, valence and dominance). The results show improved performance over ranking algorithms trained with support vector machine (SVM) (i.e., RankSVM). The results are significantly better than performance reported in previous work, demonstrating the potential of RankNet to retrieve speech with target emotional behaviors.  

## １．研究概要
次元属性（覚醒度、価数、優位性）の観点から発話間のプリファレンスを推定するRankNetアルゴリズムで実装された深層学習モデルを提案した．
## ２．問題設定と解決した点
Rank-SVMなどを用いて感情スコアのランキングに取り組んだ研究はこれまでにもあったが，このタスクに深層学習は適用されていなかった．
本研究は，RankNetアルゴリズムで実装された深層学習モデルを使って，感情スコアのランキングに取り組んだ最初の研究である．
## ３．技術や手法のキモ
RankNetにおいて，最低でもマージンtだけ離れているサンプル間でペアを作成することが，テストデータ(全ペア)のプリファレンス推定に有効であることを明らかにした．
## ４．主張の有効性検証
Precision＠ｋとKendall's tau coefficientを用いて，RankNetとRank-SVM, DNNregressionを比較した．
