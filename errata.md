# Errata for *Neural Networks and Deep Learning: A Textbook*

**Date**: September 1, 2020

## 1. An Introduction to Neural Networks

- Page 5, 1st paragraph, 4th row - $\mathbf{X} = [x_1, \ldots x_d]$ should be
$\mathbf{X} = [x_1 \ldots x_d]$

- Page 32, 1st paragraph in subsection *1.5.1 The Importance of Nonlinear Activation*, 4th row - "There are two instances, A and B, ..." should be "There are two instances, A and **C**, ..."

## 2. Machine Learning with Shallow Neural Networks

## 3. Training Deep Neural Networks

## 4. Teaching Deep Learners to Generalize

## 5. Radial Basis Function Networks

## 6. Restricted Boltzmann Machines

- Page 237, 3rd paragraph, 2nd to last row before Eq. 6.1, - $\mathbf{s} =
(s_1, \ldots s_d)$ should be $\mathbf{s} = (s_1 \ldots s_d)$
- Page 243, Eq. 6.7, - $P(s_i = 1 | s_1, \ldots, s_{i-1},s_{i+1}, s_q)$ should
be $P(s_i = 1 | s_1, \ldots, s_q)$
- Page 244, derivation of $P(s_i = 1 | s_1, \ldots, s_{i-1},s_{i+1}, s_q)$ -
$P(s_i = 1 | s_1, \ldots, s_{i-1},s_{i+1}, s_q)$ should be $P(s_i = 1 | s_1, \ldots, s_q)$
- Page 244, section *6.3.1 How a Boltzmann Machine Generates Data*, 1st
paragraph, sentence in 6th row starts with "The notion of thermal equilibrium
means ..." but fails to explain what thermal equilibrium is. From a short
correspondence with the autor that sentence can be replaced with "The notion of
thermal equilibrium means that the observed frequencies of sampling
various attribute values represent their long-term steady-state probability
distributions."
- Page 244, section *6.3.1 How a Boltzmann Machine Generates Data*, 1st
paragraph, 5th row from the bottom - $P(s_i = 1 | s_1 \ldots s_{i-1},s_{i+1}, \ldots s_q)$
should be $P(s_i = 1 | s_1, \ldots, s_q)$
- Page 248, 5th row after Eq. 6.15 - "... variables and only the **hidden** variables." should
be "... variables and only the **visible** variables."

## 7. Recurrent Neural Networks

## 8. Convolutional Neural Networks

## 9. Deep Reinforcement Learning

## 10. Advanced Topics in Deep Learning