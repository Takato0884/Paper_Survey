# Adversarial Examples for Evaluating Reading Comprehension Systems  

【Authors】Robin Jia, Percy Liang  
【Publisher】EMNLP 2017  
【Submission】2017  
【URL】https://arxiv.org/abs/1707.07328  

【Abstract】  
Standard accuracy metrics indicate that reading comprehension systems are making rapid progress, but the extent to which these systems truly understand language remains unclear. To reward systems with real language understanding abilities, we propose an adversarial evaluation scheme for the Stanford Question Answering Dataset (SQuAD). Our method tests whether systems can answer questions about paragraphs that contain adversarially inserted sentences, which are automatically generated to distract computer systems without changing the correct answer or misleading humans. In this adversarial setting, the accuracy of sixteen published models drops from an average of 75% F1 score to 36%; when the adversary is allowed to add ungrammatical sequences of words, average accuracy on four models decreases further to 7%. We hope our insights will motivate the development of new models that understand language more precisely.  

## １．研究概要  
SQuADデータセットに対して，敵対的な摂動を加える方法について提案している．また，敵対的な摂動を加えたSQuADデータセットを用いて，従来のモデルの頑健性を検証した．
## ２．問題設定と解決した点  
NLP分野で手安されてきた従来のモデルがどれほど自然言語を理解しているかについては不明である．また，一部ではモデルがタスクを効率って気に解くためのショートカットを利用しているという指摘もある．そこで，この研究では，敵対的摂動が加えられたデータセットを用いて，従来のモデルのロバスト性を検証した．
## ３．技術や手法のキモ  

## ４．主張の有効性検証
## ５．議論すべき点
## ６．次に読むべき論文
