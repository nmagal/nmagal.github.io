## Portfolio

---

### Evaluation of Deep Music Features for Music Recommendation Systems
As the quantity of songs stored online increases, users are relying more on music recommendation systems to find new music, and the importance of music recommendation systems are increasing. Currently, one of the state of the art representation learning methods in Music Information Retrieval (MIR) is to use features obtained from Jukebox, a Transformer based model capable of generating audio. However, little work has been done in evalu- ating how Jukebox features perform compared to other features in context of music recommender systems. In this research, tests are run evaluating the effectiveness and semantic differences of different types of music features used for retrieving similar sounding songs in a simple content-based song recommendation system, with the goal of seeing how Jukebox features perform relative to other embedding methods.

<figure>
  <img src="images/rec_perf.png?raw=true"/>
  <figcaption> Figure: Average accuracy of different features across different levels of N top tracks.</figcaption>
</figure>



[View Repo Here](https://github.com/nmagal/deep_music_embeddings_for_rec_sys)

[View Paper Here](https://drive.google.com/file/d/1IcAgyNX-oLxC7kDvxPVWbWh5sM9bhdF3/view?usp=share_link)

---
### Modality Drop For Co-learning

We find that by using aggressive modality dropout we are able to reverse negative co-learning (NCL) to positive co-learning (PCL). Aggressive modality dropout can be used to ’prep’ a multimodal model for unimodal deployment, and dramatically increases model performance during negative co-learning, where during some experiments we saw a 20% gain in accuracy.

<figure>
  <img src="images/res_iemo.png?raw=true"/>
  <figcaption> Figure: Results for using different levels of modality dropout on IEMOCAP dataset</figcaption>
</figure>


[View Repo Here](https://github.com/nmagal/modality_drop_for_colearning)

[View Paper Here](https://drive.google.com/file/d/1eh_gAMi15dxSTqfn4n0RKp-PfGv-n00P/view?usp=share_link)

---
### Utterance to Phoneme Ablation Report

In this project various different model designs are evaluated on the objective of predicting phonemes given mel spectogram speech data. Model designs experimented on include using a Pyramidal LSTM design, Resnet blocks to embed speech data, variable data augmentation, and more.

<figure>
  <img src="images/W&B Chart 12_12_2022, 7_27_29 PM.png?raw=true"/>
  <figcaption> Figure: Results from using different model and hyperparamter configurations</figcaption>
</figure>

[View Notebook Here](https://github.com/nmagal/Assignments/blob/master/Intro%20to%20Deep%20Learning/pytorch/utterance_LSTMs/UtterancetoPhoneme.ipynb)

[View Report Here](https://drive.google.com/file/d/1SGtxrw3Toegvvvt5v63CBGdJLN68iB4d/view)

---
### Resnet34 Reimplementation

In this project I reimplement Resent34. Residual blocks are implemented, and the model is tested on both image classification and face verification. Face verification is performed by using the image pair distance of embeddings created by using Resnet34 trained on image classification.

[View Code Here](https://github.com/nmagal/Assignments/tree/master/Intro%20to%20Deep%20Learning/pytorch/resnet)

---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
