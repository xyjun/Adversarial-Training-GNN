**在GNN和NLP的任务中中，对抗训练的角色不再是为了防御基于梯度的恶意攻击，反而更多的是作为一种regularization，提高模型的泛化能力。所以这里我收集了一些不同领域相关的论文**

## NLP

#
* [1] [Adversarial Training Methods for Semi-supervised Text Classification](https://arxiv.org/pdf/1605.07725.pdf), ICLR 2017
* TensorFlow implementation：https://github.com/enry12/adversarial_training_methods

#
* [2] [Improving Neural Language Modeling via Adversarial Training](http://proceedings.mlr.press/v97/wang19f/wang19f.pdf),PMLR 2019
* Pytorch implementation：https://github.com/ChengyueGongR/advsoft

#
* [3] [Interpretable Adversarial Perturbation in Input Embedding Space for Text](https://www.ijcai.org/Proceedings/2018/0601.pdf), IJCAI 2018
* Implementation: https://github.com/aonotas/interpretable-adv

# 
* [4] [Adversarial Training for Large Neural Language Models](https://arxiv.org/pdf/2004.08994v1.pdf)
* Implementation: None

# 
* [5] [FreeLB: Enhanced Adversarial Training for Natural Language Understanding](https://openreview.net/pdf?id=BygzbyHFvB),  ICLR 2020
* Implementation: https://github.com/zhuchen03/FreeLB




## CV

#
* [6] [Regularizing Deep Networks Using Efﬁcient Layerwise Adversarial Training](https://arxiv.org/pdf/1705.07819.pdf), AAAI 2018
* Implementation: https://github.com/swamiviv/layerwise_reg

# 
* [7] [Virtual Adversarial Training: A Regularization Method for Supervised and Semi-Supervised Learning](https://arxiv.org/pdf/1704.03976.pdf), IEEE Transactions
* TensorFlow implementation: https://github.com/takerum/vat_tf
* Pytorch implementation: https://github.com/9310gaurav/virtual-adversarial-training ///// https://github.com/lyakaap/VAT-pytorch

# 
* [8] [MixUp as Directional Adversarial Training](https://arxiv.org/pdf/1906.06875.pdf)
* Implementation: https://github.com/mixupAsDirectionalAdversarial/mixup_as_dat
#
* [9] [Towards Deep Learning Models Resistant to Adversarial Attacks] (https://arxiv.org/pdf/1706.06083.pdf)
* Pytorch implementation: https://github.com/Harry24k/PGD-pytorch

#
* [10] [Adversarial Training for Free](https://arxiv.org/pdf/1904.12843.pdf), NeurIPS 2019
* TensorFlow implementation: https://github.com/ashafahi/free_adv_train
* Pytorch implementation: https://github.com/mahyarnajibi/FreeAdversarialTraining


## GNN

#
* [11] [Batch Virtual Adversarial Training for Graph Convolutional Networks](https://arxiv.org/pdf/1902.09192.pdf), ICML 2019 Workshop
* Implementation: None


# 
* [12] [Latent Adversarial Training of Graph Convolution Networks](https://graphreason.github.io/papers/35.pdf), ICML 2019 Workshop
* Implementation: None


#
* [13] [Graph Adversarial Training: Dynamically Regularizing Based on Graph Structure](https://arxiv.org/pdf/1902.08226.pdf), IEEE Transactions
* TensorFlow implementation: https://github.com/fulifeng/GraphAT

# 
* [14] [Adversarial Training Methods for Network Embedding ](https://arxiv.org/pdf/1908.11514.pdf), WWW 2019
* TensorFlow implementation: https://github.com/wonniu/AdvT4NE_WWW2019

#
* [15] [Virtual Adversarial Training on Graph Convolutional Networks in Node Classiﬁcation](https://arxiv.org/pdf/1902.11045.pdf), PRCV 2020
* Implementation: None


# 
* [16] [Learning Graph Embedding with Adversarial Training Methods](https://arxiv.org/pdf/1901.01250.pdf), IEEE Transactions
* Implementation: None





## Recommendation

# 
* [17] [Adversarial Personalized Ranking for Recommendation](https://arxiv.org/pdf/1808.03908.pdf), SIGIR 2018
* Tensorflow implementation: https://github.com/hexiangnan/adversarial_personalized_ranking 

# 
* [18] [Adversarial Training Towards Robust Multimedia Recommender System](https://arxiv.org/pdf/1809.07062.pdf), IEEE Transactions
* Tensorflow implementation: https://github.com/duxy-me/AMR

#
* [19] [Directional Adversarial Training for Recommender Systems](), ECAI 2020
* Implementaion: None



生成扰动的方法总结：

| Perturbation | Model            | Reference |
|--------------|------------------|-----------|
| AT           | GAT,Dwns_AdvT    | [[13]](https://arxiv.org/pdf/1902.08226.pdf),[[14]](https://arxiv.org/pdf/1908.11514.pdf)     |
| VAT          | GATV,BVAT,GCNVAT | [[13]]((https://arxiv.org/pdf/1902.08226.pdf)),[[11]](https://arxiv.org/pdf/1902.09192.pdf),[[15]](https://arxiv.org/pdf/1902.11045.pdf)  |
| DAT          | DAGMF,Mixup      | [[19]](),[[8]](https://arxiv.org/pdf/1906.06875.pdf)     |
| PGD-based    | FREELB,PGD-K      | [[5]](https://openreview.net/pdf?id=BygzbyHFvB),[[10]](https://arxiv.org/pdf/1904.12843.pdf)        |









