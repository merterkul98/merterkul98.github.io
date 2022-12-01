---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

Here, you can find the undergrad/grad projects that I completed, in a reverse chronological order. The ones that include reports are either 100% project courses, i.e. no exam, or were substantial in grade obtained for the course.

## Offline Reinforcement Learning for Efficient and Realizable Fertilization Policies
### ETH Zurich, Research in Data Science <img src="/images/eth_z_logo.png" height="50px" width="100px" align="right"/>

*Abstract:* Reinforcement learning (RL) has gained immense popularity among optimal planning problems, prescribing policies which yield better rewards than the status-quo policies. RL is inherently an online learning paradigm, where agents require numerous interactions with the environment. In high-risk tasks such as usage of nitrogen-based fertilizers, interacting with the environment can be expensive and detrimental. For tasks where records of transactions exist, and agent interaction is restricted, the notion of offline RL has emerged. In this study, we apply model-free offline RL algorithms to find near-optimal policies for fertilization using nitrogen. We show that offline RL strategies can easily surpass the existing expert policies, demonstrate the reward increase with larger state spaces, illustrate the policies that are prescribed by the trained agents, and compare them with the expert policies.

[Report](/files/projects/offlineRL_REPORT.pdf)

*Grade:* 6.0 / 6.0


## Italy v Spain Match Analysis, EURO 2020

### ETH Zurich, Soccer Analytics <img src="/images/eth_z_logo.png" height="50px" width="100px" align="right"/>

*Abstract:* In this project, we examined the EURO 2020 semi-final match Italy against Spain. Throughout the course, we saw various analysis techniques, regarding players' movement, passing, shooting, in-game and end-of-game match probabilities, set-pieces, player valuations, ratings and many more. Using these, we generated a match report based on the event data obtained from Statsbomb, and the tracking data obtained by the courtesy of UEFA.

[Report](/files/projects/49.html)

*Grade:* 6.0 / 6.0

## Probabilistic Artificial Intelligence Mini-Projects

### ETH Zurich, Probabilistic Artificial Intellifence <img src="/images/eth_z_logo.png" height="50px" width="100px" align="right"/>

We were assigned 4 different mini-projects throughout the semester. Concretely, our tasks were as follows:

1. Gaussian Process Regression to model air pollution and predict fine particle concentration at new coordinate locations.

2. Bayesian Neural Network implementation based on the ’Bayes by Backprop’ algorithm by Blundell et al. (2015). for multi-class classification on the MNIST dataset.

3. Implementation of Bayesian optimization under constraints to the feasible domain (2D grid), following Gelbart et al. (2014).

4. Lunar lander using Generalized Advantage Estimation technique, introduced in Schulman et al. (2016). Main task was to implement a model-free policy gradient based Actor-Critic algorithm.

*Grade:* 6.0 / 6.0

## Word-Level Adversarial Defense Layer for Robust Natural Language Classification

### ETH Zurich, Deep Learning <img src="/images/eth_z_logo.png" height="50px" width="100px" align="right"/>

*Abstract:* Deep Neural Networks (DNNs) are frequently used in NLP for various tasks, such as classification and machine translation. However, recent results show that they are prone to adversarial attacks. Typically, defense strategies against the attacks either augment the training dataset, modify the word embeddings or use model-dependent algorithms. In this study, we propose a computationally efficient, model and attack agnostic algorithm called Word-Level Adversarial Defense Layer (WLADL). For comparison, we applied the vanilla adversarial training (VAT) strategy (augmenting the dataset with successful adversarial examples), and the Synonym Encoding Method (SEM) to generate new word embeddings. We evaluate the defense strategies through their clean test results, alterations in the accuracies and adversarial query counts compared to non-defended models when attacked. Our experiments demonstrate that, when compared with VAT and SEM, WLADL shows competitive performance, while being a transferable algorithm that does not require any pre-computations. 

[Report](/files/projects/wladl.pdf)

*Grade:* 6.0 / 6.0

## Advanced Machine Learning Projects

### ETH Zurich, Advanced Machine Learning <img src="/images/eth_z_logo.png" height="50px" width="100px" align="right"/>

Similar to the _Probabilistic Artificial Intelligence_ course, we were assigned 4 Kaggle-type projects to compete with others in a leaderboard based on a metric. Assigned projects were as follows:

1. The first task was to predict a person's age from the brain image data: a standard regression problem.

