---
layout: post
title: "基于Simulink的永磁同步电机控制系统设计与仿真"
date: 2025-10-04
author: "Zhou Heng"
categories: notes 
tags: [notes]
image: 2025-10-04-FOC-Simulink-永磁同步电机控制系统设计与仿真/FOC仿真模型图.jpg
permalink: /基于Simulink的永磁同步电机控制系统设计与仿真/
---


本文介绍了基于Simulink的永磁同步电机控制系统设计与仿真方法。

## 系统概述
永磁同步电机控制系统采用FOC（Field Oriented Control）控制策略，通过Simulink进行建模和仿真。

本文采用的是𝑖𝑖𝑑𝑑 = 0的控制方法，由于𝑑𝑑𝑑𝑑轴电流内环具有对称性和具有相似的系统
特性，下面仅分析𝑑𝑑轴电流 PI 调节器的参数整定方法，𝑑𝑑轴电流 PI 调节器的参数整定和
𝑑𝑑轴类似。

{% include pdf_embed.html pdf_url="/assets/pdf/基于Simulink的永磁同步电机控制系统设计与仿真.pdf" %}

