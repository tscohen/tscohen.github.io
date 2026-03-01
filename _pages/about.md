---
layout: about
title: about
permalink: /
subtitle: AI Research Scientist, <a href="https://ai.meta.com/">Meta / FAIR</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>taco.cohen@gmail.com</p>

news: false
selected_papers: true
social: true
---

Welcome! I'm Taco Cohen, AI research scientist at Meta / FAIR, interested in RL, LLMs, generative models, and equivariant networks.

Here is my [CV](https://tacocohen.wordpress.com/wp-content/uploads/2024/09/cv_taco_cohen.pdf) and [Google Scholar](https://scholar.google.com/citations?user=a3q4YxEAAAAJ&hl=en) page.

---

### Bio

Taco Cohen is an AI Research Scientist at Meta. He received a BSc in computer science from Utrecht University, and a MSc in AI and PhD in ML (with prof. Max Welling) from the University of Amsterdam (all three cum laude). During his PhD he developed and popularized equivariant networks and geometric deep learning. He was a co-founder of Scyfer, a company focussed on deep active learning, acquired by Qualcomm in 2017. At Qualcomm, he founded and led the generative models and data compression team. His current research is focused on code generation and reinforcement learning. During his studies he has interned at Google Deepmind (working with Geoff Hinton) and OpenAI. He received the 2014 University of Amsterdam MSc thesis prize, a Google PhD Fellowship, ICLR 2018 best paper award for "Spherical CNNs", was named one of 35 innovators under 35 by MIT Tech Review, and won the 2022 ELLIS PhD Award and 2022 Kees Schouhamer Immink prize for his PhD research.

---

### Research

**Equivariant Networks & Geometric Deep Learning**

During my PhD I developed the first [group equivariant convolutional networks](https://tacocohen.wordpress.com/wp-content/uploads/2016/06/gcnn.pdf) (G-CNNs) and several generalizations such as [Steerable CNNs](https://openreview.net/pdf?id=rJQKYt5ll), [Spherical CNNs](https://openreview.net/pdf?id=Hkbd5xZRb), and [Gauge Equivariant CNNs](https://arxiv.org/abs/1902.04615) on manifolds, as well as a [general theory](https://arxiv.org/abs/1811.02017) of equivariant convolutions. Equivariant networks leverage knowledge of the symmetries of a learning problem to improve data efficiency, and have been shown to enjoy better scaling behavior than non-equivariant methods in problems with symmetries. Symmetries can be found in many applications of machine learning, such as medical imaging, drug design, materials design, analysis of protein structure, global climate modeling, lattice gauge theory, cryo-electron microscopy, graph-structured data, combinatorial optimization, robotics, and many others. In recent years, the field of equivariant networks (also known as geometric deep learning) has blossomed into a very active area of research, with many researchers developing equivariant networks for use in these domains.

In my work I have tried to be systematic, developing a general class of network architectures, a theory, and an approach to modeling rather than a specific network architecture. The general theory of equivariant convolutional networks, described in Part II of my [PhD thesis](https://pure.uva.nl/ws/files/60770359/Thesis.pdf), covers a large class of neural network layers, which can be categorized by the base space on which the data live (e.g. images on the plane, sphere, a graph, or other spaces), the kind of geometric quantity attached to each point in the base space (e.g. scalars, vectors, tensors), and the group of symmetries (permutation, translation, rotation, scaling, etc.). By varying these, one obtains many of the methods that can be found in the literature on equivariant networks. The "convolution is all you need" theorem states that the most general (i.e. least restricted) equivariant linear map between feature spaces in this class is a generalized convolution.

Together with Michael Bronstein, Joan Bruna and Petar Veličković, we are writing a book on geometric deep learning that aims to make equivariant networks accessible to a general machine learning audience. An early draft and lecture course can be found [here](http://www.geometricdeeplearning.com).

**Generative models & data compression**

In 2019 I started the generative models & data compression team at Qualcomm, with the goal to apply the spectacular advances in deep generative modeling to the problem of image, video and speech compression. Generative models hold great potential for compression, not only because better probability models correspond to more efficient codes, but also because generative models have the unique capacity to *generate* details that are not coded in the bitstream. So whereas a classical video codec will produce artifacts such as blocking at low bitrates, a generative compression system can generate realistic looking textures. Together with the semantic understanding afforded by deep networks, this allows for fine-grained control over which areas to encode with high fidelity, and which ones to generate on the receiver side.

We published one of the first [neural video codecs](https://arxiv.org/abs/1908.05717), introduced various novel concepts such as [instance-adaptive compression](https://arxiv.org/abs/2101.08687), feedback-recurrent autoencoders for [speech](https://arxiv.org/abs/1911.04018) and [video](https://arxiv.org/abs/2004.04342) coding, and the first [transformer-based neural video codec](https://openreview.net/pdf?id=IDwN6xjHnK8). After several years of dedicated effort, our neural speech and video compression methods now significantly outperform classical codecs and run efficiently on low-power devices. Next-generation video coding standards will likely incorporate some of these advances.

**RL & LLMs**

I'm currently working on RL with LLMs for codegen and mathematics.

---

### Links

Twitter: [@TacoCohen](https://twitter.com/TacoCohen)
Google Scholar: [link](https://scholar.google.com/citations?user=a3q4YxEAAAAJ&hl=en)
Geometric Deep Learning Book & Video Lectures: [link](https://geometricdeeplearning.com/)
NeurIPS Tutorial on Equivariant Networks with Risi Kondor: [link](https://slideslive.com/38943570/equivariant-networks)
awesome-equivariant-network: [overview](https://github.com/Chen-Cai-OSU/awesome-equivariant-network) of papers & videos on equivariant networks
Article in [Quanta](https://www.quantamagazine.org/an-idea-from-physics-helps-ai-see-in-higher-dimensions-20200109/) / [Wired](https://www.wired.com/story/computers-are-learning-to-see-in-higher-dimensions/) (2020)
TWIML Podcast on [Natural Graph Networks](https://twimlai.com/natural-graph-networks-with-taco-cohen/) (2020)
