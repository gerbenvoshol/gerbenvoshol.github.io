---
layout: page
title: Projects
permalink: /projects/
---

### Hidden Markov Model

Single header file implementation of a discrete Hidden Markov Model (HMM) in C. The file includes basic HMM functions such as the forward, backward, Viterbi and Baum-Welch algorithm. Also included are the hmms used for transmembrane and signal peptide prediction. In the near future, I hope to write a set of short tutorials about using HMMs in the field of biology.

### Statistics Tool Box

Single header file with a bunch of useful statistical functions in C. Sometimes you need to do some simple statistics and you don't want to include a big library such as the GNU Scientific Library. Functions implemented include:
* T-Test
* Anova
* k-Sample Anderson Darling
* Chisqr (and G-Test)
* Liniear, Exponential, Polynomial curve fitting
* Multiple linear/logistic regression
* Matrix manipulations (was needed for multiple regression) such as transpose, inverse, multiply, etc.
* A very simple histogram
* and several more functions

Get it at [https://github.com/gerbenvoshol/Statistics-Tool-Box](https://github.com/gerbenvoshol/Statistics-Tool-Box)

### Self-Organizing Map

A self-organizing map, also called a SOM or Kohonen map, is a type of artificial neural network that is trained using unsupervised learning. This project uses a SOM to produce a two-dimensional representation of the relative synonymous codon usage of diverse microorganisms. This information can then be used to determine groups of similar genes (for example, high versus low expressed genes) and determine the likelihood that a gene is (in)correctly annotated, based on how well it fits the trained map.

### Genetic Algorithm and Artificial Neural Networks

Artifical neural network (ANN for short) have successfully been used in Biology for example for the prediction of signal peptides, 2d protein structures, transmembrane proteins, etc.. The design of a good artifical neural network (ANN for short) is usually done by experts and requires a good understanding of the underlying problem. When understanding of the underlying problem is missing, many topologies of the ANN can be attempted using a brute force approach (e.a. just try everything), but a more elegant approach is using a genetic algortithm to evolve the proper topology. This project uses such an approach to evolve a new ANN for the prediction of signal peptides.
