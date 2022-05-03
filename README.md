---
title: 🏡 Home
permalink: /
nav_order: 1
---

# Optimization methods. MSAI 2022

The course is a summary of state-of-the-art results and approaches in solving applied optimization problems. Despite the focus on applications, the course contains the necessary set of theoretical foundations to understand why and how given methods work.

Classes are taken online twice a week for an hour and a half. In the lecture session a brief theoretical introduction to the topic is discussed, in the practical interactive session students solve problems on the topic on their own with Q&A.

## Program

Introductory session. [📝 Notes](/notes/intro_info.pdf). [📼 Video](https://youtu.be/Q7e4brrZgww)

### Week 1

<table>
<thead>
  <tr>
    <th>🦄 Lecture</th>
    <th>🏛 Seminar</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Brief recap of matrix calculus. <br> <a href="/presentations/1_1.pdf" class="btn">📄 presentation </a> <a href="/notes/1_1.pdf" class="btn">📝 notes</a> <a href="https://youtu.be/Ia0UfweJk5o" class="btn">📼 video</a></td>
    <td>Examples of matrix and vector derivatives. <br> <a href="https://youtu.be/akVc3ydJBtU" class="btn">📼 video</a> <a href="https://colab.research.google.com/github/MerkulovDaniil/msai22/blob/main/notebooks/1_1.ipynb" class="btn">🐍 code</a> </td>
  </tr>
  <tr>
    <td>Idea of automatic differentiation. <br> <a href="/presentations/1_2.pdf" class="btn">📄 presentation</a> <a href="/notes/1_2.pdf" class="btn">📝 notes</a>  <a href="https://colab.research.google.com/github/MerkulovDaniil/msai22/blob/main/notebooks/1_2_Autograd.ipynb"  class="btn">🐍 code</a> <a href="https://youtu.be/xKRWNgEPYNo" class="btn">📼 video</a></td>
    <td>Work with automatic differentiation libraries - jax, pytorch, autograd. <br> <a href="https://youtu.be/akVc3ydJBtU?t=4253" class="btn">📼 video</a><a href="https://colab.research.google.com/github/MerkulovDaniil/msai22/blob/main/notebooks/1_2.ipynb"  class="btn">🐍 code</a></td>
  </tr>
</tbody>
</table>

### Week 2

<table>
<thead>
  <tr>
    <th>🦄 Lecture</th>
    <th>🏛 Seminar</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Markowitz portfolio theory <br> <a href="/presentations/2_1.pdf" class="btn">📄 presentation </a> <a href="/notes/2_1.pdf" class="btn">📝 notes</a> <a href="https://youtu.be/SV-NimfpmQw" class="btn">📼 video</a><a href="https://colab.research.google.com/github/MerkulovDaniil/msai22/blob/main/notebooks/2_1_Markowitz_portfolio.ipynb" class="btn">🐍 code</a> </td>
    <td>Building a portfolio based on a real-world data. <br> <a href="https://youtu.be/Fqfw0ADRbpk" class="btn">📼 video</a> <a href="https://colab.research.google.com/github/MerkulovDaniil/msai22/blob/main/notebooks/2_1.ipynb" class="btn">🐍 code</a> </td>
  </tr>
</tbody>
</table>

### Week 3

<table>
<thead>
  <tr>
    <th>🦄 Lecture</th>
    <th>🏛 Seminar</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Applications of linear programming. <br> <a href="/presentations/3_1.pdf" class="btn">📄 presentation</a> <a href="/notes/3_1.pdf" class="btn">📝 notes</a> <a href="https://youtu.be/X14e-bFCsac" class="btn">📼 video</a><a href="https://colab.research.google.com/github/MerkulovDaniil/msai22/blob/main/notebooks/3_1_LP.ipynb" class="btn">🐍 code</a> </td>
    <td>LP applications exercises: selecting TED talks as LP, production planning. <br> <a href="https://youtu.be/jsJrTo0qYnA" class="btn">📼 video</a><a href="https://colab.research.google.com/github/MerkulovDaniil/msai22/blob/main/notebooks/3_1.ipynb"  class="btn">🐍 code</a></td>
  </tr>
</tbody>
</table>

### Week 4

<table>
<thead>
  <tr>
    <th>🦄 Lecture</th>
    <th>🏛 Seminar</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Zero order methods: simulated annealing, evolutionary algorithms, genetic algorithm. Idea of Nelder Mead algorithm. <br> <a href="https://colab.research.google.com/github/MerkulovDaniil/optim/blob/master/assets/Notebooks/Global_optimization_illustration.ipynb" class="btn">🐍 code</a> <br> ML models hyperparameter search with nevergrad <a href="https://colab.research.google.com/github/MerkulovDaniil/optim/blob/master/assets/Notebooks/Nevergrad.ipynb" class="btn">🐍 code</a> and optuna <a href="https://colab.research.google.com/github/MerkulovDaniil/optim/blob/master/assets/Notebooks/optuna_intro.ipynb" class="btn">🐍 code</a>.<br> <a href="/presentations/4.pdf" class="btn">📄 presentation</a> <a href="/notes/4.pdf" class="btn">📝 notes</a> <a href="https://youtu.be/7l2CCEeHnEQ" class="btn">📼 video</a></td>
    <td>ML models Hyperparameter search with optuna and keras. <br> <a href="https://youtu.be/jsJrTo0qYnA" class="btn">📼 video</a><a href="https://colab.research.google.com/github/MerkulovDaniil/optim/blob/master/assets/Notebooks/optuna_keras.ipynb" class="btn">🐍 code</a></td>
  </tr>
</tbody>
</table>

### Week 5

<table>
<thead>
  <tr>
    <th>🦄 Lecture</th>
    <th>🏛 Seminar</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Newton method. <br> <a href="https://colab.research.google.com/github/MerkulovDaniil/optim/blob/master/assets/Notebooks/Newton.ipynb" class="btn">🐍 code</a> <br> Quasi-Newton methods. <a href="https://colab.research.google.com/github/MerkulovDaniil/optim/blob/master/assets/Notebooks/Quasi_Newton.ipynb" class="btn">🐍 code</a><br> <a href="/presentations/5.pdf" class="btn">📄 presentation</a> <a href="/notes/5.pdf" class="btn">📝 notes</a> <a href="https://youtu.be/uXy7EyQZLJA" class="btn">📼 video</a></td>
    <td>Implementation of the damped Newton method. Finding the analytical center of a set. Convergence study. Comparison with other methods. Benchmarking of quasi-Newtonian methods. <br> <a href="https://youtu.be/qQ1xhhH0GrU" class="btn">📼 video</a><a href="https://colab.research.google.com/github/MerkulovDaniil/optim/blob/master/assets/Notebooks/Newton_Quasi_Newton_exercises.ipynb" class="btn">🐍 code</a></td>
  </tr>
</tbody>
</table>


### Week 6

<table>
<thead>
  <tr>
    <th>🦄 Lecture</th>
    <th>🏛 Seminar</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Stochastic gradient descent method. Batches, epochs, schedulers. Nesterov Momentum and Polyak Momentum. Accelerated gradient method. Adaptive stochastic methods. Adam, RMSProp, AdaDelta.<br> <a href="https://colab.research.google.com/github/MerkulovDaniil/optim/blob/master/assets/Notebooks/SGD_and_variations.ipynb" class="btn">🐍 code</a><br> <a href="/presentations/6.pdf" class="btn">📄 presentation</a> <a href="/notes/6.pdf" class="btn">📝 notes</a> <a href="https://youtu.be/zCbPs8K3U3g" class="btn">📼 video</a></td>
    <td>A convergence study of the SGD. Hyperparameter tuning. Convergence study of accelerated methods in neural network training.  Convergence study of adaptive methods in neural network training. <br> <a href="" class="btn">📼 video</a><a href="https://colab.research.google.com/github/MerkulovDaniil/optim/blob/master/assets/Notebooks/SGD_timeseries.ipynb" class="btn">🐍 code</a></td>
  </tr>
</tbody>
</table>

### Week 7

<table>
<thead>
  <tr>
    <th>🦄 Lecture</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>The landscape of the loss function of a neural network. Neural network fine-tuning aka transfer learning. Neural style transfer. <br> <a href="https://colab.research.google.com/github/MerkulovDaniil/optim/blob/master/assets/Notebooks/NN_applications.ipynb" class="btn">🐍 code</a> Using GANs to train density distribution on the plane. Generating new pokemons using deep neural networks. <br> <a href="https://colab.research.google.com/github/MerkulovDaniil/optim/blob/master/assets/Notebooks/GANs.ipynb" class="btn">🐍 code</a> Visualizing the projection of the loss function of a neural network on a straight line and a plane. <br> <a href="https://colab.research.google.com/github/MerkulovDaniil/optim/blob/master/assets/Notebooks/NN_loss_surface.ipynb" class="btn">🐍 code</a> <a href="https://youtu.be/nKDa2N071Vw" class="btn">📼 video</a> </td>
  </tr>
</tbody>
</table>

* [📧 Chat](https://t.me/+kokUwlZ9ClBlYWZi)
* [👨‍💻 Github](https://github.com/MerkulovDaniil/msai22)
