---
title: "Compyle: a Python package for parallel computing"
collection: publications
permalink: /publication/2020-compyle
excerpt: 'Compyle allows users to execute a restricted subset of Python on a variety of HPC platforms. 
It is an embedded domain-specific language (eDSL) for parallel computing. It currently supports 
multi-core execution using Cython, and OpenCL and CUDA for GPU devices. Users write code in a 
restricted subset of Python that is automatically transpiled to high-performance Cython or C. 
Compyle also provides a few very general purpose and useful parallel algorithms that allow 
users to write code once and have them run on a variety of HPC platforms.'
date: 2020-07-01
venue: 'Proceedings of the 19th Python in Science Conference'
citation: 'Aditya Bhosale, & Prabhu Ramachandran (2020). Compyle: a Python package for parallel computing. In Proceedings of the 19th Python in Science Conference (pp. 32 - 39).'
---

Compyle allows users to execute a restricted subset of Python on a variety of HPC platforms. 
It is an embedded domain-specific language (eDSL) for parallel computing. It currently supports 
multi-core execution using Cython, and OpenCL and CUDA for GPU devices. Users write code in a 
restricted subset of Python that is automatically transpiled to high-performance Cython or C. 
Compyle also provides a few very general purpose and useful parallel algorithms that allow 
users to write code once and have them run on a variety of HPC platforms.

In this article, we show how to implement a simple two-dimensional molecular dynamics (MD) simulation 
package in pure Python using Compyle. The result is a fully parallel program that is relatively 
easy to implement and solves a non-trivial problem. The code transparently executes on multi-core 
CPUs and GPGPUs allowing simulations with millions of particles. A 3D MD code is also provided and 
compares very favorably with a well known, open source, molecular dynamics package.

[Download paper here](http://conference.scipy.org/proceedings/scipy2020/pdfs/compyle_pr_ab.pdf)
