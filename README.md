# Parallel Programming Scala

Functional Programming in Scala Specialisation - Parallel Programming Scala

## About the specialisation

This Specialization provides a hands-on introduction to functional programming using the widespread programming language, Scala. It begins from the basic building blocks of the functional paradigm, first showing how to use these blocks to solve small problems, before building up to combining these concepts to architect larger functional programs. Functional paradigm facilitates parallel and distributed programming, and through a series of hands on examples and programming assignments, you'll learn how to analyze data sets small to large; from parallel programming on multicore architectures, to distributed programming on a cluster using Apache Spark.

A final capstone project will allow you to apply the skills you learned by building a large data-intensive application using real-world data.

## About the course

Manipulating big data distributed over a cluster using functional concepts is rampant in industry, and is arguably one of the first widespread industrial uses of functional ideas. This is evidenced by the popularity of MapReduce and Hadoop, and most recently Apache Spark, a fast, in-memory distributed collections framework written in Scala. In this course, we'll see how the data parallel paradigm can be extended to the distributed case, using Spark throughout. We'll cover Spark's programming model in detail, being careful to understand how and when it differs from familiar programming models, like shared-memory parallel collections or sequential Scala collections. Through hands-on examples in Spark and Scala, we'll learn when important issues related to distribution like latency and network communication should be considered and how they can be addressed effectively for improved performance.

Learning Outcomes. By the end of this course you will be able to:

- read data from persistent storage and load it into Apache Spark,
- manipulate data with Spark and Scala,
- express algorithms for data analysis in a functional style, 
- recognize how to avoid shuffles and recomputation in Spark,

## Syllabus 



*Getting Started + Spark Basics - Week 1 :* Get up and running with Scala on your computer. Complete an example assignment to familiarize yourself with our unique way of submitting assignments. In this week, we'll bridge the gap between data parallelism in the shared memory scenario (learned in the Parallel Programming course, prerequisite) and the distributed scenario. We'll look at important concerns that arise in distributed systems, like latency and failure. We'll go on to cover the basics of Spark, a functionally-oriented framework for big data processing in Scala. We'll end the first week by exercising what we learned about Spark by immediately getting our hands dirty analyzing a real-world data set..

*Reduction Operations & Distributed Key-Value Pairs - Week 2 :* This week, we'll look at a special kind of RDD called pair RDDs. With this specialized kind of RDD in hand, we'll cover essential operations on large data sets, such as reductions and joins.

*Partitioning and Shuffling - Week 3 :* This week we'll look at some of the performance implications of using operations like joins. Is it possible to get the same result without having to pay for the overhead of moving data over the network? We'll answer this question by delving into how we can partition our data to achieve better data locality, in turn optimizing some of our Spark jobs.

*Structured data: SQL, Dataframes, and Datasets - Week 4 :* 
With our newfound understanding of the cost of data movement in a Spark job, and some experience optimizing jobs for data locality last week, this week we'll focus on how we can more easily achieve similar optimizations. Can structured data help us? We'll look at Spark SQL and its powerful optimizer which uses structure to apply impressive optimizations.


**Assignment deatails are broken down in each week's folder.**
