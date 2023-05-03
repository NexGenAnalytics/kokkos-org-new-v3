---
title: "HPX now available as an experimental backend"
description: ""
excerpt: ""
date: 2019-04-09
lastmod: 2019-04-09
draft: false
weight: 50
images: [kokkos-blog-post1.jpg]
categories: ["News"]
tags: ["blog", "HPX"]
contributors: ["kokkos team"]
pinned: false
homepage: false
---

![kokkos-blog-post1](kokkos-blog-post1.jpg)

We are pleased to announce that Kokkos now has an HPX backend thanks to the work of Mikael Simberg from CSCS. This backend is the first backend capable of providing Kokkos’ asynchronous semantics on CPUs. It is fully functional including the task graph API. If you have time try it out and let us know how it goes. The backend is available on Kokkos’ “develop” branch: [https://github.com/kokkos/kokkos/tree/develop](https://github.com/kokkos/kokkos/tree/develop) and will be part of the Kokkos 3.0 release in May.