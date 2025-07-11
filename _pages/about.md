---
layout: about
title: about
permalink: /
subtitle: suic20@mails.tsinghua.edu.cn.

profile:
  align: right
  image: my_pic.jpg
  image_circular: false # crops the image to make it circular
  address: >
    <p>Tsinghua University, Beijing, China</p>

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---
**This website is still under construction.**

I am a graduate student in the Department of Astronomy at Tsinghua University, China, since 2020, working under the supervision of [Prof. Yi Mao](http://i.astro.tsinghua.edu.cn/~ymao/members/). I am currently visiting Johns Hopkins University, where I am co-supervised by [Prof. Ben Wandelt](https://benwandelt.org/).

### Research

My primary research interests lie at the intersection of machine learning, statistical methods, and astronomy. I focus on leveraging techniques such as simulation-based inference, information theory, and generative models to tackle key data challenges in cosmology.

A major theme of my work is the application of information-theoretic approaches to cosmological inference. I have explored how mutual information and related metrics can guide the design of summary statistics and improve the interpretability and efficiency of inference pipelines:

* [**Quantifying Information Content**](https://arxiv.org/abs/2307.04994): Demonstrates how mutual information can be used to select optimal summary statistics for cosmological inference.
* [**Extracting Complementary Information**](https://arxiv.org/abs/2410.07548): Extends the previous work by showing how to learn new summaries that are complementary to existing ones—enhancing both informativeness and interpretability.
* [**Learning Local information**](https://arxiv.org/abs/2507.07833): Introduces a novel approach that uses score matching to learn the Fisher score of arbitrary models, enabling accurate Fisher forecasts without relying on explicit likelihoods.

More recently, I’ve been exploring forward modeling techniques for cosmological analysis. One example is:

* [**Symbolic Emulator for Matter Spectrum**](https://arxiv.org/abs/2410.14623): Uses symbolic regression to construct accurate, interpretable, and efficient emulators for the linear and nonlinear matter power spectra.

These efforts are closely tied to simulation-based inference and cosmological modeling. I'm also involved in several collaborative projects where we apply these methods to real or realistic data:

* [**Galaxy Clustering**](https://github.com/maho3/ltu-cmass) :  As part of the [learing the Universe Collaboration](https://learning-the-universe.org/), I work on forward modeling galaxy clustering from the BOSS survey and performing inference across multiple simulations.
* [**21cm Signal**](https://github.com/suicee/21cmPipeline) : During the early years of my PhD, I focused on inference from 21cm cosmology. Although I did not publish in this area, I recently led a team in the [SKA-Data-Chanllenge](https://sdc3.skao.int/challenges/inference), developing a full forward and inference pipeline that performed well in the competition
* [**Galaxy Spectra**](https://github.com/suicee/spec_sbi): I am currently working on applying simulation-based inference to galaxy spectra, with the aim of developing robust methods that can handle observational effects.

In addition to research, I organized the Data Science Group at THU-DOA from 2021 to 2023, where we explored a range of topics related to machine learning and astrophysics. Some of this work is available in our [repo](https://github.com/ZechangSun/THU-DoA-DATA-SCIENCE).

My future research will focus primarily on two directions:

* **Exploring information theory and metrics** : I remain deeply interested in the concept of information—it provides a powerful, quantitative way to formalize our intuitions and understanding of data. I believe information-theoretic tools can offer valuable insights across many aspects of cosmology. Additionally, their close connection to generative models opens up exciting possibilities that I plan to explore further.
* **Advancing forward modeling and addressing model misspecification** : As inference methods continue to improve, one of the key bottlenecks lies in the accuracy of the forward models. Inadequate or incorrect forward modeling can lead to significant biases in the results. I aim to work on improving these forward processes and developing methods that are robust to potential model misspecifications.

### Hobbies

I'm a passionate gamer with a love for both video games and card games. Beyond playing, I'm also interested in game development and have been learning Unity3D to create my own games. One day, I hope to build a "universe" of my own—one that I actually understand :)
