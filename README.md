# Deep Learning for Molecules and Materials Book

[![Build Stats](https://github.com/whitead/dmol-book/workflows/deploy-book/badge.svg)](https://github.com/whitead/dmol-book/actions)

日本語版はこちらから読めます [https://resnant.github.io/dmol-book-japanese/](https://resnant.github.io/dmol-book-japanese/)

原著（英語版）はこちらから [dmol.pub](https://dmol.pub)  
&copy; Andrew White (original author)


## 翻訳への協力のお願い
現在の翻訳の進捗は以下です。もし翻訳を手伝ってもいいよという方がいらっしゃれば、どの章を担当したいかissueでお知らせください。  

A. Math Review

- [ ] 1. Tensors and Shapes

B. Machine Learning

- [x] 2. Introduction to Machine Learning
- [ ] 3. Regression & Model Assessment
  - in progress by @ikwus
- [ ] 4. Classification
- [ ] 5. Kernel Learning
- [ ] C. Deep Learning

- [ ] 6. Deep Learning Overview
- [ ] 7. Standard Layers
- [ ] 8. Graph Neural Networks
- [ ] 9. Input Data & Equivariances
- [ ] 10. Equivariant Neural Networks
- [ ] 11. Modern Molecular NNs
- [ ] 12. Explaining Predictions
- [ ] 13. Attention Layers
- [ ] 14. Deep Learning on Sequences
- [ ] 15. Variational Autoencoder
- [ ] 16. Normalizing Flows

D. Applications
- [ ] 17. Predicting DFT Energies with GNNs
  - in progress by @resnant
- [ ] 18. Generative RNN in Browser

E. Contributed Chapters

- [ ] 19. Hyperparameter Tuning

### contributionの手順
1. どの章を担当したいかissueを立てる
2. このリポジトリをご自分のアカウントでフォーク
3. ご興味のある章のnotebook(ipynbファイル）を選んで、VS CodeやJupyter上で翻訳し、commit
  - 具体的には、このリポジトリ以下の `math/`, `ml/`, `dl/`, `applied/` の各ディレクトリの中のファイルです
  - ご不明な点などあればissueでお気軽にご相談ください
4. ご自分のアカウントのリポジトリにpush後、このリポジトリにpull requestを提出
  - 内容を確認してmergeします