2. The problem was a classification task. We had 5 classes but these were unbalanced with one to have a significantly higher number of samples.

3. Time-series classification on ECG signal diagnosing heart diseases (ACS vs TTS). Extracting features of the heartbeats by using an autoencoder, as well as features on the general time-series.

4. Final task was automatic sleep scoring using EEG/EMG data from 3 people, classifying sleep into deep, REM and awake. We extracted frequency features, and applied a bi-directional RNN decoder and a 1-D CNN as a feature extractor on the raw signals.

*Rankings:* 3rd, 2nd, 8th, 11th out of approx. 170 groups of 4 people.
*Total Grade:* 5.97 / 6.0

## BeeSMART

### Bilkent University, Industrial Design Project, EE 494 <img src="/images/bilkent_logo.png" height="50px" width="50px" align="right"/>

*Abstract:* This project aims to create an environment for beekeepers so that they can monitor the hive conditions and also try to predict the medical conditions of the bees by processing their sounds. The solution uses hardware components such as temperature, moisture, tilt, accelerometer, GPS, GSM and microphones for monitoring the hive conditions with addition to recording and processing sounds present in the hive and transferring them over GSM to a cloud server. After the sounds are processed with edge computing, the information are sent to beekeepers and other third-party users via a phone or web application. There are six milestones designated for this project, hardware design, embedded software design, machine learning algorithm design, Android Application design, Web Application design and Cloud-Application connection design. As a result, we have successfully acquired a fully functional hardware that is in connection to applications that notifies beekeepers and helps them correctly classify and monitor hive conditions so that they can plan their visitations more precisely and thus be more efficient in terms of honey production and collection overall.

[Report](/files/projects/report_ee494.pdf)

[Booklet](/files/projects/booklet.pdf)

*Grade:* 4.0 / 4.0

## Puzzle Generator

### Bilkent University, Artificial Intelligence, CS 461 <img src="/images/bilkent_logo.png" height="50px" width="50px" align="right"/>

*Description:* Built an AI-NLP hybrid project that generates daily puzzles similar to New York Times' Daily Mini, using their past puzzles as the training dataset and through generating new puzzles with new clues. 

*Grade:* 4.0 / 4.0

## Auto Caption Generator

### Bilkent University, Neural Networks, EE 443 <img src="/images/bilkent_logo.png" height="50px" width="50px" align="right"/>

*Description:* Completed an AI Auto-Caption Generator using Visual Attention and Transfer Learning, CNNs and LSTMs for sequential reasoning. As the accuracy metrics, chose Jaccard Similarity metrics and BLEU scores which compare sentences through their structures and meaning similarities. Obtained meaningful captions which were slightly different ground truth labels.

*Grade:* 4.0 / 4.0

## Self-Driving Car Challenge 2

### Bilkent University, Introduction to Machine Learning, CS 464 <img src="/images/bilkent_logo.png" height="50px" width="50px" align="right"/>

*Description:* Completed Udacity Self-Driving Car Challenge 2 with three different algorithms; Multi-Layer Perceptron, Convolutional Neural Networks and Transfer Learning. We obtained a root mean squared error of 3.02 Degrees per image. Best R value was found to be 90.2 percent using our own architecture with addition to ResNet-50 architecture using Transfer Learning method. 

*Grade:* 4.0 / 4.0

## Urination Monitor

### Bilkent University, Microprocessors, EE 212 <img src="/images/bilkent_logo.png" height="50px" width="50px" align="right"/>

*Description:* Built a Bluetooth connected urination monitor using FRDM board which was programmed in MBED KL25Z using C as the language. The built module included a 24x4 programmable graphic LCD that included the interface and the submodule had the HC04 Bluetooth module that was paired with the main-module as slave master connection with an additional urine sensor at the submodule. The interface included external ROM to save the data and an internal linear regressive mechanism to guess the next urinating time.

*Grade:* 4.0 / 4.0

## Speed Radar

### Bilkent University, Introduction to Digital Circuit Design, EE 102 <img src="/images/bilkent_logo.png" height="50px" width="50px" align="right"/>

*Description:* Programmed an FPGA board BASYS3 on Vivado IDE and used data exchange from two distance sensors to build a radar which measured a given object's velocity in terms of centimeters/second, displayed it on a 16x2 programmable LCD. [Video Link](https://www.youtube.com/watch?v=iopFCk1l58U)

*Grade:* 95 / 100
















