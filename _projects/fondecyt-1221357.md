---
title: Logo Project

title: Fondecyt Regular 1221357

description: |
  Combining Tensor Cores with Ray-Tracing Cores for GPU-based Simulations

people:
  - prof-cnavarro
  - prof-hferrada
  - prof-nhitschfeld
  - fquezada

layout: project
image: "/img/fondecyt1221357.png"
last-updated: 2022-03-05
---
Combining Tensor Cores with Ray-Tracing Cores for GPU-based Simulations

## ABSTRACT
The main objective of this proposal is to develop new approaches that can improve the performance and
energy-efficiency of GPU-based scientific simulations, by combining tensor-core with RT-core operations. The
hypothesis is that a significant part of the work involved in GPU-based scientific simulations can be mapped
as fast MMA (tensor-core) and space-search operations in a BVH data structure (RT-core), improving their
performance and energy-efficiency. Furthermore, the combination of these cores can produce new energy-efficient
computational patterns. The specific objectives consist of redesigning frequently used GPU computational
patterns such as nearest-neighbors exploration in structured-space, nearest-neighbors search in unstructured-
space, sorting/min/max, elementary graph operations and to compose a new computational pattern for semi-
structured space. The methodology is based on representing local/short-range computations as structured-
space tensor-core MMA operations, codifying work into the row-column computations, and global/long-range
computations as unstructured-space RT-core ray-triangle intersections. In addition to the computational patterns
already mentioned in the specific objectives, the combination of these two approaches would allow the formulation
of a new computational pattern for semi-structured-space simulations. The expected results are a major
improvement in performance and energy-efficiency for the computational patterns, allowing the study of larger
simulations as well as enable real-time performance for some of them. Numerical precision will be studied as well,
finding how much does the problem size, data types and data distributions affect the result. The importance
of this research is that the improvements produced on each computational pattern affects not only one specific
scientific simulation, but families of simulations from the different fields of science.
