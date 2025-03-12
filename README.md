# DeepRheoFlow-python4ML

The objective of this workshop is to empower engineers with low code experience to be able to use and create Machine Learning applications.

This workshop aims to present a basic overview for **operating and creating Machine Learning models**.

## High Level Programming foundation

First, we must define a ground level to start building concepts from.

The following list of topics are required for a deeper understanding of the concepts later presented:

- [Data types](https://www.w3schools.com/python/python_datatypes.asp)
- Array and tensor indexing
- Functional programming and algorithms (scripts)*
- Object oriented (high level abstraction)*

[*quick reference](https://www.datacamp.com/tutorial/functional-programming-vs-object-oriented-programming)

## Python frameworks

### Why python

- Versatile
- Lower learning barrier
- Wide community

### Environment management

Environment management in Python is essential for maintaining clean, **isolated project dependencies**. 

It allows developers to create separate virtual environments for different projects, ensuring that package versions and dependencies do not conflict. 

This is particularly useful when working on multiple projects with varying requirements or when collaborating with others.

Python uses pip (Python Package Installer) as its default tool for installing and managing dependencies. 

Pip works with the Python Package Index [PyPI](https://pypi.org/) to fetch and install libraries, making it the most widely used package manager.

It allows developers to install packages using simple commands like:

```bash
pip install matplotlib
pip install -r requirements.txt
```

However, pip alone does not handle virtual environments or dependency resolution efficiently, leading to the rise of more advanced tools like [Poetry](https://python-poetry.org/) and [uv](https://github.com/astral-sh/uv).

In this workshop **we will use Poetry** to manage our environment.

### Data sampling

Data may come from all different kinds of sources, from experimental procedures, numerical results and so on.

In many cases, the **data must be cleaned before being processed**, such as removing noise, cleaning NaN (not a number) rows and values, or joining data from multiple sources.

Tools for manipulating and mapping arrays are essential in this step.

Commonly used Python frameworks in this step are:
- [Numpy](https://numpy.org/): Efficient vectorized operations
- [Pandas](https://pandas.pydata.org/): Data analysis tool and data operations

### Data processing

After the data is collected, it is then processed. Common processing operations include statistical calculations or data scale transformation.

Commonly used Python frameworks in this step are:
- [Numpy](https://numpy.org/): Efficient vectorized operations
- [Pandas](https://pandas.pydata.org/): Data analysis tool
- [Scipy](https://scipy.org/): Mathematical operations

#### Machine Learning

Just like almost everything in python, there are open source libraries to manage machine learning.

Commonly used Python frameworks for machine learning:
- [Tensorflow](https://www.tensorflow.org/?hl=pt-br)
- [PyTorch](https://pytorch.org/)
- [DeepXDE](https://deepxde.readthedocs.io/en/latest/)
- [NVIDIA modulus](https://github.com/NVIDIA/modulus)

They can be really useful to instantiante, train, and iterate a neural network.

### Data visualization

Data is only useful when it is well presented.

After being processed, there are some tools to help visualizing results:
- [VTK](https://docs.vtk.org/en/latest/api/python.html): "Paraview API", geometric operations, data structures, processing functions.
- [Matplotlib](https://matplotlib.org/): Very popular plotting library
- [Pyvista](https://docs.pyvista.org/): Very useful wrapper for VTK

## Collaboration Tools

- [GitHub](https://github.com/pabloharbar/DeepRheoFlow-python4ML)
- [Briefer](https://briefer.cloud/)

## Instructions

Make sure to have Poetry installed to manage the environment:

```bash
pip install poetry
```

After that, install all workshop's dependencies:

```bash
poetry install
```

## Contact

Need any help? I will be happy to assist! Send an e-mail to <pablopenas@alunos.utfpr.edu.br>