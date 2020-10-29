---
title: "羲和"
#author: "Alex Chi"
date: 2020-10-20T13:26:58+08:00
draft: false
menu: "main"
#image: "images/*.jpg"
meta: true
toc: true
categories: []
tags: []
---

一个承载最新技术的渲染器。

## 特性

* 材质（依赖[MDL]）
    * UV
    * 漫反射贴图
    * 金属性
    * 粗糙度
    * 法线贴图
    * 法线强度
    * 自发光
    * 折射率
* 灯光
    * 平行光
    * 点光
    * 射灯
    * 球形光
    * 矩形面光
    * IES
* 摄像机
    * 透视
    * 平视
    * 鱼眼
    * 全景
    * 焦散
* 通用
    * 背景图

## 进展

* [ ] 构建光线追踪基础管线
    * [ ] 整合[OptiX]
* [ ] 构建材质
    * [x] 整合[MDL]
    * [x] 固有色
    * [ ] 漫反射贴图
* 工具
    * [x] 将glTF转换为可加载的FlatBuffers二进制


## 文章

* [“羲和”开发日志（一） 项目介绍](../../posts/xihe-development-log-1st-intro)

[MDL]: https://www.nvidia.com/en-us/design-visualization/technologies/material-definition-language/
[OptiX]: https://developer.nvidia.com/optix
[CUDA]: https://developer.nvidia.com/cuda-toolkit