# Pairwise Ranking Network for Affect Recognition

【Authors】Georgios Zoumpourlis, Ioannis Patras  
【CPublisher】ACII 2021  
【Submission】2021  
【URL】https://ieeexplore.ieee.org/abstract/document/9597392  

【Abstract】  
In this work we study the problem of emotion recognition under the prism of preference learning. Affective datasets are typically annotated by assigning a single absolute label, i.e. a numerical value that describes the intensity of an emotional attribute, to each sample. Then, the majority of existing works on affect recognition employ sample-wise classification/regression methods to predict affective states, using those annotations. We take a different approach and use a deep network architecture that performs joint training on the tasks of classification/regression of samples and ordinal ranking between pairs of samples. By treating input samples in a pairwise manner, we leverage the auxiliary task of inferring the ordinal relation between their corresponding affective states. Incorporating the ranking objective allows capturing the inherently ordinal structure of emotions and learning the inter-sample relations, resulting in better generalization. Our method is incorporated into existing affect recognition architectures and evaluated on datasets of electroencephalograms (EEG) and images. We show that the approach proposed in this work leads to consistent performance gains when incorporated in classification/regression networks. Index Terms—Affect annotation, emotion recognition, electroencephalogram, facial expressions.  

## １．研究概要  
感情認識で一般的なsample-wiseの回帰/分類タスクに，pair-wiseランキングタスクをサブタスクとして追加することで，元々のタスクの精度も向上することを検証した．

## ２．問題設定と解決した点  
従来の自己報告の感情認識は，回帰/分類タスクとしてモデルを学習してきたが，それには次のような問題点がある．  
まず，自身の感情状態を連続的な値に変換することは，個人の尺度バイアスの影響を受けやすく，機械学習モデルの学習に有害であることが知られている．  
次に，連続的な値を高群/低群のような低次元の分類に変換することは，同じクラス間あるいは異なるクラス間における序数的な情報を失ってしまう可能性がある．  
さらに，高群/低群の基準値は，人間が恣意的に決めるため，感情の本質を反映できないかもしれない．

## ３．技術や手法のキモ

## ４．主張の有効性検証

## ５．議論すべき点
