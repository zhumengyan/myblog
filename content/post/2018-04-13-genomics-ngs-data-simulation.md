---
title: Genomics ngs data simulation
author: zhu mengyan
date: '2018-04-13'
slug: genomics-ngs-data-simulation
categories:
  - Software
  - Paper
tags:
  - Software
  - Review
  - Paper
---

>本文主要基于2016年发表在『Nature Review Genetics』杂志上综述文章『A comparison of tools for the simulation of genomic next-generation sequencing data』。

在学习高通量测序的相关知识的时候，我们往往陷入两个困境：(1)找不到想要的数据;(2)数据太大，难以下载分析。这时，高通量数据模拟的软件就派上用场了。

简单来说，测序数据模拟软件主要用于一下三个方面：
1. planning experiments
2. testing hypotheses
3. benchmarking tools
4. evaluating particular results

```
    The simulation of NGS data can be extremely useful for planning experiments,
testing hypotheses, benchmarking tools and evaluating particular results. 
    Given a reference genome or dataset, for instance,  one can play with
an array of sequencing technologies to choose the best-suited technology and parameters for the particular goal, 
possibly optimizing time and costs. 
    Yet, this is still not the standard practice and researchers often base their choices on 
practical considerations like technology and money availability.
     As shown throughout this Review, simulation of NGS data from known genomes or transcriptomes can be extremely useful 
when evaluating assembly, mapping, phasing or genotyping algorithms exposing their advantages and drawbacks under different circumstances.
```

***
这篇综述文章评估了23个测序数据模拟软件，介绍各自不同的特点，需求及潜在应用，并给出选取合适软件的方法。
![软件列表](https://upload-images.jianshu.io/upload_images/9919584-15071c3706c7090a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



### NGS genomic simulators decision tree.
下面的树状图简单说明了选取不同方法的原则
![emss-70941-f001.jpg](https://upload-images.jianshu.io/upload_images/9919584-c165f712a2ab593b.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### Main characteristics of current NGS technologies
目前不同NGS技术的一些特点。注意，**『X』**表示存在。
![image.png](https://upload-images.jianshu.io/upload_images/9919584-9ee614b1c06c7d5c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### General overview of the sequencing process and steps that can be parameterized in the simulations
![image.png](https://upload-images.jianshu.io/upload_images/9919584-60e1d13975966985.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### General overview of NGS simulation
![image.png](https://upload-images.jianshu.io/upload_images/9919584-e9d96cdf58223443.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### General information about 23 NGS genomic simulators
23种模拟软件的特点
![image.png](https://upload-images.jianshu.io/upload_images/9919584-598b2c2be2808d9f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### Technical information about 23 NGS genomic simulators
![image.png](https://upload-images.jianshu.io/upload_images/9919584-339bce0b17cb1a7f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### Genomic variants
![image.png](https://upload-images.jianshu.io/upload_images/9919584-ea0640ffe2d67937.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



最后，直接给出该文章的online summary:
![image.png](https://upload-images.jianshu.io/upload_images/9919584-d12aaf31118ecc2c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


欢迎大家关注我的微信公众号『生信family』
![qrcode_for_gh_a055c85e7513_258-2.jpg](https://upload-images.jianshu.io/upload_images/9919584-0693650973f73c38.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)









