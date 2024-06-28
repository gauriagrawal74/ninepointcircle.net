---
tags: post
title: This is my second post
layout: blog
---

# This is a heading

Aligned math?

\begin{align}
    x &= y + z \\
    y &= z + x \\
\end{align}

This isn't working. Why? Because \\ is parsed as a single \.
This is why we have to do 

\begin{align}
    x &= y + z \\\\
    y &= z + x \\\\
\end{align}

Other than, just simple math ($x + 4$)