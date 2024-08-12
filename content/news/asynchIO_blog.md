---
title: "MURaM scientific model deployed asynchronous IO blog published on Medium"
author: "Haiying Xu"
date: 2024-07-31T20:48:10-06:00
type: news
image: "images/blog/asynchIO.jpg"
feature_image: "images/blog/asynchIO.jpg"
---
Haiying Xu recently wrote a blog titled "[Asynchronous I/O in Large-Scale Time-Series Geoscience Simulations](https://medium.com/@haiyingx/asynchronous-io-in-large-scale-time-series-geoscience-simulations-3bf268eee230)" on Medium.com. The blog primarily experimented the ADIOS2 SST Input/Output (I/O) in the MURaM scientific simulation project to enhance performance. SST I/O uses RDMA or WAN communication to stream data asynchronously. It achieved better performance compared to existing MPI-I/O and also facilitated easy conversion of data to C/Fortran order, as well as the ability to rearrange or compress data without reducing performance. This asynchronous I/O approach can significantly improve the efficiency and scalability of large-scale simulations, demonstrating a promising advance in scientific computing.
