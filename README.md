# Renormalization
The repository contains my final project for IL181.008 - Renormalization in Complex Systems. 

In this project, I refute empirically the claim of Mehta &amp; Schwab (2014) that deep learning inherently conducts renormalization hence achieving its phenomenal performance.

As opposed to the results presented by Mehta & Schwab, my result (shown below) shows random couplings of cells in the Ising model rather than the expected block coupling, which according to the authors, would prove that deep learning makes physically meaningful renormalization. 

<img width="840" alt="Screen Shot 2020-02-21 at 1 00 09 AM" src="https://user-images.githubusercontent.com/20875827/75019951-a1f73c80-5446-11ea-9f10-9c81b41f13a7.png">

This difference boils down to the authors' use of L1 regularization, which prevents long-distance coupling. The algorithm is left with no other choice but block coupling. I show that with or without L1 regularization, the result is invariate. Therefore, L1 regularization does not add meaningful improvements to the result besides restricting the deep learning algorithm in ways that support the authors' claim.

<img width="857" alt="Screen Shot 2020-02-21 at 12 59 59 AM" src="https://user-images.githubusercontent.com/20875827/75019955-a3286980-5446-11ea-8dfd-59f7717ff00b.png">
