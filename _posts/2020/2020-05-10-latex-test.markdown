---
layout: "post"
title: "Testing LaTeX"
date: "2020-05-07"
excerpt: "Just a quick test to make sure LaTeX works."
comments: true
---
I read [this tutorial](http://flennerhag.com/2017-01-14-latex/) and here's what I was able to do!

Inline: $a+b>c$.

A quick equation:
$$\begin{equation} a^2 + b^2 = c^2. \end{equation}$$
$\textbf{Problem.}$ Prove that $\sqrt{2}$ is irrational.

$\textbf{Proof.}$ Assume that $\sqrt{2}$ is a rational number in the form $\frac{a}{b}$ when written in lowest terms. Then
$$\begin{equation} \sqrt{2} = \frac{a}{b}. \end{equation}$$
Squaring both sides, we get
$$\begin{equation} 2=\frac{a^{2}}{b^{2}}. \end{equation$$ 
Rearranging this, we get
$$\begin{equation} a^{2}=2b^{2}. \end{equation}$$
If $a$ is odd, then $a^{2}$ (the left side) becomes odd. However, the right side is even, so $a$ must be even. If we check, squaring an even number $a$ indeed does yield another even number, so $a$ is actually even. We can write an even number $x$ as $x = 2y$ for some integer $y$. Then, we can also write $a$ as $a = 2c$ for some $c$. Then our equation from before, $a^{2} = 2b^{2}$ becomes
$$\begin{equation} (2c)^{2} = 2b^{2}. \end{equation}$$
Expanding the left side, we get
$$\begin{equation} 4c^{2} = 2b^{2}. \end{equation}$$
and dividing by 2, the equation becomes
$$\begin{equation} 2c^{2} = b^{2}. \end{equation}$$
By the same logic as before, $b$ must be even. If both $a$ and $b$ are even, they are both divisible by 2. Then, this contradicts our assumption that $\frac{a}{b}$ is in lowest form. Therefore, our original assumption that $\sqrt{2}$ is rational must be false. If $\sqrt{2}$ is not rational, it must be irrational. Therefore, $\sqrt{2}$ is irrational.

(A sneak peak of a future handout on proofs!)
