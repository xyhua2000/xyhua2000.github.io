---
layout: post
title: "关于《动手学深度学习（第二版）》学习笔记系列的目录"
date: 2025-10-27
tags: [AI, catalogue]
toc: false
comments: false
author: xyhua
---

使用iseq下载数据<!-- more -->

## 创建并激活环境

mamba create -n iseq iseq
mamba activate iseq


## 下载文件

iseq -i acc_ids.txt -g -a -t 18 -p 10 -d ena -o data
