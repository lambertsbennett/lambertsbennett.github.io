---
layout: default
---
[Resume](./resume.md) &emsp; [Projects](./projects.md) &emsp; [Publications](./pubs.md)

## Current Projects
Although I can't speak about specifics, I am involved in some of the following activities:
* Building retrieval-augmented generation systems for question answering.
* ETL pipelines with Spark in the Databricks environment.
* Computer vision for automotive applications.
* Various data engineering projects.
* Tools: Python, Spark, SQL, and many others!

## Prior Open Source Projects
### Combining Argo Workflows with Great Expectations
* Wrote a medium article [(Link)](https://medium.com/towards-data-science/data-validation-with-great-expectations-and-argo-workflows-b8e3e2da2fcc) about using Great Expectations for data validation using Argo Workflows.
* Tools: Argo Workflows, Great Expectations, Kubernetes, Docker, Python

### Concurrent Sequence Preprocessing
* In molecular biology workflows one must commonly compute all possible k-mers from a biological sequence. A k-mer is a string of length k that occurs naturally in the sequence. For example a 4-mer could be 'ATCG'.
* This can be a very slow process, but using Golang I was able to create a very performant concurrent k-mer pre-processing tool. [(Link)](https://github.com/lambertsbennett/GoKmer)
* Tools: Golang

### Multi-resolution Local Binary Patterns
* MrLBP is a technique that can be used as a precursor to binning microbial genomes. I found that the published version of this approach was quite slow, so I re-implemented it in Golang and took advantage of its great concurrency model. [(Link)](https://github.com/lambertsbennett/GoMrLBP)
* Tools: Golang

### Ph.D. Research
* During my Ph.D. work I generated mass amounts of microscopy data. I then used MATLAB to automatically process the images and count cells.
* To analyze environmental data I used a combination of R ecology packages and custom MATLAB scripts.
* I also had the opportunity to do some robotics work and created underwater instruments that carried out fluid-handling operations. All control was carried out with an Arduino.
* Tools: MATLAB, Arduino, R, SolidWorks
