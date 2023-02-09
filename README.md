# Introduction

### 说明

最近在学习CUDA，感觉看完就忘，于是这里写一个导读，整理一下重点

主要内容来源于NVIDIA的官方文档[《CUDA C Programming Guide》](https://docs.nvidia.com/cuda/cuda-c-programming-guide/index.html)，结合了另一本书《CUDA并行程序设计 GPU编程指南》的知识。 因此在翻译总结官方文档的同时，会加一些评注，不一定对，望大家讨论指出。

另外，我才不会老老实实的翻译文档，因此细节还是需要从文档里看的。

看完两份文档总的来说，感觉《CUDA C Programming Guide》这本书作为一份官方文档，知识细碎且全面，且是针对最新的Maxwell、Pascal、Volta架构的阐述。但相对来说不够深入，且有关程序设计方面所述甚少。

而《CUDA并行程序设计 GPU编程指南》这本书，讲解的比较深入，不仅阐述了NVIDIA GPU的特性，并且在程序设计方面有比较深入的见解。美中不足的是该书是针对老旧的Tesla、Fermi架构GPU，没有涉及到新架构的新特性。
