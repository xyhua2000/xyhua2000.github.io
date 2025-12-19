---
layout: post
title: "使用iseq从ENA、SRA下载数据"
date: 2025-12-18
tags: [iseq, ENA, SRA]
toc: false
comments: false
author: xyhua
---

使用iseq下载数据<!-- more -->

## 创建并激活环境
```bash
mamba create -n iseq iseq
mamba activate iseq
```

## 下载
```bash
iseq -i acc_ids.txt -g -a -t 18 -p 10 -d ena -o data
```
