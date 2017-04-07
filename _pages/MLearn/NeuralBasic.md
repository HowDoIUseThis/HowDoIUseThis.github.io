---
layout: single
title: Neural Network Basics
permalink: /MLearn/NeuralBasic
author_profile: False
sidebar:
  title: Neural Networks
  nav: L2Neural
---
<html>
<script src='https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js?config=TeX-MML-AM_CHTML'></script>
<body>
<h2>Basic Structure</h2>
<p>In many ways the general premise of neural networks is conceptually trivial.
The most simple way to think about them is to treat them as any other mathematical function. If you
prefer a non-mathematical comparison, a black box that takes a vector as input and returns a different vector as an output is usually a good comparison.  
For every application of a neural network there will be a set of input data and a corresponding output. We have no knowledge of what is
happening inside of box, but generally we can image that the box is broken up in layers. Where each layer preforms
some form of operation on our input. The basic structure can be visualized as,</p>
$$\text{Input} \rightarrow \text{Layer 1} \rightarrow .... \text{Layer N} \rightarrow \text{Output}$$
<p>Each layer can be composed of an arbitrary number of "neurons" or <b>nodes</b> that are connected to every element in the previous layer. As more layers are added the structure begins to resemble a network of neurons, hence the name Neural Network. It is important to note that each node in a layer is completely independent of all other nodes occupying the same layer. This basic layout can be seen below.</p>
<img src="/assets/images/basicNetwork.png" alt="Network" width="720" height="540">

<h2>Actions and Weights</h2>
<p>With a basic understanding of the overlying structure we can now begin to explore the function of our layers. If we examine a single node from a layer we would see that our node takes n number of inputs and spits out a single number as an output. This output is then fed to n nodes in the next layer and this continues until the output is reached. So in this example we have each layer of our network  preforms some form of mathematical operation on the data provided by the previous layer. Some might refer to process the node undertakes as an <b>action</b>. A simple example of an action would be to have each node scale each previous n values and output their sum. The number used to scale each entry is refereed to as a <b>weight</b>.

</p>

</body>
</html>
