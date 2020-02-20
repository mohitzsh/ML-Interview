# ML-Interview
This is a list of resources I found useful during my preparation for interviews. Broadly speaking, I interviewd for three different profiles: Machine Learning Engineer, Applied Scientist and Quantitative Researcher. 

NOTE: All these profiles usually include multiple "traditional" programming/algorithm rounds, and for that, I relied upon mild leetcoding spree, spread over a period of 3 months. 

## Classical Machine Learning

+ A very good (slighly advanced) course on Machine Learning by Alex Smola. [Link](http://alex.smola.org/teaching/cmu2013-10-701/stats.html) 
+ Perhaps everything that you'll ever need to know for the interview sake. [Link](http://alumni.media.mit.edu/~tpminka/statlearn/glossary/) 
+ Generative vs Discriminative Classifiers (you should know the difference, and tradeoffs when choosing one over the other) [Link](http://www.cs.cmu.edu/~tom/mlbook/NBayesLogReg.pdf)
+ Gradient Boosted Trees [Link](https://homes.cs.washington.edu/~tqchen/pdf/BoostedTree.pdf)
+ ROC and AUC (I like this video) [Link](https://www.youtube.com/watch?v=OAl6eAyP-yo&t=729s)
+ Clustering (from Ryan Tibshirani's Data Mining course, other slides are really good as well) [Link 1](https://www.stat.cmu.edu/~ryantibs/datamining/lectures/04-clus1.pdf) [Link 2](https://www.stat.cmu.edu/~ryantibs/datamining/lectures/05-clus2.pdf) [Link 3](https://www.stat.cmu.edu/~ryantibs/datamining/lectures/06-clus3.pdf)
+ Good old Linear Regression. [Link](https://www.cs.cmu.edu/~epxing/Class/10715/lectures/lecture2-LR.pdf)
+ L0, L1 and L2 regularization (Subset Selection, Lasso and Ridge Regression), a comparison. The Elements of
Statistical Learning, Trevor Hastie, Robert Tibshirani, Jerome Friedman, 2nd Edition, Section 3.4.3 [Link](https://web.stanford.edu/~hastie/ElemStatLearn/)

## Deep Learning
+ Why tanh for Recurrent Networks [Link](https://www.cs.cmu.edu/~bhiksha/courses/deeplearning/Fall.2015/slides/lec10.recurrent.pdf)
+ Receptive Fields in CNNs [Link](https://medium.com/mlreview/a-guide-to-receptive-field-arithmetic-for-convolutional-neural-networks-e0f514068807)
+ For everything Convolution [Link](https://arxiv.org/pdf/1603.07285.pdf) 
+ For eveything Gradient Descent [Link](https://ruder.io/optimizing-gradient-descent/)
+ Adaptive Learning rates in SGD [Link](https://www.cs.cornell.edu/courses/cs6787/2019fa/lectures/Lecture8.pdf)
+ Backpropagation in Python, Andrej Karpathy [Link](https://medium.com/@karpathy/yes-you-should-understand-backprop-e2f06eab496b)

## Probability and Statistics
+ As the title would say, "Generalized Linear Models, abridged".[Link](https://bwlewis.github.io/GLM/)
+ A good course to cover Statistics [Link](https://ocw.mit.edu/courses/mathematics/18-650-statistics-for-applications-fall-2016/lecture-slides/) 
+ Basic Statistics: Introduction to Mathematical Statistics, Hogg, McKean and Craig, Chapters 1-4. [Link](https://www.amazon.com/Introduction-Mathematical-Statistics-Robert-Hogg/dp/0321795431)
+ Introduction to Hypothesis Testing: Introduction to Mathematical Statistics, Hogg, McKean and Craig, Section 4.5-4.6 [Link](https://www.amazon.com/Introduction-Mathematical-Statistics-Robert-Hogg/dp/0321795431)
+ Examples of Uncorrelated vs Independent Random Variable [Link](https://www.stat.cmu.edu/~cshalizi/uADA/13/reminders/uncorrelated-vs-independent.pdf)
+ Discrete time Markov Chains,Poisson Processes, Renewal Theory Adventures in Stochastic Processes, 2nd Edition, Sidney Resnick [Link](http://do.unicyb.kiev.ua/iksan/lectures/Adventures.pdf) TODO: Add a link to more succint notes.
+ Q-Q Plots [Link](https://en.wikipedia.org/wiki/Q%E2%80%93Q_plot)

## Assorted Mathematics
+ Some facts about Symmetric Matrices. [Link](http://www.doc.ic.ac.uk/~ae/papers/lecture05.pdf)
+ Bare minimum SVD by Gilbert Strang. [Link](https://mitocw.ups.edu.ec/courses/mathematics/18-06sc-linear-algebra-fall-2011/positive-definite-matrices-and-applications/singular-value-decomposition/MIT18_06SCF11_Ses3.5sum.pdf)
+ SVD and PCA in real-life. [Link](https://jeremykun.com/2011/07/27/eigenfaces/)
+ If you are not sure how SVD and PCA are related. [Link](https://stats.stackexchange.com/questions/134282/relationship-between-svd-and-pca-how-to-use-svd-to-perform-pca)
+ If you want to brush up on Chain Rule (or if you are like me and get confused between gradient and derivative notation) [Link](http://www.met.reading.ac.uk/~ross/Documents/Chain.pdf).
 [Wikipedia](https://en.wikipedia.org/wiki/Gradient#Derivative) has some useful information as well.
+ Collection of Quantitative Interview problems by Pete Benson, University of Michigan. [Link](https://pbenson.github.io/docs/quantTechnicalQuestions/quantTechnicalQuestions.pdf)
+ Cholesky Factorization [Link](http://www.math.sjsu.edu/~foster/m143m/cholesky.pdf)
+ QR Factorization [Link](https://www.math.usm.edu/lambers/mat610/sum10/lecture9.pdf)

## System Design (for ML) 
+ Structure for Google Index [Link](http://infolab.stanford.edu/~backrub/google.html)
+ Recommender Systems, Xavier Amatriain [Link 1](https://www.youtube.com/watch?v=mRToFXlNBpQ)
[Link 2](https://www.youtube.com/watch?v=bLhq63ygoU8)
+ News Feed Ranking @ Facebook (Lars Backstrom) [Link](https://www.youtube.com/watch?v=Xpx5RYNTQvg)

## Uncategorized
+ Sobel Operator [Link](https://en.wikipedia.org/wiki/Sobel_operator)
+ You have a fair Die, and you can choose to roll it up to 3 times. Whenever you decide to stop, the number that’s facing up is your score. What strategy would you choose to maximize your score? What is the expected score with your strategy? If you are given more than 3 chances, can you improve your score?