# NeuroMatch Academy (NMA) syllabus

*July 13-31, 2020*

**Objectives**: Introduce traditional and emerging computational neuroscience tools, their complementarity, and what they can tell us about the brain. A main focus is on modeling choices, model creation, model evaluation and understanding how they relate to biological questions.

**Tutorial microstructure**: ~5min talk, ~15min hands-on (repeated)

**Day structure**: Opening keynote, 2.5h lecture/tutorial modules, 1/2h group discussion, 1h interpretation lecture + live Q&As (what did we learn today, what does it mean, underlying philosophy). There will also be many networking activities!

**Note for visitors from China**: This repository contains many links to YouTube and Google Colab. We have a version of the repository with those same videos posted on bilibili, and the Google Colab links replaced with links to Aliyun. Please visit the [China Accessible Neuromatch Course-Content](https://github.com/erlichlab/course-content/)

**Prerequisites**: [See here](https://github.com/NeuromatchAcademy/precourse)

# Course outline
 
- [NeuroMatch Academy (NMA) syllabus](#neuromatch-academy-nma-syllabus)
- [Course outline](#course-outline)
  - [Week 1](#week-1)
    - [Mon, July 13: Model Types](#mon-july-13-model-types)
    - [Tue, July 14: Modeling Practice](#tue-july-14-modeling-practice)
    - [Wed, July 15: Model fitting](#wed-july-15-model-fitting)
    - [Thu, July 16: Machine Learning](#thu-july-16-machine-learning)
    - [Fri, July 17: Dimensionality Reduction](#fri-july-17-dimensionality-reduction)
    - [Sat/Sun, July 18/19: Professional development & Social](#satsun-july-1819-professional-development--social)
  - [Week 2](#week-2)
    - [Mon, July 20: Bayesian Statistics](#mon-july-20-bayesian-statistics)
    - [Tue, July 21: Linear Systems](#tue-july-21-linear-systems)
    - [Wed, July 22: Decision Making](#wed-july-22-decision-making)
    - [Thu, July 23: Optimal Control](#thu-july-23-optimal-control)
    - [Fri, July 24: Reinforcement Learning](#fri-july-24-reinforcement-learning)
    - [Sat/Sun, July 24/25: Professional development & Social](#satsun-july-2425-professional-development--social)
  - [Week 3](#week-3)
    - [Mon, July 27: Real Neurons](#mon-july-27-real-neurons)
    - [Tue, July 28: Dynamic Networks](#tue-july-28-dynamic-networks)
    - [Wed, July 29: Network Causality](#wed-july-29-network-causality)
    - [Thu, July 30: Deep learning 1](#thu-july-30-deep-learning-1)
    - [Fri, July 31: Deep learning 2](#fri-july-31-deep-learning-2)
  - [Networking (throughout) - interactive track only](#networking-throughout---interactive-track-only)
  - [Group projects (throughout) - interactive track only](#group-projects-throughout---interactive-track-only)

----

## Week 1

### Mon, July 13: Model Types

**Description** Introduce different example model types (Marr 1-3, what/how/why) and the kinds of questions they can answer. Realize how different models map onto different datasets.

|    Time (Hour)   |    Lecture                            |    Details                                                            |
|------------------|---------------------------------------|-----------------------------------------------------------------------|
|    0:00-0:30\*   |    Intro / keynote & tutorial setup   |    Model classifications                                              |
|    0:30-0:45     |    Pod Q&A                            |    Lecture discussion with pod TA                                     |
|    0:50-2:05     |    Tutorials 1 & 2 + nano-lectures    |    "What"/"How" models                                                |
|    2:05-2:25     |    Discussion 1                       |    Discussion with pod TA                                             |
|    2:25-3:25     |    Big break                          |    BREAK                                                              |
|    3:25-4:40     |    Tutorials 3 + nano-lectures        |    "Why" model & discussion                                           |
|    4:40-5:00     |    Discussion 2                       |    Discussion with pod TA                                             |
|    5:05-5:35     |    Outro                              |    Recap session, The role of models in discovery                     |
|    5:35-6:00     |    Q&A                                |    Q&A with lecturers/Mentors                                         |

\* the Intro / keynote will be watched asynchronously, which means that you can watch this lecture before the start of the day

----

### Tue, July 14: Modeling Practice

**Description** Introduction to the process of building models.

|    Time (Hour)   |    Lecture                            |    Details                                                            |
|------------------|---------------------------------------|-----------------------------------------------------------------------|
|    0:00-0:30\*   |    Intro / keynote & tutorial setup   |    How to approach modeling                                           |
|    0:30-0:45     |    Pod Q&A                            |    Lecture discussion with pod TA                                     |
|    0:50-2:05     |    Tutorial 1 + nano-lectures         |    Framing the question                                               |
|    2:05-2:25     |    Discussion 1                       |    Discussion with pod TA                                             |
|    2:25-3:25     |    Big break                          |    BREAK                                                              |
|    3:25-4:40     |    Tutorial 2 + nano-lectures         |    Model implementation and testing                                   |
|    4:40-5:00     |    Discussion 2                       |    Discussion with pod TA                                             |
|    5:05-5:35     |    Outro                              |    Recap session, the modeling process                                |
|    5:35-6:00     |    Q&A                                |    Q&A with lecturers/Mentors                                         |

\* the Intro / keynote will be watched asynchronously, which means that you can watch this lecture before the start of the day

----

### Wed, July 15: Model fitting

**Description** Fit models to data, quantify uncertainty, compare models

| Time (Hour) | Lecture                          | Details                                                            |
|-------------|----------------------------------|--------------------------------------------------------------------|
|   0:00-0:30\*| Intro / keynote & tutorial setup | Why and how to fit models                                          |
|   0:30-0:45 | Pod Q&A                          | Lecture discussion with pod TA                                     |
|   0:50-2:05 | Tutorials 1 & 2 + nano-lectures  | Fit a model 1 (linear regression), Get error bars                  |
|   2:05-2:25 | Discussion 1                     | Discussion with pod TA                                             |
|   2:25-3:25 | Big break                        | BREAK                                                              |
|   3:25-4:40 | Tutorials 3 & 4 + nano-lectures  | Compare models, cross-validation, hyperparameters, Fit a model 2  (nonlinear models) |
|   4:40-5:00 | Discussion 2                     | Discussion with pod TA                                             |
|   5:05-5:35 | Outro                            | Recap session, Critical evaluation of model fitting                |
|   5:35-6:00 | Q&A                              | Q&A with lecturers/Mentors                                         |

\* the Intro / keynote will be watched asynchronously, which means that you can watch this lecture before the start of the day

----

### Thu, July 16: Machine Learning

**Description** Introduction to machine learning. The commonly used approaches, how to avoid false positives, how to do it well

| Time (Hour) | Lecture                          | Details                                                            |
|-------------|----------------------------------|--------------------------------------------------------------------|
|   0:00-0:30\*| Intro / keynote & tutorial setup | We want to predict ([scikit learn](https://scikit-learn.org/))     |
|   0:30-0:45 | Pod Q&A                          | Lecture discussion with pod TA                                     |
|   0:50-2:05 | Tutorials 1 & 2 + nano-lectures  | Introduction to GLMs and regularization                            |
|   2:05-2:25 | Discussion 1                     | Discussion with pod TA                                             |
|   2:25-3:25 | Big break                        | BREAK                                                              |
|   3:25-4:40 | Tutorials 3 & 4 + nano-lectures  | GLMs for encoding and decoding                                     |
|   4:40-5:00 | Discussion 2                     | Discussion with pod TA                                             |
|   5:05-5:35 | Outro                            | Recap session, Promises and pitfalls of ML for Neuroscience        |
|   5:35-6:00 | Q&A                              | Q&A with lecturers/Mentors                                         |

\* the Intro / keynote will be watched asynchronously, which means that you can watch this lecture before the start of the day

---- 

### Fri, July 17: Dimensionality Reduction

**Description** Concept of dimensionality reduction, ways of doing it, what it means

|    Time (Hour)   |    Lecture                            |    Details                                                            |
|------------------|---------------------------------------|-----------------------------------------------------------------------|
|    0:00-0:30\*   |    Intro / keynote & tutorial setup   |    Manifolds to understand                                            |
|    0:30-0:45     |    Pod Q&A                            |    Lecture discussion with pod TA                                     |
|    0:50-2:05     |    Tutorials 1 & 2 + nano-lectures    |    PCA 1 (orthonormal basis), PCA 2 (eigenvalues)                                     |
|    2:05-2:25     |    Discussion 1                       |    Discussion with pod TA                                             |
|    2:25-3:25     |    Big break                          |    BREAK                                                              |
|    3:25-4:40     |    Tutorials 3 & 4 + nano-lectures    |    MNIST with PCA, MNIST with t-SNE |
|    4:40-5:00     |    Discussion 2                       |    Discussion with pod TA                                             |
|    5:05-5:35     |    Outro                              |    Recap session, The link between high-dimensional brain signals and low-dimensional behavior |
|    5:35-6:00     |    Q&A                                |    Q&A with lecturers/Mentors                                         |

\* the Intro / keynote will be watched asynchronously, which means that you can watch this lecture before the start of the day

---- 

### Sat/Sun, July 18/19: Professional development & Social 

**Description** Professional development sessions and social activities will be offered on the weekend. More information, including exact times TBA

----
----

## Week 2

### Mon, July 20: Bayesian Statistics

**Description** Bayesian statistics, modeling of behavior, modeling of neural data, quantifying information

| Time (Hour) | Lecture                          | Details                                                            |
|-------------|----------------------------------|--------------------------------------------------------------------|
|   0:00-0:30*| Intro / keynote & tutorial setup | Uncertainty                                                        |
|   0:30-0:45 | Pod Q&A                          | Lecture discussion with pod TA                                     |
|   0:50-2:05 | Tutorials 1 & 2 + nano-lectures  | Bayes rule: cue combination and marginalization                    |
|   2:05-2:25 | Discussion 1                     | Discussion with pod TA                                             |
|   2:25-3:25 | Big break                        | BREAK                                                              |
|   3:25-4:40 | Tutorials 3 & 4 + nano-lectures  | Bayesian Decision Theory & Causal inference                        |
|   4:40-5:00 | Discussion 2                     | Discussion with pod TA                                             |
|   5:05-5:35 | Outro                            | Recap session, Advanced Bayesian methods                           |
|   5:35-6:00 | Q&A                              | Q&A with lecturers/Mentors                                         |

\* the Intro / keynote will be watched asynchronously, which means that you can watch this lecture before the start of the day

---- 

### Tue, July 21: Linear Systems

**Description** How to make estimates over time, how the brain does it

| Time (Hour) | Lecture                          | Details                                                            |
|-------------|----------------------------------|--------------------------------------------------------------------|
|   0:00-0:30*| Intro / keynote & tutorial setup | World has time                                                     |
|   0:30-0:45 | Pod Q&A                          | Lecture discussion with pod TA                                     |
|   0:50-2:05 | Tutorials 1 & 2 + nano-lectures  | Linear systems theory I (ND deterministic) and Markov process      |
|   2:05-2:25 | Discussion 1                     | Discussion with pod TA                                             |
|   2:25-3:25 | Big break                        | BREAK                                                              |
|   3:25-4:40 | Tutorials 3 & 4 + nano-lectures  | Linear systems theory II (1D stochastic = OU process; ND stocastic = AR(1)) and State space model |
|   4:40-5:00 | Discussion 2                     | Discussion with pod TA                                             |
|   5:05-5:35 | Outro                            | Recap session, Linear systems rule the world                       |
|   5:35-6:00 | Q&A                              | Q&A with lecturers/Mentors                                         |

\* the Intro / keynote will be watched asynchronously, which means that you can watch this lecture before the start of the day

---- 

### Wed, July 22: Decision Making

**Description** How we can make decisions when information comes in over time

| Time (Hour) | Lecture                          | Details                                                            |
|-------------|----------------------------------|--------------------------------------------------------------------|
| 0:00 - 0:30*| Intro / keynote & tutorial setup | We need to decide stuff                                            |
| 0:30 - 0:45 | Pod Q&A                          | Lecture discussion with pod TA                                     |
| 0:50 - 2:05 | Tutorials 1 & 2 + nano-lectures  | Information theory, Sequential Probability Ratio Test (SPRT)       |
| 2:05 - 2:25 | Discussion 1                     | Discussion with pod TA                                             |
| 2:25 - 3:25 | Big break                        | BREAK                                                              |
| 3:25 - 4:40 | Tutorials 3 & 4 + nano-lectures  | Hidden Markov Model inference (DDM), Kalman filter                 |
| 4:40 - 5:00 | Discussion 2                     | Discussion with pod TA                                             |
| 5:05 - 5:35 | Outro                            | Recap session, Decisions, decisions, decisions ...                 |
| 5:35 - 6:00 | Q&A                              | Q&A with lecturers/Mentors                                         |

\* the Intro / keynote will be watched asynchronously, which means that you can watch this lecture before the start of the day

---- 

### Thu, July 23: Optimal Control

**Description** We need to move gain info and reach goals

| Time (Hour) | Lecture                          | Details                                                            |
|-------------|----------------------------------|--------------------------------------------------------------------|
| 0:00 - 0:30*| Intro / keynote & tutorial setup | We want to control our actions...                                  |
| 0:30 - 0:45 | Pod Q&A                          | Lecture discussion with pod TA                                     |
| 0:50 - 2:05 | Tutorials 1 & 2 + nano-lectures  | Expected utility / Cost, Markov decision process (MDP)             |
| 2:05 - 2:25 | Discussion 1                     | Discussion with pod TA                                             |
| 2:25 - 3:25 | Big break                        | BREAK                                                              |
| 3:25 - 4:40 | Tutorials 3 & 4 + nano-lectures  | LQG control (MDP for linear systems), Motor control (signal-dependent noise, time cost, ...) |
| 4:40 - 5:00 | Discussion 2                     | Discussion with pod TA                                             |
| 5:05 - 5:35 | Outro                            | Recap session, Advanced motor control                              |
| 5:35 - 6:00 | Q&A                              | Q&A with lecturers/Mentors                                         |

\* the Intro / keynote will be watched asynchronously, which means that you can watch this lecture before the start of the day

---- 

### Fri, July 24: Reinforcement Learning

**Description** The setting of reinforcement learning and how it approximates the real world, behavior, and potential brain implementations

| Time (Hour) | Lecture                          | Details                                                            |
|-------------|----------------------------------|--------------------------------------------------------------------|
| 0:00 - 0:30*| Intro / keynote & tutorial setup | Problem formulations: actor-critic                                 |
| 0:30 - 0:45 | Pod Q&A                          | Lecture discussion with pod TA                                     |
| 0:50 - 2:05 | Tutorials 1 & 2 + nano-lectures  | Critic: reward prediction error, Exploration (POMDP) vs exploitation |
| 2:05 - 2:25 | Discussion 1                     | Discussion with pod TA                                             |
| 2:25 - 3:25 | Big break                        | BREAK                                                              |
| 3:25 - 4:40 | Tutorials 3 & 4 + nano-lectures  | Model-based vs model-free RL, Multi-arm bandits: foraging          |
| 4:40 - 5:00 | Discussion 2                     | Discussion with pod TA                                             |
| 5:05 - 5:35 | Outro                            | Recap session, RL and the brain                                    |
| 5:35 - 6:00 | Q&A                              | Q&A with lecturers/Mentors                                         |

\* the Intro / keynote will be watched asynchronously, which means that you can watch this lecture before the start of the day

----

### Sat/Sun, July 24/25: Professional development & Social 

**Description** Professional development sessions and social activities will be offered on the weekend. More information, including exact times TBA

----
----

## Week 3

### Mon, July 27: Real Neurons

**Description** The things neurons are made of, channels, morphologies, neuromodulators, and plasticity

| Time (Hour) | Lecture                          | Details                                                            |
|-------------|----------------------------------|--------------------------------------------------------------------|
| 0:00 - 0:30*| Intro / keynote & tutorial setup | Real neurons ftw                                                   |
| 0:30 - 0:45 | Pod Q&A                          | Lecture discussion with pod TA                                     |
| 0:50 - 2:05 | Tutorials 1 & 2 + nano-lectures  | Reduced neuron models and transfer of synchrony                    |
| 2:05 - 2:25 | Discussion 1                     | Discussion with pod TA                                             |
| 2:25 - 3:25 | Big break                        | BREAK                                                              |
| 3:25 - 4:40 | Tutorials 3 & 4 + nano-lectures  | Short-term plasticity of synapses and Hebbian plasticity & STDP    |
| 4:40 - 5:00 | Discussion 2                     | Discussion with pod TA                                             |
| 5:05 - 5:35 | Outro                            | Recap session, A variety of neuron models                          |
| 5:35 - 6:00 | Q&A                              | Q&A with lecturers/Mentors                                         |

\* the Intro / keynote will be watched asynchronously, which means that you can watch this lecture before the start of the day

---- 

### Tue, July 28: Dynamic Networks

**Description** How single neurons create population dynamics

| Time (Hour) | Lecture                          | Details                                                            |
|-------------|----------------------------------|--------------------------------------------------------------------|
| 0:00 - 0:30*| Intro / keynote & tutorial setup | Mechanistic models of different types of brain actvivity           |
| 0:30 - 0:45 | Pod Q&A                          | Lecture discussion with pod TA                                     |
| 0:50 - 2:05 | Tutorials 1 & 2 + nano-lectures  | 2D dynamical systems, Wilson-Cowen model (coarse-grained), oscillations & synchrony |
| 2:05 - 2:25 | Discussion 1                     | Discussion with pod TA                                             |
| 2:25 - 3:25 | Big break                        | BREAK                                                              |
| 3:25 - 4:40 | Tutorials 3 & 4 + nano-lectures  | Attractors & local linearization around fixed points, Balanced Amplification & Inhibition-stabilized network |
| 4:40 - 5:00 | Discussion 2                     | Discussion with pod TA                                             |
| 5:05 - 5:35 | Outro                            | Recap session, A theory of the whole brain                         |
| 5:35 - 6:00 | Q&A                              | Q&A with lecturers/Mentors                                         |

\* the Intro / keynote will be watched asynchronously, which means that you can watch this lecture before the start of the day

---- 

### Wed, July 29: Network Causality

**Description** Ways of discovering causal relations, ways of estimating networks, what we can do with networks

| Time (Hour) | Lecture                          | Details                                                            |
|-------------|----------------------------------|--------------------------------------------------------------------|
| 0:00 - 0:30*| Intro / keynote & tutorial setup | Causality - different views                                        |
| 0:30 - 0:45 | Pod Q&A                          | Lecture discussion with pod TA                                     |
| 0:50 - 2:05 | Tutorials 1 & 2 + nano-lectures  | Pittfalls of Granger and Centrality                                |
| 2:05 - 2:25 | Discussion 1                     | Discussion with pod TA                                             |
| 2:25 - 3:25 | Big break                        | BREAK                                                              |
| 3:25 - 4:40 | Tutorials 3 & 4 + nano-lectures  | Instrumental Variables and interventions                           |
| 4:40 - 5:00 | Discussion 2                     | Discussion with pod TA                                             |
| 5:05 - 5:35 | Outro                            | Recap session, Ladders of causality                                |
| 5:35 - 6:00 | Q&A                              | Q&A with lecturers/Mentors                                         |

\* the Intro / keynote will be watched asynchronously, which means that you can watch this lecture before the start of the day

---- 

### Thu, July 30: Deep learning 1

**Description** The concept of ANNs, how to train them,what they are made out of, convnets, and how to fit them to brains

| Time (Hour) | Lecture                          | Details                                                            |
|-------------|----------------------------------|--------------------------------------------------------------------|
| 0:00 - 0:30*| Intro / keynote & tutorial setup | DL = crucial tool                                                  |
| 0:30 - 0:45 | Pod Q&A                          | Lecture discussion with pod TA                                     |
| 0:50 - 2:05 | Tutorials 1 & 2 + nano-lectures  | Pytorch intro & model components, Training it & inductive bias     |
| 2:05 - 2:25 | Discussion 1                     | Discussion with pod TA                                             |
| 2:25 - 3:25 | Big break                        | BREAK                                                              |
| 3:25 - 4:40 | Tutorials 3 & 4 + nano-lectures  | Convolutional Neural Network, Fit to brain (RSA - represenatational similarity analysis) |
| 4:40 - 5:00 | Discussion 2                     | Discussion with pod TA                                             |
| 5:05 - 5:35 | Outro                            | Recap session, Digging deep                                        |
| 5:35 - 6:00 | Q&A                              | Q&A with lecturers/Mentors                                         |

\* the Intro / keynote will be watched asynchronously, which means that you can watch this lecture before the start of the day

---- 

### Fri, July 31: Deep learning 2

**Description** Deep learning in more advanced settings. Autoencoders for structure discovery, RNNs, and fitting them to brains

| Time (Hour) | Lecture                          | Details                                                            |
|-------------|----------------------------------|--------------------------------------------------------------------|
| 0:00 - 0:30*| Intro / keynote & tutorial setup | DL for structure                                                   |
| 0:30 - 0:45 | Pod Q&A                          | Lecture discussion with pod TA                                     |
| 0:50 - 2:05 | Tutorials 1 & 2 + nano-lectures  | Variational autoencorders and uses in Neuroscience                 |
| 2:05 - 2:25 | Discussion 1                     | Discussion with pod TA                                             |
| 2:25 - 3:25 | Big break                        | BREAK                                                              |
| 3:25 - 4:40 | Tutorials 3 & 4 + nano-lectures  | NMA wrap-up                      |
| 4:40 - 5:00 | Discussion 2                     | Discussion with pod TA                                             |
| 5:05 - 5:35 | Outro                            | Recap session, Digging deeper                                      |
| 5:35 - 6:00 | Q&A                              | Q&A with lecturers/Mentors                                         |

\* the Intro / keynote will be watched asynchronously, which means that you can watch this lecture before the start of the day

----


## Networking (throughout) - interactive track only

* Meet a prof about your group's project
* Meet a prof about your career
* Meet a prof about your own project
* Meet other participants interested in similar topics
* Meet a group of likeminded people
* Meet people that are local to you (same city, country)

----


## Group projects (throughout) - interactive track only

TBA

----

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work and everything in this repo is licensed under a [Creative Commons Attribution 4.0 International
License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
