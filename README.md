# Paper Collection of Continual Learning

Continual Learning, also known as Incremental Learning or Overcoming Catastrophic Forgetting, aiming at retaining performance of neural network in sequential training setting, i.e. training on a new task without losing performance in previous task(s).

This is a collection of research and review papers of Continual Learning. The Papers are sorted by time. Any suggestions and pull requests are welcome.

The sharing principle of these references here is for research. If any authors do not want their paper to be listed here, please feel free to contact [Xuejian Wang](xuejianwang.com) (Email: xuejian.xjw [AT] gmail.com).<sup>[1](#myfootnote1)</sup>



## Overview
* [Research Papers](#research-papers)
  * [Foundamentals](#foundamentals)
  * [Setting Discussion](#setting-discussion)
  * [Regularization Based](#regularization-based)
  * [Rehearsal or Psuedo Rehearsal](#rehearsal-or-pusedo-rehearsal)
  * [Network Structure](#network-structure)

## Research Papers

### Foundamentals
* [Catastrophic interference in connectionist networks: The sequential learning problem](https://www.sciencedirect.com/science/article/pii/S0079742108605368) by McCloskey, Michael and Cohen, Neal J. Psychology of learning and motivation, 1989.
* [A practical Bayesian framework for backpropagation networks](https://arxiv.org/pdf/1703.06182.pdf) by MacKay, David JC. Neural computation, 1992.
* [Catastrophic forgetting in connectionist networks](https://www.sciencedirect.com/science/article/pii/S1364661399012942) by French, Robert M. Trends in cognitive sciences, 1999.
* [Revisiting natural gradient for deep networks](https://arxiv.org/abs/1301.3584) by Razvan Pascanu, Yoshua Bengio. ICLR, 2014.
* [Distilling the knowledge in a neural network](https://arxiv.org/abs/1503.02531) by Geoffrey Hinton, Oriol Vinyals, Jeff Dean. arXiv, 2015.

### Setting Discussion
* [An Empirical Investigation of Catastrophic Forgetting in Gradient-Based Neural Networks](https://arxiv.org/pdf/1312.6211.pdf) by 
Ian J. Goodfellow, Mehdi Mirza, Da Xiao, Aaron Courville, Yoshua Bengio. arXiv, 2013.
* [Measuring catastrophic forgetting in neural networks](https://arxiv.org/abs/1708.02072) by Ronald Kemker, Marc McClure, Angelina Abitino, Tyler Hayes, Christopher Kanan. AAAI, 2018.
* [Towards robust evaluations of continual learning](https://arxiv.org/abs/1805.09733) by 
Sebastian Farquhar, Yarin Gal. ICML LLRALA Workshop, 2018.
* [A comprehensive, application-oriented study of catastrophic forgetting in DNNs](https://openreview.net/forum?id=BkloRs0qK7) by B. Pfülb, A. Gepperth. ICLR, 2019.
* [An Empirical Study of Example Forgetting during Deep Neural Network Learning](https://openreview.net/forum?id=BJlxm30cKm) by Mariya Toneva*, Alessandro Sordoni*, Remi Tachet des Combes*, Adam Trischler, Yoshua Bengio, Geoffrey J. Gordon. ICLR, 2019.



### Regularization Based
* [Overcoming catastrophic forgetting in neural networks](https://arxiv.org/abs/1612.00796) by James Kirkpatrick. arXiv, 2017.
* [Continual Learning Through Synaptic Intelligence](https://arxiv.org/abs/1703.04200) by Friedemann Zenke, Ben Poole, Surya Ganguli. ICML, 2017.
* [Overcoming Catastrophic Forgetting by Incremental Moment Matching](https://arxiv.org/abs/1703.08475) by Sang-Woo Lee. NIPS, 2017.
* [Variational Continual Learning](https://arxiv.org/abs/1710.10628) by Cuong V. Nguyen, Yingzhen Li, Thang D. Bui, Richard E. Turner. ICLR, 2018.
* [Online Structured Laplace Approximations For Overcoming Catastrophic Forgetting](https://arxiv.org/abs/1805.07810) by 
Hippolyt Ritter, Aleksandar Botev, David Barber. NIPS, 2018.

### Rehearsal or Psuedo Rehearsal
* [Learning without Forgetting](https://arxiv.org/abs/1606.09282) by Zhizhong Li, Derek Hoiem. CVPR, 2016.
* [iCaRL: Incremental Classifier and Representation Learning](https://arxiv.org/abs/1611.07725) by 
Sylvestre-Alvise Rebuffi, Alexander Kolesnikov, Georg Sperl, Christoph H. Lampert. CVPR, 2017.
* [Continual Learning with Deep Generative Replay](https://arxiv.org/abs/1705.08690) by Hanul Shin, Jung Kwon Lee, Jaehong Kim, Jiwon Kim. NIPS, 2017.
* [FearNet: Brain-Inspired Model for Incremental Learning](https://arxiv.org/abs/1711.10563) by Ronald Kemker, Christopher Kanan. ICLR, 2018.
* [Incremental Classifier Learning with Generative Adversarial Networks](https://arxiv.org/abs/1802.00853) by Yue Wu, Yinpeng Chen, Lijuan Wang, Yuancheng Ye, Zicheng Liu, Yandong Guo, Zhengyou Zhang, Yun Fu. arXiv, 2018.
* [Memory Replay GANs: Learning to Generate New Categories without Forgetting](https://papers.nips.cc/paper/7836-memory-replay-gans-learning-to-generate-new-categories-without-forgetting) by Chenshen Wu, et al. NIPS, 2018.
* [Overcoming Catastrophic Forgetting for Continual Learning via Model Adaptation](https://openreview.net/forum?id=ryGvcoA5YX) by Wenpeng Hu, et al. ICLR, 2019.


### Network Structure
* [Progressive Neural Networks](https://arxiv.org/abs/1606.04671) by 
Andrei A. Rusu. arXiv, 2016.
* [PathNet: Evolution Channels Gradient Descent in Super Neural Networks](https://arxiv.org/pdf/1711.00832.pdf) by 
Chrisantha Fernando, et al. arXiv 2017.
* [Overcoming catastrophic forgetting through weight consolidation and long-term memory](https://arxiv.org/abs/1805.07441) by Shixian Wen, Laurent Itti. arXiv, 2018.
* [Learn to Grow: A Continual Structure Learning Framework for Overcoming Catastrophic Forgetting](https://arxiv.org/abs/1904.00310) by Xilai Li, Yingbo Zhou, Tianfu Wu, Richard Socher, Caiming Xiong. ICML, 2019.

### Yet Not Categorized
* [Dynamic Few-Shot Visual Learning without Forgetting](https://arxiv.org/abs/1804.09458) by Spyros Gidaris, Nikos Komodakis. CVPR, 2018.
* [Generative replay with feedback connections as a general strategy for continual learning](https://arxiv.org/abs/1809.10635) by Gido M. van de Ven, Andreas S. Tolias. arXiv, 2018
* [Overcoming catastrophic forgetting with hard attention to the task](https://arxiv.org/abs/1801.01423) by Joan Serrà, Dídac Surís, Marius Miron, Alexandros Karatzoglou. ICML, 2018
* [Deep Generative Dual Memory Network for Continual Learning](https://arxiv.org/abs/1710.10368) by Nitin Kamra, Umang Gupta, Yan Liu. arXiv, 2017
* [Learning to Learn without Forgetting By Maximizing Transfer and Minimizing Interference](https://arxiv.org/abs/1810.11910) by Matthew Riemer, Ignacio Cases, Robert Ajemian, Miao Liu, Irina Rish, Yuhai Tu, Gerald Tesauro. arXiv, 2018.
* [Lifelong Learning via Progressive Distillation and Retrospection](http://mmlab.ie.cuhk.edu.hk/projects/lifelong/res/0833.pdf) by Saihui Hou, Xinyu Pan, Chen Change Loy, Zilei Wang, Dahua Lin. ECCV, 2018. 
* [Few-Shot Self Reminder to Overcome Catastrophic Forgetting](https://arxiv.org/abs/1812.00543) by Junfeng Wen, Yanshuai Cao, Ruitong Huang. NIPS, 2018.
* [Reinforced Continual Learning](https://arxiv.org/abs/1805.12369) by Ju Xu, Zhanxing Zhu. NIPS, 2018.




<a name="myfootnote1">1</a>: (Template borrowed from [Lantao Yu](https://github.com/LantaoYu/MARL-Papers#framework))

