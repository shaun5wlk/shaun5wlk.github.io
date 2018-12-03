---
layout:post
title:"How do we understand Information Bottleneck?"
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
eliminate the redundant information in the same time.As is writen in the following:

\begin{equation}
MI(X,T) -\beta * MI(T,Y)
\label{eq:infromation bottleneck}
\end{equation}

where MI is mutual information of the variables and $\beta$ is the tradeoff parameter used to balance of the information saved by representation T.
