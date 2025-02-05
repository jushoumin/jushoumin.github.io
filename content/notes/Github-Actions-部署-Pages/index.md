---
date: "2025-02-06T00:49:25+08:00"
draft:  false
title: "Github Actions 部署 Pages"
summary: ""
categories: ["github actions"]
---
当我部署网站到 Github Pages 时发现在 Actions 中多了一个 pages-build-deployment 进程，这是 Github Pages 默认提供的针对 Jekyll 生成器的部署 Actions。使用 Hugo 等生成器，需要在仓库的  Settings - Pages - Build and deployment - Source 从 Deploy from a brach 切换到 Github Actions 以关闭 pages-build-deployment 进程。

![1738775485571](img/1738775485571.png)

引用

[Stack Overflow | GitHub actions: going through with pages-build-deployment](https://stackoverflow.com/questions/70631168/github-actions-going-through-with-pages-build-deployment)
