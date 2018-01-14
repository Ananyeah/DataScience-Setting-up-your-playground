# HowToAWS
## Data Science 

Data science comprises of: 
- Data - which needs storage
- Science - Statistics and programming, to take inputs, make visualizations, and apply math functions
- Hardware and processing power : big enough to work on big data
- Domain knowledge and a problem to solve.

## Statistics and Programming

There are several languages and libraries that can be used to program and solve data science problems.
In this case, we choose R. 

What's good about R?
- R was written by statisticians and is preferred by statisticians.
- R has functional procedures. Strong concise, computationally efficient ways to work with data and statistics.
- There's a community and resources to help learn and grow.
- There are IDE's available
- It is free, easy to use and open source
- Takes vectors as inputs
- Libraries for data science are more updated and large compared to it's competitors
- Multithreading and Asynchronous functions

Some concerns around R:
- R was originally written for running from a stand-alone system
- To solve computationally intensive, or huge data sets, one might have to learn syntax and use the enterprise version like Microsoft R which is not free to be used in production environments.

Python as an alternate :
- Python does more than data science and programmers are familiar with the syntax.
- It also has strong functions for data munging, but might not be as strong in single line statistical functions or a library as extensive as R. It is quickly matching up to R.
- Python is considered more readable.

Scala as an alternate:
Scala is also argued to be better than Python in some aspects, especially in conjunction with Spark.

The general thought though is to be aware of and ready to use the tool/language best fit for a problem.

For this setup, we go with R.

## Jupyter Notebook:

It's possible to use R Studio, an IDE to work for R. But Jupyter notebook has become the preferred way to work with R, Python and a pleothora of other languages. Why?

- It's readable, where code, results, images, documentation can all be grouped in one place.
- It can be shared and executed line by line on a browser through a neat interactive programming UI.
- It can be used as a template, that can be easily modified and debugged.

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/Ananyeah/HowToAWS/blob/master/terminal.png =100x20 "Laptop with R installed"

## Setting up AWS EC2 and configuring it with Docker and Jupyter

Schema describing the data science infrastructure built using AWS, Docker, Jupyter, and R 


We could be running R from the comma


reproduce the series of steps required to launch and configure their own cloud-based data science platform
Goals
Create a detailed outline of the steps required to configure your own Jupyter Data Science Notebook Server on Amazon Web Services. The idea is that you would be able to revisit these instructions some arbitrary amount of time from now and be able to bring the server online without consulting any additional documentation.

You will need to account for:

SSH keys
Amazon EC 2
Security Groups
AWS Operating System
Docker Installation
Obtaining the correct Docker image
Running the correct Docker image as a container
Jupyter notebook security concerns
Anything else I may have forgotten ...
Create at least one diagram of your overall system.
A detailed budget of the costs of running a Jupyter Data Science Notebook Server for three months using at least three different kinds of EC 2 instances.
Solution
The final submission should be in the form of a Github Repository containing a README.md document.
