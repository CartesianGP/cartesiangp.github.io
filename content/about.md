---
title: "About"
date: 2023-03-24T11:35:15+01:00
lastmod: 2023-03-24T11:35:15+01:00
menu: "main"
weight: 30

# you can close something for this content if you open it in config.toml.
comment: false
mathjax: false
---

Genetic Programming is concerned with the automatic evolution (as in Darwinian evolution) of computational structures (such as mathematical equations, computer programs, digital circuits, etc.). John Koza pioneered a form of GP that uses a tree representation of computer programs. This was inspired by the artificial intelligence computer language, LISP.

# CARTESIAN GENETIC PROGRAMMING (CGP)

CGP is a highly efficient and flexible form of Genetic Programming that encodes a graph representation of a computer program.

It was invented by Julian Miller in 1999 and was developed from a representation of electronic circuits devised by Julian Miller and Peter Thomson developed a few years earlier. 

CGP represents computational structures (mathematical equations, circuits, computer programs etc) as a string of integers. These integers, known as genes determine the functions of nodes in the graph, the connections between nodes, the connections to inputs and the locations in the graph where outputs are taken from. 

Using a graph representation is very flexible as many computational structures can be represented as graphs. A good example of this is artificial neural networks (ANNs). These can be easily encoded in CGP. Recent published results of Khan and Miller and Turner and Miller(see the Julian Miller menu above) show that using CGP to encode and evolve ANNs (CGPANNs) is highly efficient and very competitive with other methods of evolving ANNs. Here is a ten-slide introduction to CGP.
Chapters 1 and 2 of Julian Miller's edited book are available from the link below:chapter1-and-2-CGP-book.pdf