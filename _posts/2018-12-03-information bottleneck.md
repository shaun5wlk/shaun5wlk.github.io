---
layout: post
title: "How do we understand Information Bottleneck?"
subtitle: 'A good measure to evaluate your network'
author: "Zpl"
header-style: text
tags:
  - Representation Learning
  - Deep Learning
---
>Information Bottleneck is a good measure to evaluate the represenation extarcted by machine leaning algorithms in supervised tasks,which is proposed by Tishby in 1999.

### What is Information Bottleneck?
Information Bottleneck is a good measure to evaluate the represenation extarcted by machine leaning algorithms in supervised tasks,which is proposed by *Tishby* in 1999.In machine learning tasks,we want to extract a representation that save the information of input data as much as possible while
eliminate the redundant information in the same time.The idea can be writen as in the following:
<a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;\dpi{100}&space;I(X,T)&plus;\beta&space;I(T,Y)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;\dpi{100}&space;I(X,T)&plus;\beta&space;I(T,Y)" title="I(X,T)+\beta I(T,Y)" /></a>
where MI is mutual information of the variables and $\beta$ is the tradeoff parameter used to balance of the information saved by representation T.
