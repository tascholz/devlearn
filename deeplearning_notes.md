# https://www.deeplearningbook.org/

## 1 Introducction
Solving problems that are easy for people to perform, but hard for people to describe.
Hierarcchy of concepts: Building complicated concepts out of simpler ones (deep learning)

Abstract and formal tasks are easy for a computer, intuitive and subjective tasks are difficult. One of the key problems is getting the knowledge needed to execute these tasks into a computer.

####Knowledge based learning
Hard-coding this knowledge in formal languages with which the computer can reason using logical inference rules. 

####Machine learnning
AI systems acquire their own knowledge by extracting patterns from raw data.
>Each piece of information given to the computer is called a **feature**.

The choice of the representation of the data has an enormous effect on the perfomance of machine learning algorithms.

In **Representation learning** the machine discovers not only the mapping from the representation but also the representation itself. When designingfeatures or algorithms for learning features, the goal is to seperate the factors of variation that explain the observed data (i.e. sex, age etc in speech recognition). This can be too difficult for the computer. Deep learning solves this problem by introducing representations that are expressed in terms of other, simpler representations.

!MLP multilayer percceptron

Each layer of the representation can be thought of as the state of the computer's memory after executing another set of instructions in parallel.

In 2016 acceptable performance was achieved with arpund 5000 labeled examples per category and matched or exceeded human performance with at least 10 million labeled examples. An important research area focuses on taking advantage of large quantities of unlabeled examples.


The main reasons for the improving of deep learning are the increase in available data and complexer models due to faster CPU's and general purpose GPU's

## 2 Linear Algebra
**Scalar**: single number
**Vector**: an array of numbers, arranged in order
**Matrix**: a 2D-array of numbers
**Tensor**: any array of numbers arranged on a grid with a variable number of axes
